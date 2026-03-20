# interplanetaryfilesystem

### IPFS Development Archive — The Permanent Web

> 75 repositories preserving the complete InterPlanetary File System development ecosystem: core implementations, desktop applications, browser extensions, NFT storage, content addressing, Filecoin integration, decentralized websites, and the infrastructure that makes data permanent, censorship-resistant, and universally addressable.

---

## Why IPFS Matters

The conventional internet is built on location addressing: data lives at a URL, on a server, owned by a company. When the server goes down, the data disappears. When the company shuts down, decades of human knowledge vanish. When a government blocks a URL, the information ceases to exist for an entire population.

IPFS replaces location addressing with **content addressing**. Data is identified by what it is (its cryptographic hash), not where it is. The same file served from any node in the network resolves to the same address. This single architectural change makes data:

- **Permanent** — content-addressed data cannot be silently altered or deleted from the network as long as any node hosts it
- **Censorship-resistant** — there is no single URL to block; the content exists wherever peers choose to host it
- **Verifiable** — the hash of the data proves its integrity; you can verify that what you received is exactly what was requested
- **Deduplicated** — identical content across the entire network resolves to a single address, reducing storage waste at planetary scale
- **Offline-capable** — content can be shared peer-to-peer without any internet connection, through local networks or even sound waves

These properties make IPFS the natural storage layer for NFTs, decentralized applications, scientific data, legal records, creative works, and any information that must survive institutional failure.

---

## The Role of IPFS in the Decentralized Movement

Every other technology in the decentralized ecosystem — blockchains, smart contracts, DAOs, tokens — deals with computation and coordination. IPFS deals with **data itself**. Without permanent, verifiable storage, the decentralized movement builds castles on sand:

- **NFTs without IPFS** point to URLs that 404 when the hosting company folds
- **Smart contracts without IPFS** reference metadata that can be silently changed
- **DAOs without IPFS** store governance documents on servers they don't control
- **Identity systems without IPFS** depend on centralized credential databases

IPFS is the layer that makes all other decentralized systems trustworthy, because it ensures the data they reference will still exist tomorrow.

---

## Collection by Domain

### IPFS Core Infrastructure (12+ repos)

The foundational tools for running, managing, and interacting with IPFS nodes.

