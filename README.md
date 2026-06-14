# Arweave

Arweave is a permanent decentralized data storage network that enables developers to store data forever with a single upfront payment. It provides REST and GraphQL APIs for uploading data, querying blocks and transactions by tags and metadata, retrieving wallet balances, and accessing the permaweb data ecosystem.

## APIs

| API | Base URL | Description |
|-----|----------|-------------|
| HTTP Node API | https://arweave.net | Submit and retrieve transactions, upload chunks, query network state |
| GraphQL API | https://arweave.net/graphql | Query transaction and block metadata by tags, owners, block height |
| Turbo Upload API | https://turbo.ardrive.io | Managed bundling service with fiat and multi-chain crypto payment |

## Key Concepts

- **AR Token**: Native token; amounts in winstons (1 AR = 10^12 winstons)
- **Permanent Storage**: Pay once; the protocol endowment funds storage indefinitely
- **ANS-104 Bundles**: Pack multiple items into a single Arweave transaction for efficiency
- **Turbo Credits**: Pre-purchased upload credits usable via the managed Turbo service
- **Free Tier**: Uploads under 100 KiB via Turbo are free with no account required

## Documentation

- Developer Docs: https://docs.arweave.org/developers
- Permaweb Cookbook: https://cookbook.arweave.net/
- ar.io Build Docs: https://docs.ar.io/build/
- GraphQL Guide: https://gql-guide.vercel.app/
- GitHub: https://github.com/ArweaveTeam

## Repository Contents

```
apis.yml                  # APIs.json 0.19 provider profile
plans/plans.yml           # Pricing plans and tiers
rate-limits/rate-limits.yml  # Rate limit documentation
finops/finops.yml         # Cost drivers and optimization guidance
```

## Links

- Website: https://www.arweave.org/
- Discord: https://discord.gg/arweave
- Twitter: https://twitter.com/ArweaveTeam
- Blog: https://arweave.medium.com/
- Status: https://status.ar.io/
