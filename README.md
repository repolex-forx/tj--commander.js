# Repolex Knowledge Graph of tj/commander.js

RDF knowledge graph data for [tj/commander.js](https://github.com/tj/commander.js), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download tj/commander.js
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8247364da749736570161e95682b07fc2d72497b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8247364da749736570161e95682b07fc2d72497b.nq.gz
│   └── repolex
│       └── 8247364da749736570161e95682b07fc2d72497b
│           └── chunk-001.nq.gz
└── blob
    ├── 00e277c4645f06d0bc598e8299062bf10a40daa8.nq.gz
    ├── 018dc1d5748201f9d95d721fe64420925010b31a.nq.gz
    ├── 02d262e6b1f17af26a8bc9e18de9d1a028232545.nq.gz
    ├── 037b699bd36027ce10966de7492c3561edea0dd4.nq.gz
    ├── 056b44ab0f06dcc95675543b4e0013ce303cffbe.nq.gz
    ├── 07e098ed7f8819ab001a24aa455842a0bc8a0594.nq.gz
    ├── 082874f3fffa22ab928fdb9c4629f238ddf1128b.nq.gz
    ├── 09888b08ae7e9a4039f7611b8475d2d97b0c073e.nq.gz
    ├── 09e13cf50ef97f543c264c9146db7dcf6000d108.nq.gz
    ├── 09e69c06a53ec4878a4499c69e86a5b480990077.nq.gz
    ├── 0a9ab0a843e8048cf8305d01b96304b25d49166f.nq.gz
    ├── 0ad046064c7f776e7777fea2e53a069c63c98fed.nq.gz
    ├── 0b6f0876ff39c945c6d658f183b0d79d3a0b3ae8.nq.gz
    ├── 0b7efb59c361671a315b6e5127fa787ac7cc1c82.nq.gz
    ├── 0c4c2e7a840904c34becc0a25f2449f765700c7a.nq.gz
    ├── 0c6374b667291653d50caa3feacff29b38dddc6e.nq.gz
    ├── 0dc96ce52f85e34337f80198c6e2af5bcdef24a0.nq.gz
    ├── 0e3a87bca54f06a71d04c4d6e36defc6cc17523c.nq.gz
    ├── 0e8e5744e6919283888381a6de3a83dd09386ed0.nq.gz
    ├── 0fe41946595ba3ee2d54426a0e230e81be536a56.nq.gz
    ├── 10f997ab104594695189c3fca8fa6c65ae9ccdd6.nq.gz
    ├── 111fac61a29d9d70f0fc295f4d65251ac9c77592.nq.gz
    ├── 112887e84d96831f5e3dac9204b749ced00254f2.nq.gz
    ├── 122cad6f7924cd597b4dba68f73bf7485cc517dd.nq.gz
    ├── 1257bc198eae8684fa62c0ef5b4f03c050a920ad.nq.gz
    ├── 138debfc4da070385a76557d3951e86147a9dcd2.nq.gz
    ├── 14824992b6f0531e4a08bf87b3fbb78a0a41001b.nq.gz
    ├── 14feea7b156e66709ec4391d028993275eeafb22.nq.gz
    ├── 167a851d96974d4dc41de00c6118badc22a6755d.nq.gz
    ├── 18887c113d61f703fc3d7f787dc8f8f4417979f4.nq.gz
    ├── 18bb3e75edc6ed89fff0d29834a917bbb7f778d3.nq.gz
    ├── 1d495c1cd5723d210f6d004c4fb8fa8ff019966c.nq.gz
    ├── 1e149e580a2f0646825028d3e7a973e96137e260.nq.gz
    ├── 1ea3fce21a1dfcfbace4b84cc413bb733316c381.nq.gz
    ├── 1ee2c3107a25e7c9214a0be0d5fa0221568ccfa3.nq.gz
    ├── 206a23cddc8a0ed473a8f3fe90ab154f53c1b8c7.nq.gz
    ├── 23431a28bca55c4c47d5209776c2f1df624178d8.nq.gz
    ├── 262cc527ed3b5c5520c0e93bcd155bbdcb6eaf05.nq.gz
    ├── 26da3cb985f8c3ed5261fd5655b08737d73db1eb.nq.gz
    ├── 280d99cf55d20f40f4c71ac88c95baccda00f73b.nq.gz
    ├── 281d6f446ba830a7c031fc21ac407a90d101e1c2.nq.gz
    ├── 2c2f840e384721b3e5da6e60370514a0e4417127.nq.gz
    ├── 2c977311b8c92a16ec8cede6a45070712d24b10b.nq.gz
    ├── 2e85f9ac33f48464d798f331c7e1f60b63b6b79d.nq.gz
    ├── 2efa4978493b295e8e3ebd866557e7fd4a531bfb.nq.gz
    ├── 2ff307953a5a339e9e21473ff9d6111aa31a3650.nq.gz
    ├── 300c8ebaa208885ebd4f80afedcf22fb9f979d04.nq.gz
    ├── 30d9222c9dffff17458d89b30e61a5efd84af43a.nq.gz
    ├── 30ee163b82b023c3900455da514fc74642c8e2d6.nq.gz
    ├── 318ca2991e7766ced4066f890159f03a249d9c26.nq.gz
    ├── 325c3430232780c3cb532c032aa9125af6916d3c.nq.gz
    ├── 376458c963586b10cfebb3383c3eb527cd8869eb.nq.gz
    ├── 39b9d86b09c6e1c0eafaaf6dd5e1c2048c05fe97.nq.gz
    ├── 3da7a870f3e1701b95dc2a47e0e92d1ca2adef89.nq.gz
    ├── 40b0230ed85f7ec5741409cb210470e4c9e5bf49.nq.gz
    ├── 40c47c54dad2b9921d1e33bf91522d51a3ebbd86.nq.gz
    ├── 420d4b4826a0c2ffe8294eb78df8207883b4927c.nq.gz
    ├── 42d4460e9a39a1ff131c57b9fb5ed6b2432fcc68.nq.gz
    ├── 4414bdeefa1a9e80350569e7d2d235ced4ae1c1f.nq.gz
    ├── 47955159c9c300a8998d0b1a18d84ab838ad3123.nq.gz
    ├── 47c9b3a05de9fd5dc8d20c0d2b60e409df8c5032.nq.gz
    ├── 4911c77448efba31ed45060d60954e67d8c212f4.nq.gz
    ├── 4930ecccc59b3f9b2bacb63b0317d5648efde920.nq.gz
    ├── 49d88f80e04a5a9ffe7dbdc198d0717f9d35f0cd.nq.gz
    ├── 4a0bd7fac72a8fcfcec620efd78c517dcc7045b8.nq.gz
    ├── 4a20b5a66a513dbc7b9236759982b9ca63c721cf.nq.gz
    ├── 4b40fb7be7ef01fdc984dc283f706bb1362e2284.nq.gz
    ├── 4b91736cf373de693ba2d84e118beeed532de2d1.nq.gz
    ├── 4c80d58ef2a18efff3bd76c4e19a67563c7ff58b.nq.gz
    ├── 4c80e4e1927a46cc1d14bba34520c1a5f4b0d26b.nq.gz
    ├── 4ee9786c6db3feb67cc060e8562f7a310d322e85.nq.gz
    ├── 4ffc49324f68e98de6047341e0af40bbed132f7d.nq.gz
    ├── 51e1d652770679f07de5794b68e036e84fdb226d.nq.gz
    ├── 51f87fe99fc2f96a66f2728da173265ba6b333d6.nq.gz
    ├── 5284a6390c4ff11d219907e4241f41c7f523a3a1.nq.gz
    ├── 53a45698ac1ea7d235684f007be0f5a8264b5c0f.nq.gz
    ├── 541c62e7a5864a3964fb91f0dc421344a51f02fb.nq.gz
    ├── 550d944c1a9fb0bfd564d6a210ecdacaa361c542.nq.gz
    ├── 553ff2e4005f03f4db95b838d0f1bebd2ff39d2b.nq.gz
    ├── 58346dcf21a276e63e16e5a3a459a996bf61b359.nq.gz
    ├── 599efdfc49e5a909aaa3d3a20ca0685db33f34f2.nq.gz
    ├── 5bbd9c3fd74aeb88fdecf86b0c10aee9403068c7.nq.gz
    ├── 5bc2ad719ad09df43ce0010d49432e622c52059c.nq.gz
    ├── 5c225c32f47dee33207bc59830d3341a53ee9ae0.nq.gz
    ├── 5cc53c66f144625efde33a4305563fee05747c34.nq.gz
    ├── 5d887b26692b9363e99a38e2fee15d713e2003cb.nq.gz
    ├── 6047306df01b3ab7878a6e6172d3ee3847127d36.nq.gz
    ├── 620528e652d7f83c07055d06ddf97680cbd3503a.nq.gz
    ├── 62363690fcc2b0ac50404711382a9aa5a1d6d632.nq.gz
    ├── 637f3f2f13953f8d68fa12c17186e3f3005b16de.nq.gz
    ├── 6427ca06037fcdb0ad4fd1e6f5809ff62a504c67.nq.gz
    ├── 64e5284c7265dd9f3efb11f84fe2a387cf9927ee.nq.gz
    ├── 64ffbd5da4d0fc21a0f915ea8499ee1355972c41.nq.gz
    ├── 677454266418422072ea7e21320f5fe3c224cbd1.nq.gz
    ├── 67af8c44e344758c8dd72233490031ea75856f7b.nq.gz
    ├── 70066ae49683581c9c081f8de86fcd63f9dd866a.nq.gz
    ├── 70d49ac7ac88545a04d5daddaf794760dad1aa8b.nq.gz
    ├── 71159eb8dc0687b10d4fe8eaf17a0d2854c2c126.nq.gz
    ├── 71ebf9978a7cf6aa3ecb21b4566b3bca767f13c2.nq.gz
    ├── 7386e5642c18719719798be52d9c8038ba504659.nq.gz
    ├── 73fbafe751ace7b505efd2937fa29b5a28d2171b.nq.gz
    ├── 74444b79d1ec1ee0219f8adf44168dd9863c25e8.nq.gz
    ├── 74e6b4c2bfe2403afc0a3726ea37045db04cc082.nq.gz
    ├── 7649d97775f9bdfede6c222b928e3dcfcc4091fb.nq.gz
    ├── 78a5a22d26914410af6b85d2b6376a8ab4491c0f.nq.gz
    ├── 796ec3a5834ff4f3e2e9b0a8d5e335a6e9957dce.nq.gz
    ├── 7998d5b158986b5d749d57f4e0a82eeac78e7718.nq.gz
    ├── 7b5b0d3992ea3c065aea60b6021e5c59e5d4a5d6.nq.gz
    ├── 7e06efbb924c7e51f7a44116f158c37ddc1cd1bd.nq.gz
    ├── 809e33f6a4d803c8ca916d6d04bb53a3152fa553.nq.gz
    ├── 837245f7ba3a999f5dc5465276dab640b1992429.nq.gz
    ├── 841e9cce7239ac8f161e758b74526d99b90d00c3.nq.gz
    ├── 8577cef10758a684037e18d231eb0a3aeec393dc.nq.gz
    ├── 85ab43b97e2789e11151a1ffcc6638176825075b.nq.gz
    ├── 86463f5c2911a9684789b5d1d68465d24bb4c11c.nq.gz
    ├── 87272846a7806d18bb03e6e9ec0e9589b52bcd65.nq.gz
    ├── 873b9d935a7389b77348a2178ad328a0b514f9ab.nq.gz
    ├── 876f7d3aa2413f31b1ef08466e4a85dfc6ab5963.nq.gz
    ├── 893a8cd31b3dc69ba82eef0486af25cd7be8d8b9.nq.gz
    ├── 8967342cb39f0bdac7f989713117f02ff8b99c50.nq.gz
    ├── 8c6e41c077b99ef59673724c143dc2afcb62a2f6.nq.gz
    ├── 8e6f6eea9d3a634905e66368be0ae702fc5904f0.nq.gz
    ├── 8e86d69a4dcdf5c4adb02af4e53710b58ee2e959.nq.gz
    ├── 8f7d6654a527291e6d474ebcdc79cefcb2db818c.nq.gz
    ├── 9248134d8f70271e405ae2933d708368902904c5.nq.gz
    ├── 9440f9692b668abbe9c1b2cefcfabc075a299879.nq.gz
    ├── 94bc3e2158dab70990104f37f30505bc05a20029.nq.gz
    ├── 94d1ead95f3a05cd70b782ca82cc0a758c7f5cea.nq.gz
    ├── 96029773f144b780872080c748a3d25c0564b204.nq.gz
    ├── 96a1302ffb9e465117f025d35a6cc50ef550092a.nq.gz
    ├── 994f8fdc0d4eaf5f2d0a2d2897905c7eb53d2c04.nq.gz
    ├── 998d852611c6489eab46bcc19e0a142d3ec52727.nq.gz
    ├── 9ae867bcefa6764c6604c272b695b3cb61532f02.nq.gz
    ├── 9cfa860eca3691ffc5cf13955900384b6b3dd260.nq.gz
    ├── 9cff7ecd685ab064a1be32df8e573279185be9f5.nq.gz
    ├── 9dc39d39af06458b6c0ba8e1212a4052ed465351.nq.gz
    ├── 9e746422a2f0085b0ae388266a81c085beebec38.nq.gz
    ├── 9e8f71e18024f3340aeedccbea20e3ebbeb4912e.nq.gz
    ├── 9ef79355ce1589ded5b274b0d07941e781ebba5e.nq.gz
    ├── 9efd708d2e8efa5b3829a0fb0d1ccf865b3ca389.nq.gz
    ├── 9fa68ed0640641e29fec5821de532f80a925e3fd.nq.gz
    ├── a11c8b72d44ee6c162c01b77738988aca3fa1af1.nq.gz
    ├── a20274b22c564bf58e5d332b92578f9a7b027a32.nq.gz
    ├── a3094140c7cead8f35b4a2ca63e22c9be9482072.nq.gz
    ├── a3f43d234623c3ce5c4e12307538b0a7f28fddb5.nq.gz
    ├── a4a91dd587e6e055dca54817fefcc4c18000cfa0.nq.gz
    ├── a50da26081788726cac0f9bb24e91cce2660d1cb.nq.gz
    ├── a5cb39bd5486c90f98f9656156cfa47f6d6d9663.nq.gz
    ├── a74c9be0e7db9445ae5f44afbd6b37e636bb614f.nq.gz
    ├── aa18660c5249906c6fe7104d95b0b21fc800359c.nq.gz
    ├── aca98fdaab4b0e4b69679b6e7832c4595000dd07.nq.gz
    ├── af6d7d8e973e603e693323514afd71bc1fae2887.nq.gz
    ├── af7930250f8b3fdb2504d0de0a41f2559a59f58a.nq.gz
    ├── b0fe7dcf96e7dd27bb58919f3513719a64625b9c.nq.gz
    ├── b276cb1c5143c9f87e239e2aa1848c870c0e8c73.nq.gz
    ├── b28c8fcc3e0a9c66f5b56ab1610bc8555adb5c90.nq.gz
    ├── b383d609cd4aeb9d2eb5c6002e6bdf6ac10638e3.nq.gz
    ├── b50f9e25ecaf3cb41b2ad299b2e6d01ccb30111e.nq.gz
    ├── b5cba294f58f075632c20a6f4bf1509fd9565430.nq.gz
    ├── bf813ea4ad84637cbcad1cf9ea3534ee95e88e50.nq.gz
    ├── c08827cf7a2a8e239261b50901d7c299c29d94f9.nq.gz
    ├── c0ca815dba0cc855cd8f3fbdfaa19b95902d1e6e.nq.gz
    ├── c2986219ebb8823132eee4feb96ea5556041d3a6.nq.gz
    ├── c2cddf17bce27397beece6165fe25b17d89144a3.nq.gz
    ├── c30bb21a63d8cb5de1f12c93eeaa3e6dd2aba2de.nq.gz
    ├── c3640879c09717ef9db6dd1d7f3c9e0a7d3f1dac.nq.gz
    ├── c42f85365d2dd36355b8cfc72fe38f21c0ea9d83.nq.gz
    ├── c61cdb1179c1c02a2ff07c2e2dd843eb961e9fb9.nq.gz
    ├── c641895fc9bd82c39ef0282623f5b597a8d43bf9.nq.gz
    ├── c6641178cf3549617a427fca50b3cebf40998ee8.nq.gz
    ├── c752dc673e6210f45bb033dd7f563090f7cf2d86.nq.gz
    ├── c9c83e6c14ac38dc868822e48f5978b7e8001976.nq.gz
    ├── cc8f0fe72f95eca3c11075510ffba910f4053585.nq.gz
    ├── ccabc7b87f3de0655928233da34353cb562187b0.nq.gz
    ├── cd5abf075b7897638a0b2a2610de3789237baa34.nq.gz
    ├── ce5120f7fa5328fb016f139b8b3329632685a35c.nq.gz
    ├── ce5d7f70634ae657d78eae3f5022de33f9549a22.nq.gz
    ├── cf17162075241f1e8b5978873ed1dbc2c455dc11.nq.gz
    ├── d05bb2a822c78570b7a47fb39fb64d78abdd46ac.nq.gz
    ├── d17aeb3672c048a30eeb62c170f6328b6fcffd60.nq.gz
    ├── d2415d9e6e959dbce5cfa20251d3ceb446a680b8.nq.gz
    ├── d2e09449e4f88973101cc6f51b8c9396ef97cca0.nq.gz
    ├── d33662267099b729eaaf6f60050568782557f630.nq.gz
    ├── d3d53e4a1d48118c6ecedb62d27d08ed88c2991c.nq.gz
    ├── d518b28cd8810359119191018bc12bd1a3332e68.nq.gz
    ├── d577e3dad69462750073e68d217a8f3bdfffac1d.nq.gz
    ├── d6ac722ee69a9d079365142e7967102de42fb8a7.nq.gz
    ├── d7569ef30f827a85b4e62472897dfa4cf3b385ac.nq.gz
    ├── d9a21e662f59539e9d9fe91323c82a5cafefa1f4.nq.gz
    ├── da70e7bd8b5b38a932b3006cb053f851660e71ae.nq.gz
    ├── dafe7df2460064bddb07d24702dba209bca25841.nq.gz
    ├── dc14394be6f2ac7b96a220dfb88961de65c59837.nq.gz
    ├── dcd41559830eff9b9ad9a2cf0c8ace34b9b2bec5.nq.gz
    ├── e0f3a1d7ec236490dc07524107b8d5cb8db27f95.nq.gz
    ├── e25c5c09b720e449a9098492aeb509c7ce430e61.nq.gz
    ├── e3adb03335cfd20bacab39a03f5f99aa63c5d816.nq.gz
    └── e3b704017cf4645eb42e974d809e1f9b16f8252e.nq.gz

8 directories, 200 files
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

## Source repository

[tj/commander.js](https://github.com/tj/commander.js)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
