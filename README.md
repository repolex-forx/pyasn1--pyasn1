# Repolex Knowledge Graph of pyasn1/pyasn1

RDF knowledge graph data for [pyasn1/pyasn1](https://github.com/pyasn1/pyasn1), parsed by [repolex](https://repolex.ai).

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
lexq download pyasn1/pyasn1
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── af65c3b92e9deeae50db4de390982dd970d87f98
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── af65c3b92e9deeae50db4de390982dd970d87f98.nq.gz
│   └── repolex
│       └── af65c3b92e9deeae50db4de390982dd970d87f98
│           └── chunk-001.nq.gz
├── blob
│   ├── 014373489cea72827f4789735d21d603de02692d.nq.gz
│   ├── 02368d0a3cbf4d62b2e948d157d686b4a4780dcd.nq.gz
│   ├── 034870bc290c4ba375fbb9ba8e9e398fe953c044.nq.gz
│   ├── 03a960dfa8b13c0f4243f66fbe38197e8637594b.nq.gz
│   ├── 05b84048af6dde1f5e78831d8459ad30064a0166.nq.gz
│   ├── 066d03aee3cf83c76970190c9cd37f81a1743925.nq.gz
│   ├── 07194235466a40c96ed0bb81f4874793e7680cbf.nq.gz
│   ├── 095fc83a61c5c46dc9778c8186296b8efc2f479a.nq.gz
│   ├── 0bcfd69efcde227f1e8897e4806f1378867a77dc.nq.gz
│   ├── 0ff082abc2a97da934b6c86aad57dde542f2d001.nq.gz
│   ├── 11bf38453a2a8b5ff2f14ee8db9e0717cc803297.nq.gz
│   ├── 11e96f00716b2cbf9e6a48aedeabfc30bb191ab0.nq.gz
│   ├── 122d7275b39113394f4b755d1df32cd835d2e0d7.nq.gz
│   ├── 15465b81ce2e9fd1516d9ec9a6b1c49a4a7271c2.nq.gz
│   ├── 157fed064f0856fb60ea833e6cde84f4316b0c92.nq.gz
│   ├── 15a806459870dbabbddce63277e885ba7ab27d79.nq.gz
│   ├── 163a3a0506c7aad67f0a7586619658e342c0d2dc.nq.gz
│   ├── 17b98553275c7fa1e0b503ed69f12ea40c703cf1.nq.gz
│   ├── 1aed4b97e5845870bd3c664e13bcb67815499e53.nq.gz
│   ├── 1e55c8925b6a3e4d73e9a5ccebcaf817a9156ecd.nq.gz
│   ├── 2095b056633c7bbb1cf7db5988ea510b1941302a.nq.gz
│   ├── 214532e671630d8a7ed3303cffd9f9f166e6d1cc.nq.gz
│   ├── 23560098fde60278c86c1e982160f8473ffc54cd.nq.gz
│   ├── 24d1999a7817d12715bd60b6b44fa3d265b0bbc4.nq.gz
│   ├── 26dde362df49f837ce4033c1f3d8ec69e4a613a2.nq.gz
│   ├── 26f242431dc93e551d3cf95d85cfac1b7630351e.nq.gz
│   ├── 27ddf808f540de5b77588f77e1d5d4a4ddf3c86c.nq.gz
│   ├── 27ef4011bc5d85002b34467759b3760806edaa1c.nq.gz
│   ├── 2bda7167c50ed6e870c722357d8df8b10521409d.nq.gz
│   ├── 2bef454f0b01717942af8a67e839f9871f9f01c3.nq.gz
│   ├── 2e2bb9dfd86593579314f939679521647cec6b91.nq.gz
│   ├── 2e4ae7b766b6b4d9986263707537eaa29c7db8fd.nq.gz
│   ├── 2e553e63247e5de311beb5d9c6f7904294eb5f3c.nq.gz
│   ├── 2ea0be1378e9530780b78210374c4cf9a9e6fa45.nq.gz
│   ├── 2f3cfb4bc4a6c372c8142342588246592fe9b7a4.nq.gz
│   ├── 306210e5d9e7abf77946d545bd8e8c90bd50ab8e.nq.gz
│   ├── 31434db2c44bec2b5701c2c8158640a28de25949.nq.gz
│   ├── 31ea07b4b92bbb0b45b534baea5b600d07397e44.nq.gz
│   ├── 323932bb3c689f173191995d80ca305e1c6c5e75.nq.gz
│   ├── 3607616b55df0473ffddb78469689e775932a8e7.nq.gz
│   ├── 39fc3a1cff1b3878f25855bb3f647a13c01b8abe.nq.gz
│   ├── 3aeb6703f5d2c0ff1d07af1f21cdce78e38f2a52.nq.gz
│   ├── 3c947b8679789a0660f5a22273073f9423a5c502.nq.gz
│   ├── 400f7d1e8a8767d603431599198b071553708c24.nq.gz
│   ├── 41f0f29d399480a640f5a303b0d7a2d87ea7a101.nq.gz
│   ├── 4610446850e7039a84879d9b283d06202684a9bc.nq.gz
│   ├── 4617428bc16a2f853771eae25cc74ad29dd277ed.nq.gz
│   ├── 4655019c16c0955ac1cdc8cbf70d8e38844641b5.nq.gz
│   ├── 46a6496d03601eb6e1a7677053c0db542f7ced28.nq.gz
│   ├── 48556ba683637c4eea07f45cbc50efe29e695b65.nq.gz
│   ├── 49c00f5eb0363685b1ab5127abf7f91f2427b296.nq.gz
│   ├── 4dcfabb9083fcfdf05ce051ed0d9719f302d7b31.nq.gz
│   ├── 4e5510c63f1182f89377d54a40fc70965e036f0a.nq.gz
│   ├── 5553fcc0a79ea1d441de39e57cfb56492f576d38.nq.gz
│   ├── 562440b7af3d52a4fe0c34426d81d633255d6500.nq.gz
│   ├── 56e593e8bd588120c65d8b9e09bd8a3d8a366f15.nq.gz
│   ├── 581c20f9b452be5413643b68e7fec9bb2122ccf7.nq.gz
│   ├── 598b8430eff95ffcc7152feb2c9668d716f1c8eb.nq.gz
│   ├── 5a15f896da338a4dee9979f31b68d42594e92989.nq.gz
│   ├── 5c79ee7cdfdd2a9de4cc9fee98905b378d12151b.nq.gz
│   ├── 5f6c4ca35263b09fd180d02cd78962047cd65123.nq.gz
│   ├── 610841cd8adec77309b44824207ee1cda9349a2a.nq.gz
│   ├── 62444df5cbed61cc032afaa5f9a7f34f92ff6f60.nq.gz
│   ├── 643baf1053081b3ab9fc3b9542e6f27cefee3347.nq.gz
│   ├── 645c0a18d313f3104e3cfdd0c8828a8d558699db.nq.gz
│   ├── 6593b384143da2e5ff5946f4e996bf42c9683b03.nq.gz
│   ├── 669463392f58c3dae9564aaad64ff1266b3381c4.nq.gz
│   ├── 67ff23e3c09d26291a46b45b5a8a5f1790e30b31.nq.gz
│   ├── 68ac6f0fcbf2efcfc80e6bbe0225bbd0e6688d36.nq.gz
│   ├── 6d057d882f41375448f7e03e1e6ca9bd558a61a2.nq.gz
│   ├── 6e347926a5ee4898db763201ff22ee270d5c2bec.nq.gz
│   ├── 722c062047f0b8170930d8b95b36797a3910691c.nq.gz
│   ├── 73f86c75de16e6b85c8e3ebe88810c60190c3bd3.nq.gz
│   ├── 7429ffabfb29ac56d22c8c0093a37a96dc336909.nq.gz
│   ├── 75c9a3f4cd09dd531f7eea8738d9ba4191389b78.nq.gz
│   ├── 777b25f12d7b202fe9cfc47a49eedd8a3d66da00.nq.gz
│   ├── 778720ae955ec990b98ca81c31db6148e7e77394.nq.gz
│   ├── 78c62baa60611af5489d88364b3c34ce7c0e1408.nq.gz
│   ├── 7bdfa8a378cadff037a5468156481a6bef43719c.nq.gz
│   ├── 7bfafcfeb3c81c61bc858a0aa4b1a42b61983530.nq.gz
│   ├── 7d57774df64882057256d46d96d654eebd8ff46f.nq.gz
│   ├── 7f8a955ac28e54ba63be39ee5d24fcb0c918c107.nq.gz
│   ├── 83ed3751ff06e51faea2346668ec7c9b9bb647dc.nq.gz
│   ├── 86d08c47eb83647482222ff5212548bdb2f8bfa8.nq.gz
│   ├── 87090669689415e666b425fc5efb5da59e8ffdc3.nq.gz
│   ├── 87528bb8002eeb90f5a64a5e486356003956605c.nq.gz
│   ├── 881ce19b7dd79f2879c77a8b224ec6cfe79a4f50.nq.gz
│   ├── 8c3066b2e68f1883e46f696491daad967ba606bf.nq.gz
│   ├── 8c91a3d285d30fc06838e70478eeea8c64c9c2bc.nq.gz
│   ├── 8cb51c432f8935b2ba0dd65f88a5aae18b3afbc2.nq.gz
│   ├── 8ce930319b40efdcafa6d44431632ee343682bc4.nq.gz
│   ├── 8ddeb97f8bb14e882233befe42c1c8320c65a14f.nq.gz
│   ├── 8e00138defa73e60a81364b3e70344f0603fc28a.nq.gz
│   ├── 8eec8420e28b5714aecc3b21fd69afc0aeeb466d.nq.gz
│   ├── 94fe04d5241b562f3e4acf55399fca1a969d847f.nq.gz
│   ├── 9769d959446a2a6a6b83c677467855c136831053.nq.gz
│   ├── 981f84e8a65b98cf580ef70a592ad70ffe02ecca.nq.gz
│   ├── 9a35a2a41dbef8bd7dd4b775228833508dc7eba1.nq.gz
│   ├── 9aff5e69513ae1027387198559dd8e76099b8246.nq.gz
│   ├── 9ced46953d3bcd81c3c44fabfe9a259e0c8a9597.nq.gz
│   ├── a0e3247b34f8bfee08fbda9150a7c3a9d09ae015.nq.gz
│   ├── a1f1bc7d53083e28c671463f3335bb3f0ff10e09.nq.gz
│   ├── a3a91ac2c32872721c33ff308c065bd44c36f148.nq.gz
│   ├── a4e2424ae25d96e1b7103f880fb3053cf3e92baf.nq.gz
│   ├── a984a346863c4b608108723f4310404f1ca4b4a5.nq.gz
│   ├── aa86e520c8407a243232612b7146bf89756ddb73.nq.gz
│   ├── ab225ae106de7144d19e1c0b4c6d9b04e73195c7.nq.gz
│   ├── ab24c073069b6e8c19d28bd25f727f85f6714c00.nq.gz
│   ├── ab4021a62a7678e8bfae3c255cdcd52ed20d1fe3.nq.gz
│   ├── ab7faea8775b39b4c198dfd77258c4fa65697e03.nq.gz
│   ├── ad5cf8afa86ae7fb2f9f433710d4bc1bba0e57e5.nq.gz
│   ├── af66afb11e4d79809eb9c8870d79c05b103e8db6.nq.gz
│   ├── b02f0723ca228ef05a2027f6f6c549efad4bde5e.nq.gz
│   ├── ba0ca2755e3feecc869abce0e18c9b489143d1a0.nq.gz
│   ├── be8a04c6b0d3fd9f6c634ea96df47441dfdd6abf.nq.gz
│   ├── bf416f6be98dec5ddcf0a72989aca4b2391fe75c.nq.gz
│   ├── c0c1b344ab3dd5e7a0590fd2b55c0ce26ae6fd26.nq.gz
│   ├── c1e88c08b7fcd440d72fba0daa40b3c5df7b1a9d.nq.gz
│   ├── c35f24899bca4defd54ec0744bf46a8f831f69a7.nq.gz
│   ├── c4dce2eedcfb0349ce5a48d496c26fc13824a39a.nq.gz
│   ├── c605b0eef094a35e5cc8b67a6a765270b3b3b213.nq.gz
│   ├── c767625622948dd100be2682501d876ed46af2fe.nq.gz
│   ├── cc4ae0b99f1328244c4c5f45bb6b6f4cb128880c.nq.gz
│   ├── ccb8b00cad9d3a71ed0956dbd1daab107ad91aca.nq.gz
│   ├── cf3a80fbda0eb3fc0e9ea4b7660f67de58195977.nq.gz
│   ├── cf7101b52f394e26fbc2718762fb756154ca9013.nq.gz
│   ├── d0ffa0742fd397bc37d4c05bf5d7f18af98292d7.nq.gz
│   ├── d1f5b8514834742d70a86b3b754bd73c5540bacb.nq.gz
│   ├── d3e676ac6a56b74a71c8b915ab2b432deb8bf027.nq.gz
│   ├── d42f3d90f7acedacf945005dc9009d4df6e8c3c2.nq.gz
│   ├── d546e1c77c7fda6dced0efbcdcc3331ebb64f431.nq.gz
│   ├── db0ee33414d1ce97085b1e71ac2b9124c088d871.nq.gz
│   ├── dcef4bd8a14189475e6fadd45b989d6f271d43f1.nq.gz
│   ├── dd4f0c523ea0100740c1cefaaa96964c316b161a.nq.gz
│   ├── e6062aa704061e5652b2db784f4204a9e41f9042.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73c9599cba1deed5f3196c2511cafd409140b02.nq.gz
│   ├── ec65f00621dc958075cbc42948886dd9d622729e.nq.gz
│   ├── ed5446bf1ad531e6b6aec5490ae91e13eae768bc.nq.gz
│   ├── f025d760d9dfbedd3046d5b2558a506b2e718d76.nq.gz
│   ├── f1556b0a07617f93d9b8911edbb4556df13897eb.nq.gz
│   ├── f203d0844b7dfc261de1001be9a2a82bd1efa0ae.nq.gz
│   ├── f73ece1e39cbe826340d2731338d60f62bc7567a.nq.gz
│   ├── f7513d8d9eeb0205aef3c006222c9fd368cc2b5d.nq.gz
│   ├── f7bf4f615f1a13264e3c3fc19cc59f560547e43f.nq.gz
│   ├── f96002419fed851f826d5fdbd13353b7ec888189.nq.gz
│   ├── ff38c970113241fd7feb48d53f14a30c043e982f.nq.gz
│   └── ffb325c92e5fed0e497bf8c079d8c95c2c77db14.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── af65c3b92e9deeae50db4de390982dd970d87f98.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 157 files
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

[pyasn1/pyasn1](https://github.com/pyasn1/pyasn1)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
