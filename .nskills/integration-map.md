# Integration Map

How components connect and what data flows between them.

### Erc721-stylus --> Frontend-scaffold

- **Source**: Erc721-stylus (`016e1463`)
  - Output ports: NFT Contract (contract)
- **Target**: Frontend-scaffold (`99ebf0cf`)
  - Input ports: Contract ABI (contract), Network Config (config)

### Frontend-scaffold --> Wallet-auth

- **Source**: Frontend-scaffold (`99ebf0cf`)
  - Output ports: App Context (config)
- **Target**: Wallet-auth (`6824e04f`)
  

### Erc721-stylus --> Dune-transaction-history

- **Source**: Erc721-stylus (`016e1463`)
  - Output ports: NFT Contract (contract)
- **Target**: Dune-transaction-history (`d6152b57`)
  

### Frontend-scaffold --> Chain-data

- **Source**: Frontend-scaffold (`99ebf0cf`)
  - Output ports: App Context (config)
- **Target**: Chain-data (`f3f2cb18`)
  