| Repository | Description |
|------------|-------------|
| [ipfs-desktop](https://github.com/interplanetaryfilesystem/ipfs-desktop) | Desktop application for IPFS on Windows, Mac, Linux |
| [ipfs-webui](https://github.com/interplanetaryfilesystem/ipfs-webui) | Web frontend for IPFS node management |
| [ipfs-companion](https://github.com/interplanetaryfilesystem/ipfs-companion) | Browser extension for IPFS resource access |
| [js-ipfs-examples](https://github.com/interplanetaryfilesystem/js-ipfs-examples) | JavaScript IPFS implementation examples |
| [helia](https://github.com/interplanetaryfilesystem/helia) | Modern IPFS implementation in JavaScript |
| [ipfs-car](https://github.com/interplanetaryfilesystem/ipfs-car) | Convert files to content-addressable archives |
| [ipfs-cluster](https://github.com/interplanetaryfilesystem/ipfs-cluster) | Zero-dependency client for IPFS Cluster HTTP API |
| [ipfs-check](https://github.com/interplanetaryfilesystem/ipfs-check) | Check accessibility of data by IPFS peers |
| [ipfs-deploy](https://github.com/interplanetaryfilesystem/ipfs-deploy) | Zero-config CLI to deploy static websites to IPFS |
| [ipfs-linux-service](https://github.com/interplanetaryfilesystem/ipfs-linux-service) | Run IPFS daemon as a Linux system service |
| [ipfs-blog](https://github.com/interplanetaryfilesystem/ipfs-blog) | IPFS Blog and News |
| [ipfs-docs](https://github.com/interplanetaryfilesystem/ipfs-docs) | IPFS documentation platform |
| [ipfs-pubsub-compute](https://github.com/interplanetaryfilesystem/ipfs-pubsub-compute) | Run code on other machines using IPFS Pubsub as message queue |
| [npm-on-ipfs](https://github.com/interplanetaryfilesystem/npm-on-ipfs) | Install npm modules through IPFS |
| [ipfsPython](https://github.com/interplanetaryfilesystem/ipfsPython) | Upload files to IPFS in Python |

### NFT Storage (8+ repos)

The bridge between NFTs and permanent storage. These tools ensure that NFT metadata and assets survive beyond any single marketplace or hosting service.

| Repository | Description |
|------------|-------------|
| [nft.storage](https://github.com/interplanetaryfilesystem/nft.storage) | Free decentralized storage for NFTs on IPFS and Filecoin |
| [nftstorage.link](https://github.com/interplanetaryfilesystem/nftstorage.link) | Caching IPFS gateway optimized for NFT retrieval |
| [nftup](https://github.com/interplanetaryfilesystem/nftup) | No-code app to upload NFTs to IPFS via NFT.Storage |
| [nft.storage-tools](https://github.com/interplanetaryfilesystem/nft.storage-tools) | Utilities for working with nft.storage |
| [nft.storage-example-next.js](https://github.com/interplanetaryfilesystem/nft.storage-example-next.js) | Next.js interface for NFT on IPFS |
| [ipnft](https://github.com/interplanetaryfilesystem/ipnft) | InterPlanetary NFT specification |
| [ipnftx](https://github.com/interplanetaryfilesystem/ipnftx) | InterPlanetary NFT Extensions |
| [checkup](https://github.com/interplanetaryfilesystem/checkup) | Verify data availability in dotStorage |
| [react-nftstorage.link-fallback-example](https://github.com/interplanetaryfilesystem/react-nftstorage.link-fallback-example) | React fallback gateway example |

### IPLD — InterPlanetary Linked Data (3 repos)

The data model that makes IPFS traversable. IPLD defines how data structures link to each other across protocols.

| Repository | Description |
|------------|-------------|
| [ipld](https://github.com/interplanetaryfilesystem/ipld) | InterPlanetary Linked Data — traversing data across protocols |
| [js-ipld](https://github.com/interplanetaryfilesystem/js-ipld) | JavaScript implementation of IPLD |
| [go-ipld-prime](https://github.com/interplanetaryfilesystem/go-ipld-prime) | Golang IPLD Data Model interfaces with codecs and schema support |
| [ipld-explorer-components](https://github.com/interplanetaryfilesystem/ipld-explorer-components) | React components for exploring IPLD data |

### Filecoin Integration (4+ repos)

IPFS provides the addressing; Filecoin provides the incentivized, verifiable, persistent storage layer.

| Repository | Description |
|------------|-------------|
| [lotus](https://github.com/interplanetaryfilesystem/lotus) | Reference implementation of the Filecoin protocol (Go) |
| [ref-fvm](https://github.com/interplanetaryfilesystem/ref-fvm) | Reference Filecoin Virtual Machine implementation |
| [FVM-Resouces](https://github.com/interplanetaryfilesystem/FVM-Resouces) | Resources for Filecoin Virtual Machine |
| [web3.storage](https://github.com/interplanetaryfilesystem/web3.storage) | Simple file storage service for IPFS and Filecoin |

### Decentralized Web (10+ repos)

Tools for building websites, applications, and services that run on IPFS rather than traditional hosting.

| Repository | Description |
|------------|-------------|
| [decentralized-websites](https://github.com/interplanetaryfilesystem/decentralized-websites) | Resources for building decentralized websites |
| [agregore-browser](https://github.com/interplanetaryfilesystem/agregore-browser) | Minimal browser for the distributed web |
| [ipfs-website](https://github.com/interplanetaryfilesystem/ipfs-website) | Official IPFS project website |
| [sns-deploy](https://github.com/interplanetaryfilesystem/sns-deploy) | Upload to IPFS and update Solana Name Service records |
| [public-gateway-checker](https://github.com/interplanetaryfilesystem/public-gateway-checker) | Check which public IPFS gateways are online |
| [interform](https://github.com/interplanetaryfilesystem/interform) | Forms on the decentralized web (Filecoin + IPFS) |
| [polydocs](https://github.com/interplanetaryfilesystem/polydocs) | Protected documents on Polygon and IPFS |
| [ghostshare-frontend](https://github.com/interplanetaryfilesystem/ghostshare-frontend) | Private file sharing — Web3 without wallets or gas costs |
| [example-image-gallery](https://github.com/interplanetaryfilesystem/example-image-gallery) | Web3.Storage image sharing example |
| [Web3.StorageLitIntegrationExample](https://github.com/interplanetaryfilesystem/Web3.StorageLitIntegrationExample) | Lit Protocol + Web3.Storage integration |

### Libp2p Networking (2 repos)

The peer-to-peer networking layer that IPFS runs on.

| Repository | Description |
|------------|-------------|
| [go-libp2p-relay-daemon](https://github.com/interplanetaryfilesystem/go-libp2p-relay-daemon) | Standalone circuit relay daemon (v1 and v2) |
| [specs](https://github.com/interplanetaryfilesystem/specs) | Technical specifications for the libp2p networking stack |

### Identity and Naming (5+ repos)

| Repository | Description |
|------------|-------------|
| [ens.domains](https://github.com/interplanetaryfilesystem/ens.domains) | Ethereum Name Service domains |
| [react-ens-address](https://github.com/interplanetaryfilesystem/react-ens-address) | React component for ENS name resolution |
| [sign-in-with-web3](https://github.com/interplanetaryfilesystem/sign-in-with-web3) | Authentication with Web3 accounts instead of OAuth |
| [ethmail.cc](https://github.com/interplanetaryfilesystem/ethmail.cc) | Ethereum-based email |
| [DoACS](https://github.com/interplanetaryfilesystem/DoACS) | Access control service for IPNS file management |

### Ethereum and Web3 Integration (8+ repos)

| Repository | Description |
|------------|-------------|
| [web3.js](https://github.com/interplanetaryfilesystem/web3.js) | Ethereum JavaScript API |
| [graphprotocolcontracts](https://github.com/interplanetaryfilesystem/graphprotocolcontracts) | The Graph Protocol Solidity contracts |
| [merkletreejs](https://github.com/interplanetaryfilesystem/merkletreejs) | Construct Merkle Trees and verify proofs |
| [eth-ipfs-browser-client](https://github.com/interplanetaryfilesystem/eth-ipfs-browser-client) | Ethereum browser client based on IPFS/libp2p |
| [ICPwasm](https://github.com/interplanetaryfilesystem/ICPwasm) | Internet Computer example applications |
| [metadata-playground](https://github.com/interplanetaryfilesystem/metadata-playground) | Solidity metadata hash and CBOR playground |
| [sha.js](https://github.com/interplanetaryfilesystem/sha.js) | Streamable SHA hashes in pure JavaScript |
| [blueprint](https://github.com/interplanetaryfilesystem/blueprint) | Solid framework for building APIs |

### Decentralized Search and Discovery (4+ repos)

| Repository | Description |
|------------|-------------|
| [deltasearch](https://github.com/interplanetaryfilesystem/deltasearch) | Search engine for the InterPlanetary Filesystem |
| [awesome-ipfs](https://github.com/interplanetaryfilesystem/awesome-ipfs) | Curated list of IPFS resources |
| [torrent-paradise](https://github.com/interplanetaryfilesystem/torrent-paradise) | Decentralized DHT search site for IPFS |
| [indexvm](https://github.com/interplanetaryfilesystem/indexvm) | The context layer of the decentralized web |

### Community and Education (5+ repos)

| Repository | Description |
|------------|-------------|
| [community](https://github.com/interplanetaryfilesystem/community) | Community practices documentation |
| [team-mgmt](https://github.com/interplanetaryfilesystem/team-mgmt) | IPFS team planning and coordination |
| [camp](https://github.com/interplanetaryfilesystem/camp) | IPFS Camp — 3-day hacker retreat for distributed web builders |
| [IPFS-Ethereum-Hackathon](https://github.com/interplanetaryfilesystem/IPFS-Ethereum-Hackathon) | Hackathon submissions |
| [IPFS-Theory](https://github.com/interplanetaryfilesystem/IPFS-Theory) | IPFS theoretical considerations |
| [IPFS-Practical](https://github.com/interplanetaryfilesystem/IPFS-Practical) | Practical IPFS NFT reference |

### Experimental (3+ repos)

| Repository | Description |
|------------|-------------|
| [lightspeed](https://github.com/interplanetaryfilesystem/lightspeed) | DeltaVerse at the speed of light (original) |
| [wave-share](https://github.com/interplanetaryfilesystem/wave-share) | Peer-to-peer file sharing through sound waves |
| [web-llm](https://github.com/interplanetaryfilesystem/web-llm) | Large language models in the browser — no server needed |
| [deltaverse](https://github.com/interplanetaryfilesystem/deltaverse) | DeltaVerse platform delivery architecture |
| [persssist](https://github.com/interplanetaryfilesystem/persssist) | Decentralized file storage and sharing on IPFS |
| [resolution-browser-extension](https://github.com/interplanetaryfilesystem/resolution-browser-extension) | Surf the dweb with browser extension |

---

## Numbers

| Metric | Value |
|--------|-------|
| Total repositories | 75 |
| Original | 2 (lightspeed, .github) |
| Forked | 73 |
| IPFS core repos | 15 |
| NFT storage repos | 9 |
| Filecoin repos | 4 |
| Decentralized web repos | 10+ |

---

## The Architecture of Permanence

```
┌─────────────────────────────────────────────────┐
│              Content Addressing                  │
│  Every file identified by its cryptographic hash │
│  Same content → same address → anywhere          │
└──────────────────────┬──────────────────────────┘
                       │
┌──────────────────────┴──────────────────────────┐
│                IPFS Network                      │
│  Peer-to-peer distribution across all nodes      │
│  No single point of failure or censorship        │
└──────────────────────┬──────────────────────────┘
                       │
        ┌──────────────┼──────────────┐
        │              │              │
┌───────┴──────┐ ┌─────┴─────┐ ┌─────┴──────┐
│   Filecoin   │ │  NFT.Stg  │ │  Web3.Stg  │
│  Incentivized│ │  Free NFT │ │  Simple    │
│  persistent  │ │  storage  │ │  file API  │
│  storage     │ │  on IPFS  │ │  for IPFS  │
└──────────────┘ └───────────┘ └────────────┘
        │              │              │
┌───────┴──────────────┴──────────────┴──────────┐
│              Applications                       │
│  Decentralized websites · NFT metadata          │
│  DAO governance docs · Scientific data          │
│  Legal records · Creative works · Identity      │
└─────────────────────────────────────────────────┘
```

---

## Related Organizations

| Organization | Role |
|-------------|------|
| [bankonme](https://github.com/bankonme) | Sovereign banking infrastructure — uses IPFS for content addressing |
| [Professor-Codephreak](https://github.com/Professor-Codephreak) | Parent architect — bankonOS |
| [DeltaVThrust-NFT](https://github.com/DeltaVThrust-NFT) | NFT source code — relies on IPFS for metadata persistence |
| [DELTAVERSE](https://github.com/deltav-deltaverse) | Metaverse construction — IPFS for asset distribution |
| [dairef](https://github.com/dairef) | DAI stablecoin reference — preserved on content-addressed storage |

---

<div align="center">

*The conventional web forgets. IPFS remembers.*

*Content addressing means data survives institutions, servers, and censorship.*

*The InterPlanetary File System is not a feature of the decentralized web. It is the foundation.*

[github.com/interplanetaryfilesystem](https://github.com/interplanetaryfilesystem) | [awesome.ipfs.io](https://awesome.ipfs.io/)

</div>
