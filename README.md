# Repolex Knowledge Graph of aio-libs/yarl

RDF knowledge graph data for [aio-libs/yarl](https://github.com/aio-libs/yarl), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/yarl
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d0d6a37515189b284583e5b25ae83975eff222b3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d0d6a37515189b284583e5b25ae83975eff222b3
│           └── chunk-001.nq.gz
├── blob
│   ├── 020e95e621f82563d0da17fa43801e0eccb4e550.nq.gz
│   ├── 03adac4dc15025385a7369c2783573dd59390a53.nq.gz
│   ├── 04347a11aa00e6ced2dc5322e2a095d0c4f1af3b.nq.gz
│   ├── 04e8b0c9d34790b970038ce427c3b730a335e0ad.nq.gz
│   ├── 04fd66326854723b1ea539bba1db509766eac7b5.nq.gz
│   ├── 059b5905e23a16605afc00b92c8858f345c0c04e.nq.gz
│   ├── 08dd848e1280598911e08a244141b6a397000354.nq.gz
│   ├── 093f4020f4a49faf656f01a223a6232695f8923d.nq.gz
│   ├── 0bb24d3b04b0bb276584f591f8dc92df298b9f2b.nq.gz
│   ├── 0c249fed59d5bc12062d6502beed78a54247a4c5.nq.gz
│   ├── 0d2469f2e3b73f1c05a270fe9fda3cd93927bf21.nq.gz
│   ├── 0ecb8a50f6347493d741ed84a68233d11b09fb22.nq.gz
│   ├── 11c9b130811ac42f3f862358c7e68f5cc1c9a3a1.nq.gz
│   ├── 13a78764b7e8c075f255a268910152d0a4333990.nq.gz
│   ├── 14a48d0ad13fec1b461eb1a1c23c48e4fd6ced9b.nq.gz
│   ├── 16294dd3413abe031ae25ced3776f8216ea818f3.nq.gz
│   ├── 18163dcebb09a74914dc5cdd9f2f6e5676d3ebcb.nq.gz
│   ├── 1a9f547dbb00f029cf3ecb1363fee430677e5170.nq.gz
│   ├── 1ac9bdff44c49906d508d785faeacd57deb2fcfd.nq.gz
│   ├── 1e2c78c9b77058a83aa77fea158eec2bce638d67.nq.gz
│   ├── 200425607c17ab964a92f329b8131ff1744e33d9.nq.gz
│   ├── 2063fab63c74cb69e6caa97ef160deab3cc4c240.nq.gz
│   ├── 22900fb0ecce0e3548d9964199e6604fa22af0a0.nq.gz
│   ├── 23705400953a7a671c2c42dd1439aee2f62c689d.nq.gz
│   ├── 24a415234c15745d7f48fc8ad6f95fd3ed113567.nq.gz
│   ├── 24c49e9404379d893a665eb874914784a792ff46.nq.gz
│   ├── 25d76c885cacaa815bb7e0149aedbe76c20f2228.nq.gz
│   ├── 2618faf7700507a9f88e1df26069df5ca8d27f71.nq.gz
│   ├── 273bdd5c4c36cd20d02748371947d6be0bf0a030.nq.gz
│   ├── 283613350c459df9621615fdedaa68de7d2fa8f8.nq.gz
│   ├── 2879ab2fdd3580dd4a1f12acccefd0b9bdc09cc9.nq.gz
│   ├── 2890e7765c6913543d311314ce9b9660410106f5.nq.gz
│   ├── 29b4c169b637819e3c9cf229b948fc1b646c3eb8.nq.gz
│   ├── 2bd430d702b9986d793ccaf57c9ba164d663852e.nq.gz
│   ├── 2d40560478a50d1bd1c538c4b3a29e19ee157c3d.nq.gz
│   ├── 2d650bac77e41bee5caaa6bc376b4d168ab82982.nq.gz
│   ├── 2e59e40226b6b52827becc3195436f6352e94bc5.nq.gz
│   ├── 2e8d00c81f3e3992a77749de343fea07dc426824.nq.gz
│   ├── 2eccdfe317eba1456527e28d59626c4fd92caf6a.nq.gz
│   ├── 2facd947375f711b4c2c36c5015892df4dec62b1.nq.gz
│   ├── 3030c73a042ffa52014b189515b9e63d5da343ac.nq.gz
│   ├── 33286e0ba750ae00dd0cbf1e20a3c62f43b8fe40.nq.gz
│   ├── 39029e482bade47b6e32397b3535130a138c4478.nq.gz
│   ├── 39c46d03ac2988226f949ee7ab3c7347d5481bd8.nq.gz
│   ├── 3b06d42ac95a870f206136482e2431508870d84f.nq.gz
│   ├── 3b236ceb61aa3b502b3bcc7cb6ed4f4b01e97669.nq.gz
│   ├── 3cdd0bc8fa8c0332085075e14a282c03fa743909.nq.gz
│   ├── 3d649d460f8b02c54ac165f5138c49192d179c42.nq.gz
│   ├── 3f5ca22e832ef58fbe5529c296c7083c5e3a589a.nq.gz
│   ├── 40cf678e9efb05d100abdf35e24570316fe7003c.nq.gz
│   ├── 414abc75308c248ab0191229744284b5d0c5caae.nq.gz
│   ├── 436d3760611a08c3a4fa6cee635739321fb561e1.nq.gz
│   ├── 442eb9c03f5c91dbbacb4e45c069c66fac98ece2.nq.gz
│   ├── 4465ae7b22d6a06432675dd06a5ebb7c0f991d32.nq.gz
│   ├── 46d9156e93c4961672f606d7549fc9c7519e0832.nq.gz
│   ├── 471d9cfb0097eb83db0e1d700abc51abdaaf6822.nq.gz
│   ├── 48075a847360477c2bab6c9f21969444a748fe83.nq.gz
│   ├── 4a0871a624f727bd34fe9291465e54b117758243.nq.gz
│   ├── 4a28240a90fd67214e00d49bf8c4b3d0acae70eb.nq.gz
│   ├── 4b70d9b0ce20357e25f24911efa062eace881710.nq.gz
│   ├── 4e034ea77c32c05f06381e58022ef1b157e04551.nq.gz
│   ├── 4e26fabbe5f8536a23cffa36639d738cdeaeb9a1.nq.gz
│   ├── 517ecd235823cfe9e5b0dc606460612b62498b57.nq.gz
│   ├── 51fee7fa7544c2f9a117ab55c85f8846300bdbd4.nq.gz
│   ├── 52681d1de87ca2248865c1c68cc8ea31b6a01c44.nq.gz
│   ├── 526c0543658e03b25415fab64ab3acd399f85d21.nq.gz
│   ├── 546676a2cd71609b9ed6df7ac16830622436069d.nq.gz
│   ├── 5548f56712d350f46bfe17a65d6d4e206b5aa512.nq.gz
│   ├── 5741f5934e9f464ad235e72c3dc8c0c798116b2f.nq.gz
│   ├── 58672612437144610ca6d60f780b74955947d766.nq.gz
│   ├── 586ad551c6c931bf3d06c0b5d35b5d220b494ee2.nq.gz
│   ├── 59af15b95e342c2c9c2923986f1f796a81185b96.nq.gz
│   ├── 5a4c48c0e6400f68b6b087165ebb58d7dd4b4c01.nq.gz
│   ├── 5b6242e8ba86696a13d88e3b514c2326f5249f1b.nq.gz
│   ├── 5d4247256f8261636dd6ce86cb952bf8a40ab3d7.nq.gz
│   ├── 5d5e8b68ec64334dbd49ae6515f51d90b5c2092d.nq.gz
│   ├── 5de9c032cbdffe7c30b918d661c514eca22a6c0f.nq.gz
│   ├── 5e3306bf8112d9f5f13ef9ea3e9790c6476f28eb.nq.gz
│   ├── 5ec91e02056c043e2588c54ed1267a1ecbcf1e02.nq.gz
│   ├── 60b413976ce40aa0f9b2fac5e98fe740ad7c9690.nq.gz
│   ├── 60b6c8629c72e8a750497728d6b2a7109bf8b395.nq.gz
│   ├── 6364083280fd332bcdea707999ec4da508f64254.nq.gz
│   ├── 6387656c74d3cbdc6e6544a7813963c98a90e12e.nq.gz
│   ├── 65ed60be419ff49c845c216a2b58692a38b343fa.nq.gz
│   ├── 66abb4717f2780951683eac0f0a3b915170bc0b0.nq.gz
│   ├── 6f35a49e555e3ca818f19e9f29d867ec45a30ca7.nq.gz
│   ├── 70438e4c943ce5cc1f084caf662cce38813ed07c.nq.gz
│   ├── 70be76832131d49a9b7bf882d00cefd8cad8d8df.nq.gz
│   ├── 71380eb2aec3980361a7e17723a4a8bfffc9eb46.nq.gz
│   ├── 7170fd598b54ab66786a2838e2ae702a64852b6a.nq.gz
│   ├── 723629ec6be48e6c7bbc0d78b3eed5cf99a3cb4d.nq.gz
│   ├── 74149750d00a2ba7e9abbc63f91f448c734abfc8.nq.gz
│   ├── 74ae436973392f8859ac010016afd2474a0540a6.nq.gz
│   ├── 77c85d33ffb370cdd39fd0c5dcd5a58cb5f17bab.nq.gz
│   ├── 8029a7678c3a9864931fa9ca11e4e1a384d8a77c.nq.gz
│   ├── 80ccfe5cc6be8ec98a24a80a954195bd90e2e96a.nq.gz
│   ├── 81803cf0fbce6cdd1d81f27836dfe7231db4364b.nq.gz
│   ├── 82cb77f057c170d7ad1dabad8f112596859f0198.nq.gz
│   ├── 8380f80b1b59941f3f93dc952686925193f7d598.nq.gz
│   ├── 8490a9b1e9437edbf43b81e3c86e26179772f144.nq.gz
│   ├── 85378aa1dfa61e6e472ac2da64fd581f607fbb5b.nq.gz
│   ├── 8557acf47a437db0fe4a5978677d59d092424318.nq.gz
│   ├── 8c366f54e5da68f11eb2d6138cd69f4dde5dd3a1.nq.gz
│   ├── 949930aaf9e4f54333ac8e78613a39fb4f2ca6bf.nq.gz
│   ├── 957af1ec0f05e0a603b3faeb93808e45876024e7.nq.gz
│   ├── 95d59a80d2f5a92b2acac32885e91b5b4968d1e1.nq.gz
│   ├── 9940dc56fb2c98a1c0eb3a6c134ad5bbf2b11851.nq.gz
│   ├── 99b505bad4ace15073d6201a27ead70ad2ff096a.nq.gz
│   ├── 9a2a2d8586d1091672ced3024449c97569a943d1.nq.gz
│   ├── 9bd0e90ae3ad5f570217edcb7ebf8a0932803b8c.nq.gz
│   ├── 9c15eb45106da1d922aba8f4abf09a7e6743c438.nq.gz
│   ├── 9d44a9fc52745e5ce264ac1b0329fc76f81ca953.nq.gz
│   ├── 9d59ff07fea2c606390f879f35c02243ee178925.nq.gz
│   ├── 9d650bd51946bedbb4f0b5ba3f40651fdddd86a7.nq.gz
│   ├── 9dbe4812aff0b1316d30f0513df055b5e19bb8f5.nq.gz
│   ├── 9dff6291066599b8527e2b56a160bad04087def5.nq.gz
│   ├── a1c3ef1aa34a6d6bfc64c53d9cdb182cb0ba799e.nq.gz
│   ├── a592f61387f2f47f16e019c9feb788c22d23ca6f.nq.gz
│   ├── a5950a28db37d3575a5297bfc525ba7efe692e01.nq.gz
│   ├── a6358312aaa8da5e5ae4e1b88d58fce819a81868.nq.gz
│   ├── a6d3e95e33091a2e2867063208b4a3b2d407164b.nq.gz
│   ├── a79d6645c0137662484702c727919efc1f60baa8.nq.gz
│   ├── a95cefcb12fd2800e0c0c7c92bb0ba4a90448fbb.nq.gz
│   ├── a9b027511f258f37211ac4ba8e83e3a72cabc84c.nq.gz
│   ├── aac298f20e2ef547eb7f5a50e713ca2ddc82521e.nq.gz
│   ├── aaedb9e534c6489193b73954cc1a1003602857e3.nq.gz
│   ├── acc90065050670f3ebd25367861dfe507debe8bb.nq.gz
│   ├── ad804f273afa0de41f1ac7a88b7a4758e089c8a2.nq.gz
│   ├── ae8ba79ddfbd1fb03d73843378b89043524e1f2e.nq.gz
│   ├── b1f143181d0a63b7a62661d69c53100bf76648f7.nq.gz
│   ├── b2daa0548d28bb0ea69b1eb463b9eecb5f352e4b.nq.gz
│   ├── b32d8fe14677e37581f1dc43ba3f65a0f6e318ed.nq.gz
│   ├── b4f6146d85b7746167fba27c8cbc2d06ed184d61.nq.gz
│   ├── b537da9795a1c94fab9d745916c4341912fc1ab3.nq.gz
│   ├── b684f00b5d9b2ed39cd104802411566acf126076.nq.gz
│   ├── b78efd2d57040584544f03a0088491865f6985fa.nq.gz
│   ├── b8298a28dec59363a7d5467227ac2bcf31420f26.nq.gz
│   ├── ba5e5fb3ef5781ecbfbf384370a901e09474df40.nq.gz
│   ├── ba8a3be8db96c8c6562ee2b83e0d26203d0cfb38.nq.gz
│   ├── bdb3701f0da3490710242bab2f544268c1b2d704.nq.gz
│   ├── c0a3f1f6208cd1c0bf144949ad2435a36ad3f6c3.nq.gz
│   ├── cab18cb610a796155c1da83beb3a572b92fd70fa.nq.gz
│   ├── cc9093027aa587d93bc283c81f5d6577b0b58eb2.nq.gz
│   ├── ce3798ed0db5790d1e3a896d0399cd40a7c00082.nq.gz
│   ├── cfb16564c66366a03fbb882c739684910b0cf9b4.nq.gz
│   ├── d0d0c83bf66e60a9d9dc2a0077babd58a9aecd39.nq.gz
│   ├── d2033d73b163fb47f45ea5757c18201677997e73.nq.gz
│   ├── d6409a0dd82d0c0350c0faed16e26120efb5adef.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d661de716975c932cc020d6ec87c6dcc52476856.nq.gz
│   ├── d857e030c244af3f36c6b8185b9c1451a9a46589.nq.gz
│   ├── d868762ad67f2f9b948b0cb00cae7fd43136105c.nq.gz
│   ├── da41cb110550a185d0d2fc5b3fd6d61d0f1514a2.nq.gz
│   ├── da6534b9bf3fce368a9957f2157cffe941da1648.nq.gz
│   ├── dc695064b258bcef63714128be3eb7486baee6aa.nq.gz
│   ├── dcf2c804da5e19d617a03a6c68aa128d1d1f89a0.nq.gz
│   ├── df3ffe3c705ad845e4ebf91f1636d47c553ae06a.nq.gz
│   ├── df903756c247850dd565d4b2a3ff063ea92b899a.nq.gz
│   ├── e085fd687a9ae5f50becec2cce761ead2d396ada.nq.gz
│   ├── e3de3c751d9f387f00c3ee03671f51dbc0323911.nq.gz
│   ├── e7362bc59c999d843e22b297e36dc9fbd1720f9a.nq.gz
│   ├── e7a9ba1b1a89dccbfb3275c2b285fc8c6c564a19.nq.gz
│   ├── ea13c82ce0f1ecb131a6c5061036f4cce10e96b3.nq.gz
│   ├── edd49edc900e3ab0471d9ab1cc71e8672a93d678.nq.gz
│   ├── ee4c4fbbdcd742229c35ee5954b5dbf827df0aef.nq.gz
│   ├── f0413b8df561a9a49d8e0190fbca30dfc1f3b309.nq.gz
│   ├── f10292889100453f3d06ce472d508ffc6a18aa7a.nq.gz
│   ├── f1c829c229ca07977e648d0682657ce1d1b1b989.nq.gz
│   ├── f1d0b30039acc24c610c17bc67882ab38afda349.nq.gz
│   ├── f6283eaee3f924dcb9e37cedac202a2b1f87fba0.nq.gz
│   ├── f7063f8fec45a518e82899bb234e6d40d955bf21.nq.gz
│   ├── f80acd94bb2396d1a016c47c0c1e40eccff2751e.nq.gz
│   ├── f8673dba8c2443bc9a3d6b8db1a1c30fac7bc628.nq.gz
│   ├── f8e03e17bea0893a74fba5596998c5acf7b9f6de.nq.gz
│   ├── f9dacce817340e738d097d4b3e7ec1948c3a8f63.nq.gz
│   ├── fa53b2b138df881c4c95239d0e4bede831b36ab5.nq.gz
│   └── fea7641292511a82f0f592b556bf5eb569f3bef9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d0d6a37515189b284583e5b25ae83975eff222b3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 185 files
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

[aio-libs/yarl](https://github.com/aio-libs/yarl)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
