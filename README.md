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
│   │   └── 810199f89bf916590426e1c5cb3d612584f11a2f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 810199f89bf916590426e1c5cb3d612584f11a2f
│           └── chunk-001.nq.gz
└── blob
    ├── 022837af49917c56227084604499f8f8d8d5e426.nq.gz
    ├── 04b5432a974ec13d5a4b9e49828dabf352757a3d.nq.gz
    ├── 05ebc9eb5d5a6d5e157801f77d027c381a964123.nq.gz
    ├── 06229c7912a292db4bdb47f9a242304c2ac3e22a.nq.gz
    ├── 066d66116f2f04d57e9968c209c7293ad49d4ab8.nq.gz
    ├── 081ff8547fbeb137024c2cc3582850a465129f94.nq.gz
    ├── 087aea1485d2ea75a0e4bc70967e144c7f2e2048.nq.gz
    ├── 0af6ad15da8b995423f2d60ee2383714d6d747d8.nq.gz
    ├── 0c8fc6119f6a984da5ade7ab947f5ca3640cd920.nq.gz
    ├── 0c9166f197dbf5337a5ef84c3e2cec08e94472c3.nq.gz
    ├── 0d240a5d5b40b00bf3a417e6e92336310ead3483.nq.gz
    ├── 0e379a2b774b32702772e6abdb10ea1710a4d615.nq.gz
    ├── 0fbb091245a4d8a266a51355bf9fedd64854c27e.nq.gz
    ├── 118f03acd5d1e1486f519aef147d585350d23cb4.nq.gz
    ├── 123fe585f0edb463768ebd67e4cf450d5f878d25.nq.gz
    ├── 147dcad1ecc94b4b0bef50b2c01783ddb9a66d07.nq.gz
    ├── 15cf2829272ec70e79dea1b60b530bfc132f3e6e.nq.gz
    ├── 17a7b2ab32234d7b264fdc59702a4a091f3dc11d.nq.gz
    ├── 18f32673ab31e21defc3680e55ff0a50d91afd8c.nq.gz
    ├── 19c436cb7a43489c693ff66680757004e274aee7.nq.gz
    ├── 1b01509700f884fab541f14766491e6d2f88b66f.nq.gz
    ├── 1b293fc9bc14e9fd5b1cb664766de37c242dc1ec.nq.gz
    ├── 1b8c058da0e69112dc44b52996a3ac9c4f1d9d45.nq.gz
    ├── 1befde714f6ab3df45819a3ea3b43a23e092994f.nq.gz
    ├── 1daf65e4161f6f346185ae7abc87690556b0bc29.nq.gz
    ├── 1e4e9425e62a62d1b70fe26d5b6fae12d3b9d5da.nq.gz
    ├── 1f3ae4a5cca1842ced72cca181959ec6b3945b31.nq.gz
    ├── 23c902dddcaeb78e28240baa2b87e2dca87d5685.nq.gz
    ├── 242a7de9c99ba1aebc8d2b1e72ea64207f5fb579.nq.gz
    ├── 24f07ed930d02c701be7d29c369cbbc327eead96.nq.gz
    ├── 265590429915d76906e00d8544f305801acca7bf.nq.gz
    ├── 28055b14fbd7dfd8d4664d4234d56dae1699ae66.nq.gz
    ├── 289d9740c577ae0d2c0c6ead1c5d12ca6af7d993.nq.gz
    ├── 2b977ddd5112c83f8e381335d91a440bf63c733b.nq.gz
    ├── 3068958f700610fff94bdae4a803e1d78fa0ccc3.nq.gz
    ├── 32bb94e4397a2dd4b66e2a725c1e119e3518de71.nq.gz
    ├── 32e62f25e35765caba93ddad6abdccbb93d43504.nq.gz
    ├── 340aca3d0c13016d6079fac6c190e3de5518afb2.nq.gz
    ├── 3428ba93e0036f9a99313e670ae8eac243c5d0b3.nq.gz
    ├── 346d2693d6ba3a5aef7583bb9dbfb3048cfe9780.nq.gz
    ├── 356fd55cb0806ce1c022bb9fa129e1fe973d2b44.nq.gz
    ├── 36e67b2d903809104dca87985da8d8e4b7bf95d2.nq.gz
    ├── 372d239f219e5f26360bc1f2854645fa89608ca6.nq.gz
    ├── 375789081ff1a3ec1161e3aa2fc290c1693957f2.nq.gz
    ├── 3818c80b5b1fbde4d70dafe974ffda1d9727bbe5.nq.gz
    ├── 38f27e3939b25fd0b1bf004faeec3ec3eacdf38b.nq.gz
    ├── 3aa4f2b896c0e137c1be9a9b86daa314ab16a54c.nq.gz
    ├── 3b4daa99bdee5cc219e6d643b4ffd1d883bb3e9c.nq.gz
    ├── 3bb23e371fd13739c7d758a60d8a6190f57356aa.nq.gz
    ├── 3d7efe26cdd92e1f4deb02a8e225d2d8e8e827f0.nq.gz
    ├── 3dfe81e2a03163464149df227e4cbf6a0c6c417e.nq.gz
    ├── 3e06c6310ff7251059add1a7f82a1f3f714687aa.nq.gz
    ├── 4126bdeb81cb616d8ea4fd6338b93fa089791390.nq.gz
    ├── 432a8404064a7c724a3273bfcd999c0cc23e6608.nq.gz
    ├── 43f3ae3e9dcf60b89de1a3c712fbc22d829e7ed8.nq.gz
    ├── 44fcc63439371c8c829df00eec6aedbdc4d0e4cd.nq.gz
    ├── 45914c2fae3a9884a7edce08605bb90854e79dcd.nq.gz
    ├── 45d99b2942391a41a9eeeba371b25d2e32dac4c2.nq.gz
    ├── 4700d2c02c0a2d83ee20af6d2749fd7517ad1ee0.nq.gz
    ├── 47cd625fb844a19cfd38f472e6a12df1e681de62.nq.gz
    ├── 49fc2383883bbb468f7641f6c049aa8876df1eed.nq.gz
    ├── 4a1012a8080f0041042a1a5d1a73478ca6cd487b.nq.gz
    ├── 4abec8a85f807b7d52d1f99f97dc7c555efa65d9.nq.gz
    ├── 4bb3c0fa62dd375d2da146d969ebbe31d11ad425.nq.gz
    ├── 4e1085e2084f30ca0edf0787e936325be8d61214.nq.gz
    ├── 4e4e2b56dba6399a45b068ba08eb12dd468cd7a2.nq.gz
    ├── 4ebe72795d118e330bb971d042e055f8919d96ea.nq.gz
    ├── 4edf8ee52fdcdd7fb75dfd5ee2737d5ed16c0185.nq.gz
    ├── 4f84d2ca79d45ae8bf04cc68ca70355a4cb29230.nq.gz
    ├── 53e1a2d469996a43f1d96a90396120c9015d11d9.nq.gz
    ├── 559c9ded6bde0e849087e9e69d3af7e522f8dbbd.nq.gz
    ├── 5600b28469a5100edf37cb17ee4e1befaa1266fc.nq.gz
    ├── 565aac30df3df391ca0f48b8522c4b2c50c00360.nq.gz
    ├── 5669c2d36e9fa4da62024616faf8754c2ca7ff0d.nq.gz
    ├── 595b57d555280b0cc923cf59f8f935f3466a6cfe.nq.gz
    ├── 5bd0a0fecbac7ba064aa879b681773e2abe93140.nq.gz
    ├── 5f817bc2d85b7874ad12e5e52d697f4229cf68e4.nq.gz
    ├── 5ff94b1b34436417421ce7e53a143dfa17e22d3f.nq.gz
    ├── 603920404d4fbc01e9a8593daf39e9eb2cecc529.nq.gz
    ├── 6185f18b0ce37438e2b5843906c4c5454256d3bc.nq.gz
    ├── 61c22e0acafa08ba158a1214f18e1fcc87cdc979.nq.gz
    ├── 63ff540e321a95ee65731132b7899e0160de09e0.nq.gz
    ├── 642c16c5f74dcc8242901bf155f73ea9a7291e9d.nq.gz
    ├── 653647939090d4b7bfb3c3f387b034393baf3a7b.nq.gz
    ├── 65d4013fef61ef9128e397c030d96969546625aa.nq.gz
    ├── 66aeb3e8bc40ba9f203953e55674b7e7a9f188ca.nq.gz
    ├── 6aa45d5623e4940456edd65670c904192e8fdbba.nq.gz
    ├── 6aea89ad7288f1b702dc2d91a22ca48fb2d84993.nq.gz
    ├── 6c22d841f27bdb4fd6387172be25a391c77afdf1.nq.gz
    ├── 6cbf474eaf77ea5c2a700856fa05aa8ae0e46d44.nq.gz
    ├── 6d8b0c4d9d139987d1aa95260d3cb6fbe040298c.nq.gz
    ├── 6dbdb46b3a17f3649f80b126b861777fcbbfb30d.nq.gz
    ├── 6f9f9b973817b506f63aee77fa73a8d621917258.nq.gz
    ├── 701ff35db736b7d99af01db72fd072bf68485468.nq.gz
    ├── 71e734b49493f376cebdfef8f89c2d567b8016ef.nq.gz
    ├── 730ad96b8c51969fb37e2a345a4a82366ae1c2a8.nq.gz
    ├── 74e843f92d5b67abcfca3d27614eea1c3aea785f.nq.gz
    ├── 768ff9bd627cf029045bc87c317020a81b9ec219.nq.gz
    ├── 76bcc72235b8ec9b9730d3b51afa2e7e0c97e7f3.nq.gz
    ├── 774a73d8828f622c9b8689b059fe8ad841042a44.nq.gz
    ├── 776fe953a092ca2b45e79799724d0daebc694e42.nq.gz
    ├── 781b07bb49affc0d7aa9a101fd937855a0f89bea.nq.gz
    ├── 784f8ab448c1b0fafb65a9f8c46eb5edf230f9fd.nq.gz
    ├── 7864755ee98d83047eb2dabd1dde2f38a6ff42d2.nq.gz
    ├── 7a4e954da829f35e1d428f465a386024a8ee5ee4.nq.gz
    ├── 7ab26c2bcaa4e9e432b3cb79b6baeca01642a8b7.nq.gz
    ├── 7b54c3ea10e5e48b7477bf13d000508707738b1f.nq.gz
    ├── 7cb109c7e49a8840350328fea193c1dc94227ed6.nq.gz
    ├── 7d5921ca39b48977f07ee5c3a577ae64e34b1838.nq.gz
    ├── 7d5d954d0eab1d76828cd6c7f278eac6514996d8.nq.gz
    ├── 7e10ff448badf46f73c696d255cab4b467830500.nq.gz
    ├── 7e77a39ced9ac63387fe3ede3cb195af731687dd.nq.gz
    ├── 7f06b45f688fc47dd30a063d316397a91883a2df.nq.gz
    ├── 80a8c969b2b78a8c03de5cc3bf011d01ac90e37c.nq.gz
    ├── 812df477992c8396e2b64fc1214ad950b6138309.nq.gz
    ├── 81be74f894cccf93f159cf8cad1467def437668d.nq.gz
    ├── 82031f3098d7b030d07a50e9ae710d296e4d82df.nq.gz
    ├── 83cea039917716a846a6173bf7097520bb0fa6fd.nq.gz
    ├── 85dc41284031eb6c2c97ec0b3ce06173a516eaeb.nq.gz
    ├── 874001cb8aceea7f81cf72872c3de027cc31fb4f.nq.gz
    ├── 878b2649fd17d6d2d3424431b79568004f3fba00.nq.gz
    ├── 87df274fe62214a12a1b0d52794cefca2be3e064.nq.gz
    ├── 880d7bf592885c389a321e3c0b8fed10a43ca36a.nq.gz
    ├── 88b88bf1eb421b0b4eef52bf9c0216627048b55a.nq.gz
    ├── 8b314bc7ac2081166f4caff8bcaca0da0a453f19.nq.gz
    ├── 8c2da4d7087befabb1745d26bb3ae04a6ec9a466.nq.gz
    ├── 8c7a2bed07c5775b218daffb7fced6da404a16d4.nq.gz
    ├── 8d48d334e7f9242601ecece1018d5a5223d73a5b.nq.gz
    ├── 8d6b46f265a554185e4b3f9d556b293eca48b425.nq.gz
    ├── 8f008a21615aca422cb6d6f6db8e4ba1242663d4.nq.gz
    ├── 8f7b2178818a116af1742338dc2a12f82337adcb.nq.gz
    ├── 900911805ebd6a81bb89f971f4002b242156e256.nq.gz
    ├── 920ed651a5f115bd754fdf49188ad380f307a169.nq.gz
    ├── 92d38c75c2c8373977af1ee86e9710fae8d28628.nq.gz
    ├── 93030e44c406727c24fd7ad06bab02733db694b7.nq.gz
    ├── 9390eaf604c853e570a2e36c5a686155c3879d7d.nq.gz
    ├── 945692007f99f146627265df2596082eb553f0c6.nq.gz
    ├── 94aa52d8f42579e90ddff66d53efc1626f27ff41.nq.gz
    ├── 94df0732087314ea6389a2c9ea544feb46f32f5d.nq.gz
    ├── 9527ff49393afb7811d0cd3770f205483e57b9b9.nq.gz
    ├── 953ad4b992358ac1d7ae70d8a2c727215aeb277f.nq.gz
    ├── 9658b50896d0106e0110d54cdda08cd515f62dcd.nq.gz
    ├── 96e0ba2f582a6ac5e8c4a7fcc09f261918c75620.nq.gz
    ├── 9b4fe6e3d797c069eee4fdb4a128d97ee000e753.nq.gz
    ├── 9c31979d7f5f6a8d2a0634bb1fd4c87827c1c054.nq.gz
    ├── 9daf19daa12aaeee28abbe53d2b54542e83b224d.nq.gz
    ├── 9f2979e3a54619cb42f97061a9efdf64baefc82d.nq.gz
    ├── 9f2d01073ffdd77fb39c8485168de025abfebc2b.nq.gz
    ├── a08016cec0e75bd5f5444e71147d874500117de3.nq.gz
    ├── a113c46de0f0b66b9df1ed2bd5444e5554d24499.nq.gz
    ├── a142991c2d76b3f3489fd3ba3bcc0bbff51e31a6.nq.gz
    ├── a148d0f34dbfdee6dbd5d255ca13dd207de910b0.nq.gz
    ├── a6a7bb6b4188108d8b059a82717e6e46b2141141.nq.gz
    ├── a6daa302d7fec8aaf5d20938e57d9edc706ce88e.nq.gz
    ├── a6ddf5e313020c775544d934e8f0eddd4452597b.nq.gz
    ├── a8b5645ccbe535940220e0d95119b8edda1a3fc2.nq.gz
    ├── a91e06fbe74a68d8c4c7258f07e5ba61a956cf6d.nq.gz
    ├── aa8272a626447de0feccfc45fef7896c082d31e6.nq.gz
    ├── aaa7e1a7f50ee143fe09bef14f53322a785d29ee.nq.gz
    ├── aafb209350f5eea212c174676e1ffa49bb3ac75a.nq.gz
    ├── ac313d449968104d7b4197a8a3b9b29c5e35c934.nq.gz
    ├── ac96bdb1fbd043369203b23ba0efe8a1d8a7772f.nq.gz
    ├── aca5012d53be11c55666dc8acbcda6f25fabe134.nq.gz
    ├── acd931dd9aec2f2dc1a1f7d47c8cc1bb5a17202f.nq.gz
    ├── ae78b92439a198e7d51e15d9d438122cf989f737.nq.gz
    ├── b11214186fe5255aa9da8d12789b2ddb4284fc72.nq.gz
    ├── b126da7663b09acc3e497b9d80ceaf4c3076cf4a.nq.gz
    ├── b1a1bba1c09eb5880a3f235e17506f97c53e0a0a.nq.gz
    ├── b2808c233a0c24a6453aa7a74528df1b817ee5bf.nq.gz
    ├── b3172570ce5be7e8ec468ad4c1e493ac2df06886.nq.gz
    ├── b408bf940ecb746e96d0e6802af2c6072c6a7fc3.nq.gz
    ├── b5fe5248564b06437321394ae2aa80d4c520bfb1.nq.gz
    ├── b715dbfe3c10b82844adcfe862afcf62059165e8.nq.gz
    ├── b7dc275bf6604989dd3d20be9a00ef340a282764.nq.gz
    ├── b809d0fa49fd4d520243b1a46fcde0f7fb8aca05.nq.gz
    ├── b8ba0277694e55dcd1cbe29915980b9294af5415.nq.gz
    ├── b8baa47d14751ee7954e380ef16b97707bce9e0d.nq.gz
    ├── b8ff1aca056dda632d2c9e9c4787901ef74e06b5.nq.gz
    ├── b95ea1d80a75d080d0aa193d734d4b1cc2f8e86b.nq.gz
    ├── baf6d1213690aa5f26735afc0089128af14009bb.nq.gz
    ├── bb9c6dbee54563ec4bb6abea1a85aa7431f18c93.nq.gz
    ├── bbbfbe14cecdb0df4b716b76fe49f0a0d082ead5.nq.gz
    ├── bca82a4070eb865a172d30dfa2180b88d8b3649f.nq.gz
    ├── be0c6fe4d9e7498f522aeebe43757bc1d85ecc11.nq.gz
    ├── bf4b42023d0fd8ab620ba5d15ac820d3e6e11896.nq.gz
    ├── c22212f768eaf62791be28fca1c299847969f90e.nq.gz
    ├── c3321ce07c5c7db4c67576da9703f00641b86f20.nq.gz
    ├── c60813277cc21af96a8b47a0f24cd6bc2227dd5b.nq.gz
    ├── c74d9ff154b40ab8f74a0151a2d0a35c3c4444be.nq.gz
    ├── c7aedf9d92e5971db4cf29e162b68992241b7ccc.nq.gz
    ├── c9b9123ff53676d90b01b595a498c8cc418e48eb.nq.gz
    ├── cd9ff4ebd281853e6d3b2fd24583d9998d6c25ff.nq.gz
    ├── cea9241d5ae8db1ecf7af9530cdd1b755922e205.nq.gz
    ├── cebe77d97c9dbf5f10e1dac63706cb474934b800.nq.gz
    ├── cff0f858e14c194a458c50b381980df509db2e2f.nq.gz
    ├── d039bc23dca42fb3dbdebea8dd0b21e4ee34ca07.nq.gz
    ├── d12b5848fcf58b617bf54e95e827f43092dfb759.nq.gz
    └── d1a43875dee1b91964bbd938859f893b7a0e1c3a.nq.gz

7 directories, 200 files
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
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
