# mini-bitcoin.rs

A minimal Bitcoin-like blockchain implementation in Rust, built for learning and as the first boss in my Full-Stack Cryptographer project.

## Features (v0.1)
- [ ] Block struct with index, timestamp, data, previous_hash, hash, nonce
- [ ] Calculate SHA-256 hash of block
- [ ] Proof-of-Work mining: find hash with N leading zeros (difficulty adjustable)
- [ ] Genesis block creation
- [ ] Adding new blocks with data
- [ ] Blockchain validation (check hashes and links)
- [ ] Simple CLI to interact with the chain

## Stack
- Rust (no external crates for crypto at first, only std and basic sha2 if needed later)
- Learning goals: understand block linking, PoW, and basic Rust ownership/error handling

## Milestones
1. **Day 1-2**: project setup, Block struct, hash function.
2. **Day 3-5**: PoW mining, genesis block, adding blocks.
3. **Day 6-7**: validation, CLI, final polish.
