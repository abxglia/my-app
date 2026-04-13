# Architecture

## Dependency Graph

```mermaid
graph TD
  016e1463["Erc721-stylus (erc721-stylus)"]
  99ebf0cf["Frontend-scaffold (frontend-scaffold)"]
  d6152b57["Dune-transaction-history (dune-transaction-history)"]
  6824e04f["Wallet-auth (wallet-auth)"]
  f3f2cb18["Chain-data (chain-data)"]
  016e1463 --> 99ebf0cf
  99ebf0cf --> 6824e04f
  016e1463 --> d6152b57
  99ebf0cf --> f3f2cb18
```

## Execution / Implementation Order

1. **Erc721-stylus** (`016e1463`)
2. **Frontend-scaffold** (`99ebf0cf`)
3. **Dune-transaction-history** (`d6152b57`)
4. **Wallet-auth** (`6824e04f`)
5. **Chain-data** (`f3f2cb18`)
