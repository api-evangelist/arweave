# Arweave GraphQL API

The Arweave GraphQL API exposes a read-only query interface for searching and retrieving Arweave transaction and block metadata. It allows developers to find transactions by owner address, recipient, tag key/value pairs, bundle ID, block height range, and ingestion time range. Results are returned as cursor-paginated connection sets following the Relay GraphQL cursor specification. The API does not expose mutations — all data writes go through the Arweave REST (HTTP Node) API. No authentication or API key is required; the endpoint is fully public.

**Endpoint:** https://arweave.net/graphql

**Alternative high-performance endpoint:** https://arweave-search.goldsky.com/graphql

**Documentation:** https://gql-guide.vercel.app/

**References:**
- Documentation: https://gql-guide.vercel.app/
- GettingStarted: https://docs.arweave.org/developers/arweave-node-server/http-api
- GitHubOrganization: https://github.com/ArweaveTeam
- Cookbook: https://cookbook.arweave.net/
