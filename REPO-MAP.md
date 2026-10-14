# interplanetaryfilesystem: repository map

*Generated 2026-10-13 from the GitHub API (read-only). Machine-readable copy: [`repo-map.json`](repo-map.json).*

This organization is an **archive of forks kept for study**. It did not create IPFS, IPLD, libp2p, Filecoin or any of the upstream projects listed here. The original work belongs to its creators, chiefly **[Protocol Labs](https://protocol.ai)** and the **IPFS, IPLD, libp2p and Filecoin communities** ([IPFS Project](https://ipfs.tech) · [Filecoin](https://filecoin.io) · [IPLD](https://ipld.io) · [libp2p](https://libp2p.io)), along with the independent teams named in each row (NFT.Storage, Storacha, Agregore, ENS, The Graph, MLC and others). For current code, docs and releases, always go to the upstream link.

The map reads in two directions:
- **From the archive:** each repo traced to its upstream creator, the creator's site and its current state.
- **Into the archive:** what points into these repos from our other organizations (including PARSEC wallet), and current upstream projects the archive does not yet hold.

## At a glance

| Measure | Count |
|---|---|
| Repositories | 75 |
| Forks | 73 |
| Originals (`.github`, `lightspeed`) | 2 |
| Upstream active (pushed in the last 2 years, no deprecation notice) | 28 |
| Upstream dormant (no push in 2 years, not archived) | 19 |
| Upstream archived | 14 |
| Upstream superseded, deprecated, decommissioned or marked unmaintained | 20 |
| Our fork in sync with upstream | 22 |
| Our fork behind upstream | 49 |
| Our fork diverged (has its own commits and is behind) | 3 |

Status vocabulary: **active** = not archived, no deprecation notice and pushed since 2024-10-13. **dormant** = not archived, but no push in two years. Fork state compares the upstream default branch with our default branch via `compare/{upstream}...interplanetaryfilesystem:{branch}`.

## From the archive: map by category

### Core implementations and networking

| Repo | Upstream | Creator site | Upstream status | Latest upstream release | Our fork |
|---|---|---|---|---|---|
| [go-libp2p-relay-daemon](https://github.com/interplanetaryfilesystem/go-libp2p-relay-daemon) | [libp2p/go-libp2p-relay-daemon](https://github.com/libp2p/go-libp2p-relay-daemon) | <https://libp2p.io> | archived; deprecated; successor: Circuit Relay v2 built into go-libp2p (per upstream README) | v0.5.0 (2024-09-05) | 42 behind |
| [helia](https://github.com/interplanetaryfilesystem/helia) | [ipfs/helia](https://github.com/ipfs/helia) | <https://helia.io> | active | unixfs-v8.0.9 (2026-09-29) | 335 behind |
| [ipfs-linux-service](https://github.com/interplanetaryfilesystem/ipfs-linux-service) | [dylanPowers/ipfs-linux-service](https://github.com/dylanPowers/ipfs-linux-service) (forked via DeltaLabratory/ipfs-linux-service) | <http://bits.dylankpowers.com> | dormant (no push since 2015-04-21) | no release (last push 2015-04-21) | in sync |
| [ipfs-pubsub-compute](https://github.com/interplanetaryfilesystem/ipfs-pubsub-compute) | [drbh/ipfs-pubsub-compute](https://github.com/drbh/ipfs-pubsub-compute) (forked via idmanagement/ipfs-pubsub-compute) | <https://medium.com/@david.richard.holtz/an-ipfs-application-demo-49a1255ffd0> | dormant (no push since 2019-05-26) | no release (last push 2019-05-26) | in sync |
| [ipfsPython](https://github.com/interplanetaryfilesystem/ipfsPython) | [CodeWithJoe2020/ipfsPython](https://github.com/CodeWithJoe2020/ipfsPython) | <https://www.youtube.com/channel/UCdgU4pljNproO0RQVbT5QKg> | dormant (no push since 2023-07-29) | no release (last push 2023-07-29) | 1 ahead (our own commits) |
| [js-ipfs-examples](https://github.com/interplanetaryfilesystem/js-ipfs-examples) | [ipfs-examples/js-ipfs-examples](https://github.com/ipfs-examples/js-ipfs-examples) | <https://ipfs.tech> | archived; superseded by Helia; successor: ipfs/helia + ipfs-examples/helia-examples (js-ipfs itself is deprecated in favour of Helia) | no release (last push 2023-03-06) | 7 behind |
| [specs](https://github.com/interplanetaryfilesystem/specs) | [libp2p/specs](https://github.com/libp2p/specs) | <https://libp2p.io> | active | no release (last push 2026-10-09) | 237 behind |

### Gateways, pinning and storage services

| Repo | Upstream | Creator site | Upstream status | Latest upstream release | Our fork |
|---|---|---|---|---|---|
| [checkup](https://github.com/interplanetaryfilesystem/checkup) | [nftstorage/checkup](https://github.com/nftstorage/checkup) | <https://nft.storage> | no longer maintained (upstream notice) | no release (last push 2023-02-23) | 3 behind |
| [example-image-gallery](https://github.com/interplanetaryfilesystem/example-image-gallery) | [web3-storage/example-image-gallery](https://github.com/web3-storage/example-image-gallery) | <https://web3.storage> | archived; successor: Storacha clients (storacha/upload-service) | no release (last push 2023-05-05) | in sync |
| [ipfs-check](https://github.com/interplanetaryfilesystem/ipfs-check) | [ipfs/ipfs-check](https://github.com/ipfs/ipfs-check) (forked via nftstorage/ipfs-check) | <https://check.ipfs.network/> | active (canonical upstream is ipfs/ipfs-check; our immediate parent was nftstorage/ipfs-check) | v0.11.2 (2026-08-17) | 258 behind |
| [ipfs-cluster](https://github.com/interplanetaryfilesystem/ipfs-cluster) | [nftstorage/ipfs-cluster](https://github.com/nftstorage/ipfs-cluster) | <https://nft.storage> | no longer maintained (upstream notice); successor: IPFS Cluster itself: ipfs-cluster/ipfs-cluster (ipfscluster.io) | v5.0.1 (2022-04-08) | in sync |
| [nft.storage](https://github.com/interplanetaryfilesystem/nft.storage) | [nftstorage/nft.storage](https://github.com/nftstorage/nft.storage) | <https://classic.nft.storage> | NFT.Storage Classic uploads decommissioned 2024-06-30; retrieval continues; successor: current NFT.Storage service at nft.storage | api-v4.10.0 (2024-07-02) | 176 behind |
| [nft.storage-example-next.js](https://github.com/interplanetaryfilesystem/nft.storage-example-next.js) | [nftstorage/nft.storage-example-next.js](https://github.com/nftstorage/nft.storage-example-next.js) | <https://nft.storage> | example for NFT.Storage Classic (decommissioned) | no release (last push 2024-07-03) | 1 behind |
| [nft.storage-tools](https://github.com/interplanetaryfilesystem/nft.storage-tools) | [nftstorage/nft.storage-tools](https://github.com/nftstorage/nft.storage-tools) | <https://nft.storage> | no longer maintained (upstream notice) | tag latest (no GitHub release) | in sync |
| [nftstorage.link](https://github.com/interplanetaryfilesystem/nftstorage.link) | [nftstorage/nftstorage.link](https://github.com/nftstorage/nftstorage.link) | <https://nft.storage/nft-storage-classic> | NFT.Storage Classic decommissioned 2024-06-30; gateway retrieval continues; successor: current NFT.Storage service at nft.storage | edge-gateway-v1.16.0 (2024-12-04) | 71 behind |
| [nftup](https://github.com/interplanetaryfilesystem/nftup) | [nftstorage/nftup](https://github.com/nftstorage/nftup) | <https://nft.storage/nft-storage-classic> | archived; Classic decommissioned; successor: current NFT.Storage service at nft.storage | v1.0.2 (2023-03-20) | 15 behind |
| [public-gateway-checker](https://github.com/interplanetaryfilesystem/public-gateway-checker) | [ipfs/public-gateway-checker](https://github.com/ipfs/public-gateway-checker) | <https://ipfs.github.io/public-gateway-checker/> | active | v1.23.3 (2026-08-21) | 234 behind |
| [react-nftstorage.link-fallback-example](https://github.com/interplanetaryfilesystem/react-nftstorage.link-fallback-example) | [nftstorage/react-nftstorage.link-fallback-example](https://github.com/nftstorage/react-nftstorage.link-fallback-example) | <https://nft.storage> | no longer maintained (upstream notice) | no release (last push 2022-04-27) | in sync |
| [web3.storage](https://github.com/interplanetaryfilesystem/web3.storage) | [web3-storage/web3.storage](https://github.com/web3-storage/web3.storage) | <https://web3.storage> | deprecated (old API no longer takes uploads); successor: Storacha: storacha/upload-service (w3up protocol), storacha.network | api-v7.25.1 (2025-02-14) | 418 behind |
| [Web3.StorageLitIntegrationExample](https://github.com/interplanetaryfilesystem/Web3.StorageLitIntegrationExample) | [Ghostshare/Web3.StorageLitIntegrationExample](https://github.com/Ghostshare/Web3.StorageLitIntegrationExample) | <https://www.ghostshare.xyz/> | dormant (no push since 2022-07-21) | no release (last push 2022-07-21) | in sync |

### Content addressing, IPLD and CAR

| Repo | Upstream | Creator site | Upstream status | Latest upstream release | Our fork |
|---|---|---|---|---|---|
| [go-ipld-prime](https://github.com/interplanetaryfilesystem/go-ipld-prime) | [ipld/go-ipld-prime](https://github.com/ipld/go-ipld-prime) | <https://ipld.io> | active | v0.24.0 (2026-06-02) | 183 behind |
| [ipfs-car](https://github.com/interplanetaryfilesystem/ipfs-car) | [storacha/ipfs-car](https://github.com/storacha/ipfs-car) | <https://storacha.network> | active (now hosted by Storacha, the renamed web3.storage team) | v3.1.0 (2025-10-08) | 28 behind |
| [ipld](https://github.com/interplanetaryfilesystem/ipld) | [ipld/ipld](https://github.com/ipld/ipld) | <https://ipld.io/> | active | no release (last push 2026-10-02) | 113 behind |
| [ipld-explorer-components](https://github.com/interplanetaryfilesystem/ipld-explorer-components) | [ipfs/ipld-explorer-components](https://github.com/ipfs/ipld-explorer-components) | <https://ipfs.tech> | active | v8.2.3 (2026-01-30) | 136 behind |
| [ipnft](https://github.com/interplanetaryfilesystem/ipnft) | [nftstorage/ipnft](https://github.com/nftstorage/ipnft) | <https://nft.storage> | no longer maintained (upstream notice) | no release (last push 2021-11-23) | in sync |
| [ipnftx](https://github.com/interplanetaryfilesystem/ipnftx) | [nftstorage/ipnftx](https://github.com/nftstorage/ipnftx) | <https://nft.storage> | no longer maintained (upstream notice) | no release (last push 2021-09-16) | in sync |
| [js-ipld](https://github.com/interplanetaryfilesystem/js-ipld) | [ipld/js-ipld](https://github.com/ipld/js-ipld) | <https://ipld.io> | archived; superseded; successor: multiformats/js-multiformats (per upstream README) | v0.30.2 (2021-08-11) | in sync |
| [merkletreejs](https://github.com/interplanetaryfilesystem/merkletreejs) | [merkletreejs/merkletreejs](https://github.com/merkletreejs/merkletreejs) | <https://merkletree.js.org> | active | v0.6.0 (2025-09-15) | 57 behind |
| [metadata-playground](https://github.com/interplanetaryfilesystem/metadata-playground) | [sourcifyeth/metadata-playground](https://github.com/sourcifyeth/metadata-playground) | <https://sourcify.dev> | active | no release (last push 2026-09-24) | 42 behind |
| [sha.js](https://github.com/interplanetaryfilesystem/sha.js) | [browserify/sha.js](https://github.com/browserify/sha.js) (forked via idmanagement/sha.js) | <https://browserify.org> | active | tag v2.4.12 (no GitHub release) | 22 behind |

### Filecoin

| Repo | Upstream | Creator site | Upstream status | Latest upstream release | Our fork |
|---|---|---|---|---|---|
| [FVM-Resouces](https://github.com/interplanetaryfilesystem/FVM-Resouces) | [umershaikh123/FVM-Resouces](https://github.com/umershaikh123/FVM-Resouces) | <https://muhammad-umer-portfolio-23.vercel.app/> | dormant (no push since 2023-01-19) | no release (last push 2023-01-19) | in sync |
| [lotus](https://github.com/interplanetaryfilesystem/lotus) | [filecoin-project/lotus](https://github.com/filecoin-project/lotus) | <https://lotus.filecoin.io/> | active | v1.38.1 (2026-10-13) | 4873 behind |
| [ref-fvm](https://github.com/interplanetaryfilesystem/ref-fvm) | [filecoin-project/ref-fvm](https://github.com/filecoin-project/ref-fvm) | <https://fvm.filecoin.io/> | active | fvm_shared@v4.8.4 (2026-10-08) | 394 behind |

### Browser and desktop

| Repo | Upstream | Creator site | Upstream status | Latest upstream release | Our fork |
|---|---|---|---|---|---|
| [agregore-browser](https://github.com/interplanetaryfilesystem/agregore-browser) | [AgregoreWeb/agregore-browser](https://github.com/AgregoreWeb/agregore-browser) (forked via parsec-wallet/agregore-browser) | <https://agregore.mauve.moe> | active | v2.24.0 (2026-04-23) | 227 behind |
| [eth-ipfs-browser-client](https://github.com/interplanetaryfilesystem/eth-ipfs-browser-client) | [MetaMask/eth-ipfs-browser-client](https://github.com/MetaMask/eth-ipfs-browser-client) | <https://metamask.io> | archived | no release (last push 2017-10-06) | in sync |
| [ipfs-companion](https://github.com/interplanetaryfilesystem/ipfs-companion) | [ipfs/ipfs-companion](https://github.com/ipfs/ipfs-companion) (forked via unstoppabledomains/ipfs-companion) | <https://docs.ipfs.tech/install/ipfs-companion/> | active | v3.4.0 (2026-07-21) | 245 behind |
| [ipfs-desktop](https://github.com/interplanetaryfilesystem/ipfs-desktop) | [ipfs/ipfs-desktop](https://github.com/ipfs/ipfs-desktop) | <https://docs.ipfs.tech/install/ipfs-desktop/> | active | v0.50.1 (2026-09-15) | 300 behind |
| [ipfs-webui](https://github.com/interplanetaryfilesystem/ipfs-webui) | [ipfs/ipfs-webui](https://github.com/ipfs/ipfs-webui) | <https://webui.ipfs.io> | active | v4.13.0 (2026-07-16) | 227 behind |
| [resolution-browser-extension](https://github.com/interplanetaryfilesystem/resolution-browser-extension) | [unstoppabledomains/resolution-browser-extension](https://github.com/unstoppabledomains/resolution-browser-extension) | <https://unstoppabledomains.com/extension> | active | v3.1.63.4 (2025-09-30) | 417 behind |
| [wave-share](https://github.com/interplanetaryfilesystem/wave-share) | [ggerganov/wave-share](https://github.com/ggerganov/wave-share) | <https://ggerganov.github.io/wave-share> | dormant (no push since 2020-12-11) | no release (last push 2020-12-11) | in sync |
| [web-llm](https://github.com/interplanetaryfilesystem/web-llm) | [mlc-ai/web-llm](https://github.com/mlc-ai/web-llm) (forked via webmindml/web-llm) | <https://webllm.mlc.ai> | active | v0.2.86 (2026-10-11) | 366 behind |

### Dev tooling and deploy

| Repo | Upstream | Creator site | Upstream status | Latest upstream release | Our fork |
|---|---|---|---|---|---|
| [blueprint](https://github.com/interplanetaryfilesystem/blueprint) | [onehilltech/blueprint](https://github.com/onehilltech/blueprint) | <https://onehilltech.com> | dormant (no push since 2024-07-15) | v2.7.0 (2017-03-11) | 117 behind |
| [decentralized-websites](https://github.com/interplanetaryfilesystem/decentralized-websites) | [unstoppabledomains/decentralized-websites](https://github.com/unstoppabledomains/decentralized-websites) | <https://unstoppabledomains.com> | archived | no release (last push 2026-05-27) | 2 behind |
| [ipfs-deploy](https://github.com/interplanetaryfilesystem/ipfs-deploy) | [ipfs-shipyard/ipfs-deploy](https://github.com/ipfs-shipyard/ipfs-deploy) (forked via solsolution/ipfs-deploy) | <https://ipfs.tech> | upstream labels it an "old (2022) proof of concept"; successor: none named in upstream metadata | v12.0.1 (2022-09-26) | 1 behind |
| [npm-on-ipfs](https://github.com/interplanetaryfilesystem/npm-on-ipfs) | [ipfs-shipyard/npm-on-ipfs](https://github.com/ipfs-shipyard/npm-on-ipfs) | <https://ipfs.tech> | archived | v0.16.3 (2019-06-06) | 1 behind |
| [sns-deploy](https://github.com/interplanetaryfilesystem/sns-deploy) | [Bonfida/sns-deploy](https://github.com/Bonfida/sns-deploy) (forked via augml/sns-deploy) | <https://sns.id> | dormant (no push since 2021-11-17) | no release (last push 2021-11-17) | in sync |

### Docs, community and education

| Repo | Upstream | Creator site | Upstream status | Latest upstream release | Our fork |
|---|---|---|---|---|---|
| [awesome-ipfs](https://github.com/interplanetaryfilesystem/awesome-ipfs) | [ipfs/awesome-ipfs](https://github.com/ipfs/awesome-ipfs) | <https://awesome.ipfs.tech/> | active | no release (last push 2025-11-13) | 112 behind |
| [camp](https://github.com/interplanetaryfilesystem/camp) | [ipfs/camp](https://github.com/ipfs/camp) | <https://camp.ipfs.io> | archived (IPFS Camp 2019-2022) | no release (last push 2025-05-10) | 8 behind |
| [community](https://github.com/interplanetaryfilesystem/community) | [ipfs/community](https://github.com/ipfs/community) | <https://docs.ipfs.tech/community/> | active | no release (last push 2026-08-10) | 39 behind |
| [ipfs-blog](https://github.com/interplanetaryfilesystem/ipfs-blog) | [ipfs/ipfs-blog](https://github.com/ipfs/ipfs-blog) | <https://blog.ipfs.tech> | active | no release (last push 2026-10-13) | 942 behind |
| [ipfs-docs](https://github.com/interplanetaryfilesystem/ipfs-docs) | [ipfs/ipfs-docs](https://github.com/ipfs/ipfs-docs) | <https://docs.ipfs.tech/> | active | no release (last push 2026-09-27) | 1099 behind |
| [IPFS-Ethereum-Hackathon](https://github.com/interplanetaryfilesystem/IPFS-Ethereum-Hackathon) | [MetaMask/IPFS-Ethereum-Hackathon](https://github.com/MetaMask/IPFS-Ethereum-Hackathon) | <https://metamask.io> | archived | no release (last push 2018-01-08) | in sync |
| [IPFS-Practical](https://github.com/interplanetaryfilesystem/IPFS-Practical) | [LearnWeb3DAO/IPFS-Practical](https://github.com/LearnWeb3DAO/IPFS-Practical) | <https://www.learnweb3.io/> | dormant (no push since 2023-03-07) | no release (last push 2023-03-07) | in sync |
| [IPFS-Theory](https://github.com/interplanetaryfilesystem/IPFS-Theory) | [LearnWeb3DAO/IPFS-Theory](https://github.com/LearnWeb3DAO/IPFS-Theory) | <https://www.learnweb3.io/> | dormant (no push since 2022-06-23) | no release (last push 2022-06-23) | in sync |
| [ipfs-website](https://github.com/interplanetaryfilesystem/ipfs-website) | [ipfs/ipfs-website](https://github.com/ipfs/ipfs-website) | <https://ipfs.tech/> | active | no release (last push 2026-08-25) | 217 behind |
| [Medium-Final](https://github.com/interplanetaryfilesystem/Medium-Final) | [IAmJaysWay/Medium-Final](https://github.com/IAmJaysWay/Medium-Final) | unknown | dormant (no push since 2022-06-10) | no release (last push 2022-06-10) | in sync |
| [team-mgmt](https://github.com/interplanetaryfilesystem/team-mgmt) | [ipfs/team-mgmt](https://github.com/ipfs/team-mgmt) | <https://github.com/ipfs/team-mgmt/issues> | archived; successor: docs.ipfs.tech/community | no release (last push 2023-01-28) | 8 behind |

### Identity and other

| Repo | Upstream | Creator site | Upstream status | Latest upstream release | Our fork |
|---|---|---|---|---|---|
| [.github](https://github.com/interplanetaryfilesystem/.github) | — (original) | — | original to this org | — | last push 2026-03-20 |
| [deltasearch](https://github.com/interplanetaryfilesystem/deltasearch) | [ipfs-search/ipfs-search](https://github.com/ipfs-search/ipfs-search) (forked via deltav-deltaverse/deltasearch) | <http://ipfs-search.com> | dormant (no push since 2023-10-27) | no release (last push 2023-10-27) | 79 behind |
| [deltaverse](https://github.com/interplanetaryfilesystem/deltaverse) | [Web3dGuy/tauri-workflow-template](https://github.com/Web3dGuy/tauri-workflow-template) (forked via BANKONPYTHAI/tauri-workflow-template) | unknown | active | no release (last push 2025-07-08) | 2 ahead (our own commits) |
| [DoACS](https://github.com/interplanetaryfilesystem/DoACS) | [DoNFT/DoACS](https://github.com/DoNFT/DoACS) | unknown | dormant (no push since 2023-03-28) | no release (last push 2023-03-28) | 14 behind |
| [ens.domains](https://github.com/interplanetaryfilesystem/ens.domains) | [ensdomains/ens.domains](https://github.com/ensdomains/ens.domains) (forked via PaulRBerg/ens.domains) | <https://ens.domains/> | dormant (no push since 2022-12-08) | no release (last push 2022-12-08) | diverged: 2 ahead / 106 behind |
| [ethmail.cc](https://github.com/interplanetaryfilesystem/ethmail.cc) | [CryptoverseCC/ethmail.cc](https://github.com/CryptoverseCC/ethmail.cc) | <https://ethmail.cc/> | dormant (no push since 2022-04-26) | no release (last push 2022-04-26) | in sync |
| [ghostshare-frontend](https://github.com/interplanetaryfilesystem/ghostshare-frontend) | [fs2022-project/ghostshare-frontend](https://github.com/fs2022-project/ghostshare-frontend) | <https://www.ghostshare.xyz> | dormant (no push since 2022-07-24) | no release (last push 2022-07-24) | in sync |
| [graphprotocolcontracts](https://github.com/interplanetaryfilesystem/graphprotocolcontracts) | [graphprotocol/contracts](https://github.com/graphprotocol/contracts) | <https://thegraph.com> | active | v2.1.0 (2022-11-30) | 1686 behind |
| [ICPwasm](https://github.com/interplanetaryfilesystem/ICPwasm) | [dfinity/examples](https://github.com/dfinity/examples) | <https://dfinity.org> | active | rust-basic-bitcoin-25-10-10 (2025-10-10) | 2701 behind |
| [indexvm](https://github.com/interplanetaryfilesystem/indexvm) | [ava-labs/indexvm](https://github.com/ava-labs/indexvm) (forked via TNTbkc/indexvm) | <https://www.avalabs.org> | archived | v0.0.1 (2023-02-21) | in sync |
| [interform](https://github.com/interplanetaryfilesystem/interform) | [interform-open-web/interform](https://github.com/interform-open-web/interform) | <https://interform.app/> | dormant (no push since 2022-07-26) | no release (last push 2022-07-26) | in sync |
| [lightspeed](https://github.com/interplanetaryfilesystem/lightspeed) | — (original) | — | original to this org | — | last push 2022-07-09 |
| [persssist](https://github.com/interplanetaryfilesystem/persssist) | [MCarlomagno/persssist](https://github.com/MCarlomagno/persssist) (forked via THRUSTDeltaV/persssist) | unknown | archived | no release (last push 2022-08-30) | 2 behind |
| [polydocs](https://github.com/interplanetaryfilesystem/polydocs) | [statechangelabs/polydocs-old](https://github.com/statechangelabs/polydocs-old) | <https://polydocs.xyz> | upstream renamed to statechangelabs/polydocs-old; successor: statechangelabs/Polydocs-EIP exists; relationship unknown | no release (last push 2022-09-10) | 205 behind |
| [react-ens-address](https://github.com/interplanetaryfilesystem/react-ens-address) | [ensdomains/react-ens-address](https://github.com/ensdomains/react-ens-address) (forked via PaulRBerg/react-ens-address) | <https://ens.domains/> | dormant (no push since 2022-12-10) | no release (last push 2022-12-10) | diverged: 1 ahead / 20 behind |
| [sign-in-with-web3](https://github.com/interplanetaryfilesystem/sign-in-with-web3) | [Web3Auth/sign-in-with-web3](https://github.com/Web3Auth/sign-in-with-web3) | <https://web3auth.io/docs> | active | 6.2.0 (2026-09-29) | 67 behind |
| [torrent-paradise](https://github.com/interplanetaryfilesystem/torrent-paradise) | [urbanguacamole/torrent-paradise](https://github.com/urbanguacamole/torrent-paradise) (forked via Web3dGuy/torrent-paradise) | <https://torrent-paradise.ml> | dormant (no push since 2023-12-30) | no release (last push 2023-12-30) | 16 behind |
| [web3.js](https://github.com/interplanetaryfilesystem/web3.js) | [web3/web3.js](https://github.com/web3/web3.js) | <https://web3js.org/> | archived; sunset 2025-03-04; successor: see the ChainSafe sunset/migration notice linked from the upstream README | v4.16.0 (2024-12-03) | diverged: 173 ahead / 892 behind |

### The two originals

- **`.github`**: holds the organization profile (`profile/README.md`), which presents the archive by domain.
- **`lightspeed`**: an original experiment ("DeltaVerse at the speed of light"): its README installs `rxjs` and `@parity/light.js` and links the light-client tutorial. It has been forked into PARSEC as [`parsec-wallet/lightspeed`](https://github.com/parsec-wallet/lightspeed), and PARSEC ships a Lightspeed module (see below).

Correction to the profile: `ipfsPython` is a **fork** of [CodeWithJoe2020/ipfsPython](https://github.com/CodeWithJoe2020/ipfsPython) with one extra commit of ours (a README added on top), not an original. It is a small Python example that adds a file through a local node's `/api/v0/add` and reads it back through a gateway.

## Superseded projects and their successors

| Archive repo | What happened upstream | Where to go now |
|---|---|---|
| js-ipfs-examples | `ipfs-examples/js-ipfs-examples` archived; `ipfs/js-ipfs` itself is archived and its README says it is superseded by Helia | [ipfs/helia](https://github.com/ipfs/helia) · <https://helia.io> · [ipfs-examples/helia-examples](https://github.com/ipfs-examples/helia-examples) |
| helia | Active. It is the successor to js-ipfs, and our fork is 335 commits behind | [ipfs/helia](https://github.com/ipfs/helia) · <https://helia.io> |
| js-ipld | Archived; its README says it is superseded by multiformats | [multiformats/js-multiformats](https://github.com/multiformats/js-multiformats) |
| go-libp2p-relay-daemon | Archived. The README says it is no longer maintained: Relay v1 is gone from go-libp2p ≥ 0.26 | Circuit Relay v2 inside [libp2p/go-libp2p](https://github.com/libp2p/go-libp2p) |
| web3.storage | Old web3.storage API deprecated; the team now operates as Storacha | [storacha/upload-service](https://github.com/storacha/upload-service) (w3up protocol, `@storacha/cli`) · <https://storacha.network> |
| ipfs-car | Moved from web3-storage to storacha. It is still active and released v3.1.0 on 2025-10-08 | [storacha/ipfs-car](https://github.com/storacha/ipfs-car) |
| nft.storage, nftup, nftstorage.link, nft.storage-tools, checkup, ipnft, ipnftx, ipfs-cluster (client), react-nftstorage.link-fallback-example, nft.storage-example-next.js | NFT.Storage Classic stopped taking uploads on 2024-06-30, but existing data can still be retrieved. Several of these repos carry "no longer maintained" notices | <https://nft.storage> (current service); for IPFS Cluster itself, [ipfs-cluster/ipfs-cluster](https://github.com/ipfs-cluster/ipfs-cluster) |
| ipfs-deploy | Not archived, but the upstream description now reads "Old (2022) proof of concept" | No successor is named in the upstream metadata. PARSEC deploys its own sites to Arweave with `permaweb-deploy`, not to IPFS |
| npm-on-ipfs | Archived | none named |
| web3.js | Archived; its README says it was sunset on 2025-03-04 | See the ChainSafe sunset notice linked from the upstream README |
| team-mgmt, camp | Archived | <https://docs.ipfs.tech/community/> |
| polydocs | Upstream renamed to `statechangelabs/polydocs-old` | `statechangelabs/Polydocs-EIP` exists; its relationship to polydocs is unknown |
| ipfs-companion | Active. Our immediate parent `unstoppabledomains/ipfs-companion` is archived, but the canonical upstream is still active | [ipfs/ipfs-companion](https://github.com/ipfs/ipfs-companion) |
| (not in archive) pinning-services-api-spec | `ipfs/pinning-services-api-spec` is archived and labelled "Old (2022)" | [filecoin-project/filecoin-pin](https://github.com/filecoin-project/filecoin-pin) implements the Pinning Service API; the spec page is still at <https://ipfs.github.io/pinning-services-api-spec/> |

Creator sites in current use: <https://ipfs.tech>, <https://docs.ipfs.tech>, <https://specs.ipfs.tech>, <https://blog.ipfs.tech>, <https://helia.io>, <https://ipld.io>, <https://libp2p.io>, <https://filecoin.io>, <https://lotus.filecoin.io>, <https://fvm.filecoin.io>, <https://storacha.network>, <https://nft.storage>, <https://protocol.ai>. Upstream homepage fields that still point at older `.io` domains (for example `webui.ipfs.io`, `camp.ipfs.io`) are reproduced as found.

## PARSEC: IPFS tools as modular extensions

This section is based on the public PARSEC source, [`parsec-wallet/PARSEC`](https://github.com/parsec-wallet/PARSEC), as of 2026-10-02.

**How PARSEC handles IPFS.** PARSEC does **not** embed an IPFS implementation, and it does **not** depend on any IPFS npm or Rust package. `package.json` has no helia, kubo-rpc-client, ipfs-car, w3up/storacha or nft.storage dependency, and `Cargo.toml` has no IPFS crate. IPFS reaches PARSEC through two thin, optional layers:

| PARSEC component | What it does | IPFS tool it relies on | Archive repo | Current upstream |
|---|---|---|---|---|
| `src-tauri/src/parsec_mesh/ipfs.rs` (Rust core; Tauri commands `mesh_ipfs_add`, `mesh_ipfs_get`, `mesh_ipfs_status`, `mesh_ipfs_pins`) | add, cat, pin add/rm, pin ls, id, version, repo/stat. These are plain HTTP calls to a separately installed daemon at `/api/v0` | Kubo RPC API (any Kubo-compatible daemon) | none (Kubo is not archived; see candidates). [ipfs-desktop](https://github.com/interplanetaryfilesystem/ipfs-desktop) and [ipfs-webui](https://github.com/interplanetaryfilesystem/ipfs-webui) bundle and manage Kubo | [ipfs/kubo](https://github.com/ipfs/kubo) v0.43.1 (2026-09-15) |
| `src/lib/algorand/ipfs-gateway.ts` | parses `ipfs://`, gateway URLs and raw CIDs; sequential gateway fallback (ipfs.algonode.xyz → ipfs.io → cf-ipfs.com → gateway.pinata.cloud). Used by `nft-metadata.ts` and the dashboard NFT tiles | HTTP path gateways | [public-gateway-checker](https://github.com/interplanetaryfilesystem/public-gateway-checker) (gateway health) · [ipfs-check](https://github.com/interplanetaryfilesystem/ipfs-check) (retrievability) | [ipfs/public-gateway-checker](https://github.com/ipfs/public-gateway-checker) · [ipfs/rainbow](https://github.com/ipfs/rainbow) · [ipfs/service-worker-gateway](https://github.com/ipfs/service-worker-gateway) |
| `src/lib/algorand/nft-arc19.ts` | resolves ARC-19 `template-ipfs://{ipfscid:…}` reserve-address templates to CIDv1 | CID / multihash encoding (implemented in-house) | [ipld](https://github.com/interplanetaryfilesystem/ipld) · [js-ipld](https://github.com/interplanetaryfilesystem/js-ipld) (superseded) | [multiformats/js-multiformats](https://github.com/multiformats/js-multiformats) (not used as a dependency) |
| `src/lib/mesh.ts` | TypeScript IPC wrapper for the mesh and IPFS commands | — | — | — |

**What makes the IPFS layer modular.** PARSEC's `docs/technical.md` describes the mesh, including the IPFS handoffs, as a capability *"you switch on, not things PARSEC does by default"*. The commands fail with "IPFS not configured" until the participant supplies an `IpfsConfig` (`api_url`, `gateway_url`, `auto_pin`, `max_pin_bytes`) pointing at their own daemon. Peers are found through a PostgreSQL registry, not through libp2p or the DHT.

**Not yet wired (honest status):**
- IPFS is **not** registered through PARSEC's `registerModule()` manifest (`src/lib/modules.ts`). The registered modules are `lightspeed`, `permaweb` (Arweave / ar.io) and `x402`. IPFS sits in the Rust core and the Algorand library, not in the module tier.
- `src/lib/mesh.ts` is not imported by any view, so the Kubo commands have **no UI** yet.
- `ipfs-gateway.ts` carries a TODO for a Settings hook that would let the participant restrict gateways or use their own Kubo node.
- There is no Helia (in-process IPFS), no IPNS or DNSLink resolution, no CAR packing (ipfs-car), no Storacha/w3up and no Pinning Service API client. If these were wanted, the natural upstreams would be [ipfs/helia](https://github.com/ipfs/helia) + [ipfs/helia-verified-fetch](https://github.com/ipfs/helia-verified-fetch), [storacha/ipfs-car](https://github.com/storacha/ipfs-car), [storacha/upload-service](https://github.com/storacha/upload-service) and [filecoin-project/filecoin-pin](https://github.com/filecoin-project/filecoin-pin), and the archive already holds [helia](https://github.com/interplanetaryfilesystem/helia) and [ipfs-car](https://github.com/interplanetaryfilesystem/ipfs-car) as study copies.
- PARSEC's permanent-storage path today is Arweave/ar.io (`@ar.io/sdk`, `arweave`, `permaweb-deploy`), not IPFS.

**Shared lineage.** PARSEC was started from `Web3dGuy/tauri-workflow-template`, the same upstream as this archive's [`deltaverse`](https://github.com/interplanetaryfilesystem/deltaverse) fork (forked via `BANKONPYTHAI/tauri-workflow-template`, 2 commits ahead).

## Into the archive: what points here

### Forks taken from archive repos

These forks list an `interplanetaryfilesystem/*` repo as their immediate parent, as reported by `repos/interplanetaryfilesystem/{repo}/forks`. Owners outside the five named organizations were not checked for affiliation.

| Archive repo | Forked into |
|---|---|
| go-libp2p-relay-daemon | [deltav-deltaverse/go-libp2p-relay-daemon](https://github.com/deltav-deltaverse/go-libp2p-relay-daemon) |
| specs | [THRUSTDeltaV/specs](https://github.com/THRUSTDeltaV/specs) |
| deltasearch | [ipNFTfs/deltasearch](https://github.com/ipNFTfs/deltasearch), [cleancoindev/deltasearch](https://github.com/cleancoindev/deltasearch) |
| persssist | [cleancoindev/persssist](https://github.com/cleancoindev/persssist) |
| ipfs-companion | [ipNFTfs/ipfs-companion](https://github.com/ipNFTfs/ipfs-companion) |
| lightspeed | [parsec-wallet/lightspeed](https://github.com/parsec-wallet/lightspeed) |
| web3.storage | [ipNFTfs/web3.storage](https://github.com/ipNFTfs/web3.storage) |
| example-image-gallery | [DeltaVThrust-NFT/example-image-gallery](https://github.com/DeltaVThrust-NFT/example-image-gallery) |
| polydocs | [DeltaVerseDAO/polydocs](https://github.com/DeltaVerseDAO/polydocs) |
| nft.storage-example-next.js | [ipNFTfs/nft.storage-example-next.js](https://github.com/ipNFTfs/nft.storage-example-next.js) |
| nft.storage | [ipNFTfs/nft.storage](https://github.com/ipNFTfs/nft.storage), [DeltaVThrust-NFT/nft.storage](https://github.com/DeltaVThrust-NFT/nft.storage) |
| nftup | [ipNFTfs/nftup](https://github.com/ipNFTfs/nftup) |
| nft.storage-tools | [DeltaVThrust-NFT/nft.storage-tools](https://github.com/DeltaVThrust-NFT/nft.storage-tools) |
| ipfs-check | [ipNFTfs/ipfs-check](https://github.com/ipNFTfs/ipfs-check) |
| ipnftx | [ipNFTfs/ipnftx](https://github.com/ipNFTfs/ipnftx) |
| ipnft | [ipNFTfs/ipNFTfspecs](https://github.com/ipNFTfs/ipNFTfspecs) |
| IPFS-Practical | [ipNFTfs/IPFS-Practical](https://github.com/ipNFTfs/IPFS-Practical) |
| eth-ipfs-browser-client | [ipNFTfs/eth-ipfs-browser-client](https://github.com/ipNFTfs/eth-ipfs-browser-client) |
| ipld | [ipNFTfs/ipld](https://github.com/ipNFTfs/ipld) |
| sha.js | [IPFSdapps/sha.js](https://github.com/IPFSdapps/sha.js) |
| ipfs-pubsub-compute | [ipNFTfs/ipfs-pubsub-compute](https://github.com/ipNFTfs/ipfs-pubsub-compute) |
| FVM-Resouces | [ipNFTfs/FVM-Resouces](https://github.com/ipNFTfs/FVM-Resouces) |
| sign-in-with-web3 | [solidml/sign-in-with-web3](https://github.com/solidml/sign-in-with-web3) |
| merkletreejs | [ipNFTfs/merkletreejs](https://github.com/ipNFTfs/merkletreejs), [webthreejs/merkletreejs](https://github.com/webthreejs/merkletreejs) |
| metadata-playground | [ipNFTfs/metadata-playground](https://github.com/ipNFTfs/metadata-playground), [DeltaVML/metadata-playground](https://github.com/DeltaVML/metadata-playground) |
| npm-on-ipfs | [ipNFTfs/npm-on-ipfs](https://github.com/ipNFTfs/npm-on-ipfs) |
| ipfsPython | [ipNFTfs/ipfsPython](https://github.com/ipNFTfs/ipfsPython) |
| indexvm | [IPFSdapps/indexvm](https://github.com/IPFSdapps/indexvm) |
| ipfs-linux-service | [ipNFTfs/ipfs-linux-service](https://github.com/ipNFTfs/ipfs-linux-service) |
| ipfs-deploy | [ipNFTfs/ipfs-deploy](https://github.com/ipNFTfs/ipfs-deploy), [idmanagement/ipfs-deploy](https://github.com/idmanagement/ipfs-deploy) |
| sns-deploy | [rustchain/sns-deploy](https://github.com/rustchain/sns-deploy), [idmanagement/sns-deploy](https://github.com/idmanagement/sns-deploy) |

### Our organizations' repos that share upstreams with the archive

| Repo | Immediate parent | Original upstream | Relation to the archive |
|---|---|---|---|
| [parsec-wallet/lightspeed](https://github.com/parsec-wallet/lightspeed) | interplanetaryfilesystem/lightspeed | interplanetaryfilesystem/lightspeed | forked **from the archive** |
| [parsec-wallet/agregore-browser](https://github.com/parsec-wallet/agregore-browser) | AgregoreWeb/agregore-browser | AgregoreWeb/agregore-browser | sibling fork of the same upstream |
| [THRUSTCHAIN/lotus](https://github.com/THRUSTCHAIN/lotus) | researchsolution/lotus | filecoin-project/lotus | sibling fork of the same upstream |
| [deltav-deltaverse/decentralized-websites](https://github.com/deltav-deltaverse/decentralized-websites) | unstoppabledomains/decentralized-websites | unstoppabledomains/decentralized-websites | sibling fork of the same upstream |
| [deltav-deltaverse/specs](https://github.com/deltav-deltaverse/specs) | libp2p/specs | libp2p/specs | sibling fork of the same upstream |
| [deltav-deltaverse/go-libp2p-relay-daemon](https://github.com/deltav-deltaverse/go-libp2p-relay-daemon) | interplanetaryfilesystem/go-libp2p-relay-daemon | libp2p/go-libp2p-relay-daemon | forked **from the archive** |
| [deltav-deltaverse/deltasearch](https://github.com/deltav-deltaverse/deltasearch) | deltabridge/deltasearch | ipfs-search/ipfs-search | sibling fork of the same upstream |
| [deltav-deltaverse/metadata-playground](https://github.com/deltav-deltaverse/metadata-playground) | DeltaVML/metadata-playground | sourcifyeth/metadata-playground | sibling fork of the same upstream |
| [deltav-deltaverse/web3.js](https://github.com/deltav-deltaverse/web3.js) | web3/web3.js | web3/web3.js | sibling fork of the same upstream |
| [DeltaVThrust-NFT/decentralized-websites](https://github.com/DeltaVThrust-NFT/decentralized-websites) | unstoppabledomains/decentralized-websites | unstoppabledomains/decentralized-websites | sibling fork of the same upstream |
| [DeltaVThrust-NFT/example-image-gallery](https://github.com/DeltaVThrust-NFT/example-image-gallery) | interplanetaryfilesystem/example-image-gallery | web3-storage/example-image-gallery | forked **from the archive** |
| [DeltaVThrust-NFT/nftup](https://github.com/DeltaVThrust-NFT/nftup) | nftstorage/nftup | nftstorage/nftup | sibling fork of the same upstream |
| [DeltaVThrust-NFT/nft.storage](https://github.com/DeltaVThrust-NFT/nft.storage) | interplanetaryfilesystem/nft.storage | nftstorage/nft.storage | forked **from the archive** |
| [DeltaVThrust-NFT/nft.storage-tools](https://github.com/DeltaVThrust-NFT/nft.storage-tools) | interplanetaryfilesystem/nft.storage-tools | nftstorage/nft.storage-tools | forked **from the archive** |
| [DeltaVThrust-NFT/ipnftx](https://github.com/DeltaVThrust-NFT/ipnftx) | nftstorage/ipnftx | nftstorage/ipnftx | sibling fork of the same upstream |
| [DeltaVThrust-NFT/ipfsPython](https://github.com/DeltaVThrust-NFT/ipfsPython) | AUTOMINDx/ipfsPython | CodeWithJoe2020/ipfsPython | sibling fork of the same upstream |

`thrustdrop` holds no repos tied to the archive. The `contracts` names in `parsec-wallet` and `thrustdrop` are unrelated name collisions.

### Links and dependencies

- GitHub code search for `interplanetaryfilesystem` across `parsec-wallet`, `THRUSTCHAIN`, `deltav-deltaverse`, `DeltaVThrust-NFT` and `thrustdrop` returns one hit: the `THRUSTCHAIN/.github` profile README. Code search does not index most forks, so this is a floor, not a full count.
- No package manifest in these organizations depends on an archive repo.

### Current upstream projects not yet in the archive (candidates to add)

Listed for review only. Nothing has been forked. With the `gh 2.4` installed here, `gh repo fork` has no `--fork-name`, so a name that collides with an existing archive repo will get an automatic suffix (e.g. `specs-1`). Rename it afterwards, or use a newer `gh` with `--fork-name`.

| Upstream | Why it matters | Latest release |
|---|---|---|
| [ipfs/kubo](https://github.com/ipfs/kubo) | Go reference IPFS node; PARSEC parsec_mesh talks to its /api/v0 RPC | v0.43.1 (2026-09-15) |
| [ipfs/js-kubo-rpc-client](https://github.com/ipfs/js-kubo-rpc-client) | JS client for the Kubo RPC API (successor to ipfs-http-client) | v7.1.0 (2026-06-09) |
| [ipfs/boxo](https://github.com/ipfs/boxo) | Go reference libraries for IPFS implementations | v0.43.0 (2026-09-14) |
| [ipfs/rainbow](https://github.com/ipfs/rainbow) | Production HTTP gateway daemon | v1.25.0 (2026-09-16) |
| [ipfs/someguy](https://github.com/ipfs/someguy) | Delegated Routing V1 server (providers, peers, IPNS) | v0.16.0 (2026-07-29) |
| [ipfs/service-worker-gateway](https://github.com/ipfs/service-worker-gateway) | In-browser trustless gateway (inbrowser.link) | v3.5.0 (2026-10-06) |
| [ipfs/helia-verified-fetch](https://github.com/ipfs/helia-verified-fetch) | fetch-like verified retrieval on Helia | @helia/verified-fetch-8.1.2 (2026-09-22) |
| [ipfs-examples/helia-examples](https://github.com/ipfs-examples/helia-examples) | Successor to js-ipfs-examples | none (last push 2026-07-30) |
| [ipfs/specs](https://github.com/ipfs/specs) | IPFS protocol specs (specs.ipfs.tech); name collides with our libp2p "specs" | none (last push 2026-09-26) |
| [ipfs-cluster/ipfs-cluster](https://github.com/ipfs-cluster/ipfs-cluster) | Pinset orchestration; name collides with our nftstorage "ipfs-cluster" client | v1.1.6 (2026-05-11) |
| [multiformats/js-multiformats](https://github.com/multiformats/js-multiformats) | CID/multihash/multibase; successor to js-ipld | v14.0.5 (2026-07-23) |
| [ipld/js-car](https://github.com/ipld/js-car) | CAR reader/writer for JavaScript | v5.4.7 (2026-07-30) |
| [storacha/upload-service](https://github.com/storacha/upload-service) | Storacha upload service and @storacha/cli (w3up protocol); successor to web3.storage | @storacha/cli@3.0.1 (2026-05-20) |
| [storacha/guppy](https://github.com/storacha/guppy) | Storacha client in Go | v0.7.0 (2026-04-15) |
| [libp2p/js-libp2p](https://github.com/libp2p/js-libp2p) | libp2p for JavaScript (Helia networking) | utils-v7.4.2 (2026-10-10) |
| [libp2p/go-libp2p](https://github.com/libp2p/go-libp2p) | libp2p for Go (Kubo networking; hosts Relay v2) | v0.50.0 (2026-09-21) |
| [filecoin-project/filecoin-pin](https://github.com/filecoin-project/filecoin-pin) | Pinning Service API implementation that pins to Filecoin PDP | v2.2.0 (2026-10-08) |

```sh
gh repo fork ipfs/kubo --org interplanetaryfilesystem --clone=false
gh repo fork ipfs/js-kubo-rpc-client --org interplanetaryfilesystem --clone=false
gh repo fork ipfs/boxo --org interplanetaryfilesystem --clone=false
gh repo fork ipfs/rainbow --org interplanetaryfilesystem --clone=false
gh repo fork ipfs/someguy --org interplanetaryfilesystem --clone=false
gh repo fork ipfs/service-worker-gateway --org interplanetaryfilesystem --clone=false
gh repo fork ipfs/helia-verified-fetch --org interplanetaryfilesystem --clone=false
gh repo fork ipfs-examples/helia-examples --org interplanetaryfilesystem --clone=false
gh repo fork ipfs/specs --org interplanetaryfilesystem --clone=false   # collides with existing "specs"
gh repo fork ipfs-cluster/ipfs-cluster --org interplanetaryfilesystem --clone=false   # collides with existing "ipfs-cluster"
gh repo fork multiformats/js-multiformats --org interplanetaryfilesystem --clone=false
gh repo fork ipld/js-car --org interplanetaryfilesystem --clone=false
gh repo fork storacha/upload-service --org interplanetaryfilesystem --clone=false
gh repo fork storacha/guppy --org interplanetaryfilesystem --clone=false
gh repo fork libp2p/js-libp2p --org interplanetaryfilesystem --clone=false
gh repo fork libp2p/go-libp2p --org interplanetaryfilesystem --clone=false
gh repo fork filecoin-project/filecoin-pin --org interplanetaryfilesystem --clone=false
```

`ipfs/helia` and `ipfs/ipfs-companion` are already in the archive; they need syncing, not forking. `storacha/w3up` (last push 2025-05-21) and `storacha/w3cli` (last release v7.12.0, 2025-02-25) are older than `storacha/upload-service`, which now ships `@storacha/cli`.

## Keeping the archive current

These forks are behind an **active** upstream and have no commits of their own, so each sync is a fast-forward. Archived, deprecated and dormant upstreams are left out, and so are diverged forks (`web3.js`, `ens.domains`, `react-ens-address`), which would need `--force` and would discard our commits. **Do not run these without review.**

```sh
gh repo sync interplanetaryfilesystem/agregore-browser --source AgregoreWeb/agregore-browser --branch master   # 227 behind
gh repo sync interplanetaryfilesystem/community --branch master   # 39 behind
gh repo sync interplanetaryfilesystem/go-ipld-prime --branch master   # 183 behind
gh repo sync interplanetaryfilesystem/helia --branch main   # 335 behind
gh repo sync interplanetaryfilesystem/ICPwasm --branch master   # 2701 behind
gh repo sync interplanetaryfilesystem/ipfs-blog --branch main   # 942 behind
gh repo sync interplanetaryfilesystem/ipfs-car --branch main   # 28 behind
gh repo sync interplanetaryfilesystem/ipfs-check --source ipfs/ipfs-check --branch main   # 258 behind
gh repo sync interplanetaryfilesystem/ipfs-desktop --branch main   # 300 behind
gh repo sync interplanetaryfilesystem/ipfs-docs --branch main   # 1099 behind
gh repo sync interplanetaryfilesystem/ipfs-website --branch main   # 217 behind
gh repo sync interplanetaryfilesystem/ipfs-webui --branch main   # 227 behind
gh repo sync interplanetaryfilesystem/ipld --branch master   # 113 behind
gh repo sync interplanetaryfilesystem/ipld-explorer-components --branch master   # 136 behind
gh repo sync interplanetaryfilesystem/lotus --branch master   # 4873 behind
gh repo sync interplanetaryfilesystem/merkletreejs --branch master   # 57 behind
gh repo sync interplanetaryfilesystem/metadata-playground --branch main   # 42 behind
gh repo sync interplanetaryfilesystem/ref-fvm --branch master   # 394 behind
gh repo sync interplanetaryfilesystem/resolution-browser-extension --branch master   # 417 behind
gh repo sync interplanetaryfilesystem/sha.js --source browserify/sha.js --branch master   # 22 behind
gh repo sync interplanetaryfilesystem/sign-in-with-web3 --branch master   # 67 behind
gh repo sync interplanetaryfilesystem/specs --branch master   # 237 behind
gh repo sync interplanetaryfilesystem/web-llm --source mlc-ai/web-llm --branch main   # 366 behind
```

Where `--source` is given, our immediate parent is an intermediate fork rather than the canonical upstream. Whether `gh repo sync` honours `--source` for a remote fork depends on the `gh` version. If it doesn't, use the ref fast-forward below.

The forks below have a default branch named differently from upstream's (ours vs theirs), so `gh repo sync` cannot match the branches. Each one is strictly behind, so a fast-forward of our branch to upstream's head works:

```sh
gh api -X PATCH repos/interplanetaryfilesystem/ipfs-companion/git/refs/heads/master -f sha="$(gh api repos/ipfs/ipfs-companion/commits/main --jq .sha)"   # 245 behind; upstream branch main
gh api -X PATCH repos/interplanetaryfilesystem/public-gateway-checker/git/refs/heads/master -f sha="$(gh api repos/ipfs/public-gateway-checker/commits/main --jq .sha)"   # 234 behind; upstream branch main
gh api -X PATCH repos/interplanetaryfilesystem/graphprotocolcontracts/git/refs/heads/dev -f sha="$(gh api repos/graphprotocol/contracts/commits/main --jq .sha)"   # 1686 behind; upstream branch main
gh api -X PATCH repos/interplanetaryfilesystem/awesome-ipfs/git/refs/heads/master -f sha="$(gh api repos/ipfs/awesome-ipfs/commits/main --jq .sha)"   # 112 behind; upstream branch main
```

---
*This archive is kept for study and is not affiliated with Protocol Labs, the IPFS Project, Filecoin, Storacha or NFT.Storage. All trademarks and code belong to their owners under their original licenses.*
