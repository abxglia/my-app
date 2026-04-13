# Transaction History

| Field | Value |
|-------|-------|
| Type | `dune-transaction-history` |
| ID | `d6152b57` |
| Category | analytics |
| Tags | dune, transactions, history, wallet |
| Description | Wallet transaction history |

## Configuration

| Setting | Value |
|---------|-------|
| Blockchain | arbitrum |
| Limit | 100 |
| Generate U I | Enabled |

## Environment Variables

| Key | Description | Required | Secret | Default |
|-----|-------------|----------|--------|---------|
| `DUNE_API_KEY` | Dune Analytics API key for blockchain data queries | Yes | Yes |  |

## File Structure

This component would generate the following files:

- `dune-client.ts` (frontend-lib)
- `useTransactionHistory.ts` (frontend-hooks)
- `TransactionHistory.tsx` (frontend-components)
- `dune-transaction-history.md` (docs)

## Integration Points

**Depends on:**
- Erc721-stylus (`016e1463`)

