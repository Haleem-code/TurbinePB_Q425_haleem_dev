# Solana Counter Program

A minimal Anchor-based Solana progra (a simple counter).



## Quick Start
From the `counter/` directory:
    - Build the program:
      ```
      anchor build
      ```
    - Run the test suite (starts a local validator, builds and deploys automatically):
      ```
      anchor test
      ```
    - Optionally deploy to a localnet / cluster:
      ```
      anchor deploy
      ```

## Project layout
counter/
├── programs/  
│   └── counter/  
│       └── src/lib.rs       
├── tests/  
│   └── counter.ts             # TypeScript test
├── Anchor.toml                
└── package.json               


- `anchor test` -


