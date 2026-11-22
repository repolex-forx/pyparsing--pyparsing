# Repolex Knowledge Graph of pyparsing/pyparsing

RDF knowledge graph data for [pyparsing/pyparsing](https://github.com/pyparsing/pyparsing), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download pyparsing/pyparsing
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 7d4bda2743ebc04f68d2594bc4fffc70cd65848f
│   │   │   └── chunk-001.nq.gz
│   │   └── 810199f89bf916590426e1c5cb3d612584f11a2f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7d4bda2743ebc04f68d2594bc4fffc70cd65848f.nq.gz
│   └── repolex
│       ├── 7d4bda2743ebc04f68d2594bc4fffc70cd65848f
│       │   └── chunk-001.nq.gz
│       └── 810199f89bf916590426e1c5cb3d612584f11a2f
│           └── chunk-001.nq.gz
└── blob
    ├── 022837af49917c56227084604499f8f8d8d5e426.nq.gz
    ├── 02727e908491c12009b1b579ae933d8282977105.nq.gz
    ├── 02ef481cf9ada4aaaa95866504e112a27ee82563.nq.gz
    ├── 03315beb8f1c4dfe1a8b915e244463052994774c.nq.gz
    ├── 046fe7926fa32888ec6f72ab9c44c7640e2b4ccd.nq.gz
    ├── 04b5432a974ec13d5a4b9e49828dabf352757a3d.nq.gz
    ├── 05ebc9eb5d5a6d5e157801f77d027c381a964123.nq.gz
    ├── 06229c7912a292db4bdb47f9a242304c2ac3e22a.nq.gz
    ├── 066d66116f2f04d57e9968c209c7293ad49d4ab8.nq.gz
    ├── 081ff8547fbeb137024c2cc3582850a465129f94.nq.gz
    ├── 0877e5436490f7172232ecc32903101fb8a3faac.nq.gz
    ├── 087aea1485d2ea75a0e4bc70967e144c7f2e2048.nq.gz
    ├── 0af6ad15da8b995423f2d60ee2383714d6d747d8.nq.gz
    ├── 0c2625cd6ac1a40301eaacc30c728e4d6fc57b81.nq.gz
    ├── 0c8fc6119f6a984da5ade7ab947f5ca3640cd920.nq.gz
    ├── 0c9166f197dbf5337a5ef84c3e2cec08e94472c3.nq.gz
    ├── 0d240a5d5b40b00bf3a417e6e92336310ead3483.nq.gz
    ├── 0e379a2b774b32702772e6abdb10ea1710a4d615.nq.gz
    ├── 0ea4aa1a3eb97cae627e2573c0d08c1b18f1a3e0.nq.gz
    ├── 0fbb091245a4d8a266a51355bf9fedd64854c27e.nq.gz
    ├── 10a0c770ba98394d7e5380862ea45f7ae90acda8.nq.gz
    ├── 118f03acd5d1e1486f519aef147d585350d23cb4.nq.gz
    ├── 123fe585f0edb463768ebd67e4cf450d5f878d25.nq.gz
    ├── 12fd8ddd0887ea16e135a335f935c98584a95da9.nq.gz
    ├── 147dcad1ecc94b4b0bef50b2c01783ddb9a66d07.nq.gz
    ├── 15cf2829272ec70e79dea1b60b530bfc132f3e6e.nq.gz
    ├── 16590a367cc35845da941af92d71ce494377194d.nq.gz
    ├── 16d4bb430eb4e846c5e5ed5f655caa429671e552.nq.gz
    ├── 179e10a35acabf5fac1c6406785a24182170aa76.nq.gz
    ├── 17a7b2ab32234d7b264fdc59702a4a091f3dc11d.nq.gz
    ├── 17d8fa022e8911a083c1a768d74980afbecabe94.nq.gz
    ├── 181740fdd0bd2267b8705f6cbc0ebe1e1978ab02.nq.gz
    ├── 18f32673ab31e21defc3680e55ff0a50d91afd8c.nq.gz
    ├── 19c436cb7a43489c693ff66680757004e274aee7.nq.gz
    ├── 1aaea56f54d7d7b28115362e294d191dd16b46d9.nq.gz
    ├── 1b01509700f884fab541f14766491e6d2f88b66f.nq.gz
    ├── 1b293fc9bc14e9fd5b1cb664766de37c242dc1ec.nq.gz
    ├── 1b6a6d6278dda4d910f2d42aed2270a93e942552.nq.gz
    ├── 1b8c058da0e69112dc44b52996a3ac9c4f1d9d45.nq.gz
    ├── 1befde714f6ab3df45819a3ea3b43a23e092994f.nq.gz
    ├── 1bf98523e33170372cf0702f03e38dadec3c5094.nq.gz
    ├── 1daf65e4161f6f346185ae7abc87690556b0bc29.nq.gz
    ├── 1e4e9425e62a62d1b70fe26d5b6fae12d3b9d5da.nq.gz
    ├── 1e8ff12683cfe4fe806e17c0536b99f0a6c36a3e.nq.gz
    ├── 1f3ae4a5cca1842ced72cca181959ec6b3945b31.nq.gz
    ├── 21e33b603ad1c8ce7d3f919c882a9e21058d0012.nq.gz
    ├── 2208f7a217c0ff1833a36b561ea6aa5a4ee38bb7.nq.gz
    ├── 23b2893d24e4bdfc2657bd93a376152b9f5393e0.nq.gz
    ├── 23c902dddcaeb78e28240baa2b87e2dca87d5685.nq.gz
    ├── 242a7de9c99ba1aebc8d2b1e72ea64207f5fb579.nq.gz
    ├── 24d603c7bc40aea07ca2916c5b153d6617b10311.nq.gz
    ├── 24f07ed930d02c701be7d29c369cbbc327eead96.nq.gz
    ├── 265590429915d76906e00d8544f305801acca7bf.nq.gz
    ├── 28055b14fbd7dfd8d4664d4234d56dae1699ae66.nq.gz
    ├── 289d9740c577ae0d2c0c6ead1c5d12ca6af7d993.nq.gz
    ├── 28cdfd61abacc5cc4d2e1cdc4fb92c9c63a21116.nq.gz
    ├── 294d658dd56b869d082af49a89297125293e85b8.nq.gz
    ├── 2b778cf8dbe6a09daf174c4621b200317fa4324d.nq.gz
    ├── 2b977ddd5112c83f8e381335d91a440bf63c733b.nq.gz
    ├── 2bdbd93ff2eeed2eeaac45b28589832a219111f1.nq.gz
    ├── 2d29200ec66275c90ee9d2fd3e7b4b9a43c0f0b2.nq.gz
    ├── 2f4fe3dea230e66d010fc33d869380a1ab666aca.nq.gz
    ├── 3068958f700610fff94bdae4a803e1d78fa0ccc3.nq.gz
    ├── 31494b8b2bb0eff003b8262c35e17d2be5a149e7.nq.gz
    ├── 32bb94e4397a2dd4b66e2a725c1e119e3518de71.nq.gz
    ├── 32e62f25e35765caba93ddad6abdccbb93d43504.nq.gz
    ├── 340aca3d0c13016d6079fac6c190e3de5518afb2.nq.gz
    ├── 341fd671a771fc8358d5f472f2e47494e4bf6db9.nq.gz
    ├── 3428ba93e0036f9a99313e670ae8eac243c5d0b3.nq.gz
    ├── 346d2693d6ba3a5aef7583bb9dbfb3048cfe9780.nq.gz
    ├── 34f0ef83beff8855f939a0b426d89f531ffe172a.nq.gz
    ├── 356fd55cb0806ce1c022bb9fa129e1fe973d2b44.nq.gz
    ├── 358dd6f2a8d8fb77daa2aaf165a4b6ad6de3a50a.nq.gz
    ├── 36e67b2d903809104dca87985da8d8e4b7bf95d2.nq.gz
    ├── 372d239f219e5f26360bc1f2854645fa89608ca6.nq.gz
    ├── 375789081ff1a3ec1161e3aa2fc290c1693957f2.nq.gz
    ├── 3818c80b5b1fbde4d70dafe974ffda1d9727bbe5.nq.gz
    ├── 38f27e3939b25fd0b1bf004faeec3ec3eacdf38b.nq.gz
    ├── 39b8b4b8eb96c537a26ef494cb9c4ee6ccea8d00.nq.gz
    ├── 39ec15f2dc200755dd97cb0351263353526f9398.nq.gz
    ├── 3a19ae0483bade709520a0c24d4259dce30c620d.nq.gz
    ├── 3aa4f2b896c0e137c1be9a9b86daa314ab16a54c.nq.gz
    ├── 3b4daa99bdee5cc219e6d643b4ffd1d883bb3e9c.nq.gz
    ├── 3bb23e371fd13739c7d758a60d8a6190f57356aa.nq.gz
    ├── 3c898e08bf944d403862759bbf14bff8597e741f.nq.gz
    ├── 3d7efe26cdd92e1f4deb02a8e225d2d8e8e827f0.nq.gz
    ├── 3dfe81e2a03163464149df227e4cbf6a0c6c417e.nq.gz
    ├── 3e06c6310ff7251059add1a7f82a1f3f714687aa.nq.gz
    ├── 3e3aafaa116974f3246b186b4755f4828df53669.nq.gz
    ├── 3e5fe2089bd29db913dc61df87c4f1775f73fe67.nq.gz
    ├── 4126bdeb81cb616d8ea4fd6338b93fa089791390.nq.gz
    ├── 41887fdbca0dc7c5976de1a2812e6f0b94c41051.nq.gz
    ├── 418ade286f013b226485835f8317b9196d2353e8.nq.gz
    ├── 426b8b238c8c2ed0dc8f279b14a2c1fad85b0e03.nq.gz
    ├── 432a8404064a7c724a3273bfcd999c0cc23e6608.nq.gz
    ├── 43f3ae3e9dcf60b89de1a3c712fbc22d829e7ed8.nq.gz
    ├── 44fcc63439371c8c829df00eec6aedbdc4d0e4cd.nq.gz
    ├── 45914c2fae3a9884a7edce08605bb90854e79dcd.nq.gz
    ├── 45d99b2942391a41a9eeeba371b25d2e32dac4c2.nq.gz
    ├── 4700d2c02c0a2d83ee20af6d2749fd7517ad1ee0.nq.gz
    ├── 47cd625fb844a19cfd38f472e6a12df1e681de62.nq.gz
    ├── 4843d40c5c1f2d7f86b39f9c4c9dbc81d3ad8473.nq.gz
    ├── 49151eee8db91b334bd0618008a6c7385bb27b40.nq.gz
    ├── 49788aad66a2ff2e10a913ccdf0d2829e93c6254.nq.gz
    ├── 49fc2383883bbb468f7641f6c049aa8876df1eed.nq.gz
    ├── 4a1012a8080f0041042a1a5d1a73478ca6cd487b.nq.gz
    ├── 4abec8a85f807b7d52d1f99f97dc7c555efa65d9.nq.gz
    ├── 4ae018a963659696c9ba08a20ca38eab80618e4c.nq.gz
    ├── 4bb3c0fa62dd375d2da146d969ebbe31d11ad425.nq.gz
    ├── 4be950d6ccc054c3c716cace42e5f2c810b7f41b.nq.gz
    ├── 4e1085e2084f30ca0edf0787e936325be8d61214.nq.gz
    ├── 4e4e2b56dba6399a45b068ba08eb12dd468cd7a2.nq.gz
    ├── 4ebe72795d118e330bb971d042e055f8919d96ea.nq.gz
    ├── 4edf8ee52fdcdd7fb75dfd5ee2737d5ed16c0185.nq.gz
    ├── 4f5feb162d1683adb92583a1edaa3d21fd99f338.nq.gz
    ├── 4f84d2ca79d45ae8bf04cc68ca70355a4cb29230.nq.gz
    ├── 503a4cdf0bd29775f01c31cd28b121e9340efa11.nq.gz
    ├── 53e1a2d469996a43f1d96a90396120c9015d11d9.nq.gz
    ├── 559c9ded6bde0e849087e9e69d3af7e522f8dbbd.nq.gz
    ├── 5600b28469a5100edf37cb17ee4e1befaa1266fc.nq.gz
    ├── 562ec48a6307b4417ccb0be0777f12631e878850.nq.gz
    ├── 5654d47d62d3928001e79b51ef935a3151a8e46d.nq.gz
    ├── 565aac30df3df391ca0f48b8522c4b2c50c00360.nq.gz
    ├── 5669c2d36e9fa4da62024616faf8754c2ca7ff0d.nq.gz
    ├── 589348290d740a24bcb5d3daa91dd4e8bb1579b3.nq.gz
    ├── 595b57d555280b0cc923cf59f8f935f3466a6cfe.nq.gz
    ├── 5bd0a0fecbac7ba064aa879b681773e2abe93140.nq.gz
    ├── 5c7e398f6c8f781dc51699332838b693951943df.nq.gz
    ├── 5d21e700b148ef3a39fdc2284da541497d741266.nq.gz
    ├── 5f5bd8a054746f8231b6903661201e4b77e8ac93.nq.gz
    ├── 5f817bc2d85b7874ad12e5e52d697f4229cf68e4.nq.gz
    ├── 5ff94b1b34436417421ce7e53a143dfa17e22d3f.nq.gz
    ├── 603920404d4fbc01e9a8593daf39e9eb2cecc529.nq.gz
    ├── 6163a45a034502d1e17108c01e4de007d913f3af.nq.gz
    ├── 6185f18b0ce37438e2b5843906c4c5454256d3bc.nq.gz
    ├── 61c22e0acafa08ba158a1214f18e1fcc87cdc979.nq.gz
    ├── 62a7a91c9fb4798126667632a48095c9205991e5.nq.gz
    ├── 62becd2516c91f5e86a56272f1371c9cb7a4bc4f.nq.gz
    ├── 63ff540e321a95ee65731132b7899e0160de09e0.nq.gz
    ├── 642c16c5f74dcc8242901bf155f73ea9a7291e9d.nq.gz
    ├── 653647939090d4b7bfb3c3f387b034393baf3a7b.nq.gz
    ├── 65d2b21dcdded1b35ee8e6d4e8368a6c94b0e960.nq.gz
    ├── 65d4013fef61ef9128e397c030d96969546625aa.nq.gz
    ├── 65f05571d9b602c515e2031e46e6ccb3ca66b3dc.nq.gz
    ├── 66aeb3e8bc40ba9f203953e55674b7e7a9f188ca.nq.gz
    ├── 6711199364b885ea4ff2f433d77841fe389e31c1.nq.gz
    ├── 68c9efcc52e837a8840a10dc1c26fdd3873f8a5b.nq.gz
    ├── 6a80811d60d8d0407d05c7cdb9e633e83695ae65.nq.gz
    ├── 6aa45d5623e4940456edd65670c904192e8fdbba.nq.gz
    ├── 6aea89ad7288f1b702dc2d91a22ca48fb2d84993.nq.gz
    ├── 6c22d841f27bdb4fd6387172be25a391c77afdf1.nq.gz
    ├── 6cbf474eaf77ea5c2a700856fa05aa8ae0e46d44.nq.gz
    ├── 6d51a78d72a60f0b0ad00a465ab4fba398301af2.nq.gz
    ├── 6d8b0c4d9d139987d1aa95260d3cb6fbe040298c.nq.gz
    ├── 6dbdb46b3a17f3649f80b126b861777fcbbfb30d.nq.gz
    ├── 6f2e6e776e311b9d816b4f80018cbf018641936f.nq.gz
    ├── 6f9f9b973817b506f63aee77fa73a8d621917258.nq.gz
    ├── 700d0b561f370eaa602d1c0e0a0ccd18d66c3a09.nq.gz
    ├── 7010181f713535725ce1e5174075de33e24d8335.nq.gz
    ├── 701ff35db736b7d99af01db72fd072bf68485468.nq.gz
    ├── 706a0d78a6dd044de37babe670e162232f6be1fa.nq.gz
    ├── 71e734b49493f376cebdfef8f89c2d567b8016ef.nq.gz
    ├── 730ad96b8c51969fb37e2a345a4a82366ae1c2a8.nq.gz
    ├── 73c81160c77cf793e55d69e4f2594f1be7f3812f.nq.gz
    ├── 73db323b1af1bfa7c2360fc858f06a461a888f5c.nq.gz
    ├── 74e843f92d5b67abcfca3d27614eea1c3aea785f.nq.gz
    ├── 74faa46085af6e10952f22c207ad3bb96bffc3af.nq.gz
    ├── 7614429528ade28ab4b58b3e2b08c923a7e8156d.nq.gz
    ├── 768ff9bd627cf029045bc87c317020a81b9ec219.nq.gz
    ├── 76bcc72235b8ec9b9730d3b51afa2e7e0c97e7f3.nq.gz
    ├── 77145f4876be51ca443c33313c2c9479b16a907b.nq.gz
    ├── 774a73d8828f622c9b8689b059fe8ad841042a44.nq.gz
    ├── 776fe953a092ca2b45e79799724d0daebc694e42.nq.gz
    ├── 781b07bb49affc0d7aa9a101fd937855a0f89bea.nq.gz
    ├── 784f8ab448c1b0fafb65a9f8c46eb5edf230f9fd.nq.gz
    ├── 7864755ee98d83047eb2dabd1dde2f38a6ff42d2.nq.gz
    ├── 79257ebab7607b0ef46b1373872f9c696051b49d.nq.gz
    ├── 799985da66596600d425e85c5bcdc51a8c6616c1.nq.gz
    ├── 79d8153ce33ae1aff300e5243554e62124fcde36.nq.gz
    ├── 7a4e954da829f35e1d428f465a386024a8ee5ee4.nq.gz
    ├── 7ab26c2bcaa4e9e432b3cb79b6baeca01642a8b7.nq.gz
    ├── 7b1ff7595e069627059551b2327ae7f34e9343b9.nq.gz
    ├── 7b54c3ea10e5e48b7477bf13d000508707738b1f.nq.gz
    ├── 7cb109c7e49a8840350328fea193c1dc94227ed6.nq.gz
    ├── 7d5921ca39b48977f07ee5c3a577ae64e34b1838.nq.gz
    ├── 7d5d954d0eab1d76828cd6c7f278eac6514996d8.nq.gz
    ├── 7e10ff448badf46f73c696d255cab4b467830500.nq.gz
    ├── 7e77a39ced9ac63387fe3ede3cb195af731687dd.nq.gz
    ├── 7f06b45f688fc47dd30a063d316397a91883a2df.nq.gz
    ├── 7f46fa94eef27614f7c4c264b29a0f444b095ea1.nq.gz
    ├── 7fb4a32b84c87b564dd1803531c9d985c7698bd3.nq.gz
    ├── 80a8c969b2b78a8c03de5cc3bf011d01ac90e37c.nq.gz
    ├── 812df477992c8396e2b64fc1214ad950b6138309.nq.gz
    ├── 81be74f894cccf93f159cf8cad1467def437668d.nq.gz
    └── 82031f3098d7b030d07a50e9ae710d296e4d82df.nq.gz

10 directories, 200 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[pyparsing/pyparsing](https://github.com/pyparsing/pyparsing)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
