# Repolex Knowledge Graph of intake/intake-xarray

RDF knowledge graph data for [intake/intake-xarray](https://github.com/intake/intake-xarray), parsed by [repolex](https://repolex.ai).

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
rlex download intake/intake-xarray
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 719a7c84b58ec6783b07e648fbfaf988ea4c453a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 719a7c84b58ec6783b07e648fbfaf988ea4c453a
│           └── chunk-001.nq.gz
├── blob
│   ├── 01068a3c74e7ffa4851366c633538a739d92cb24.nq.gz
│   ├── 016005ab7e4b29a6cf4609a5309c960a628777af.nq.gz
│   ├── 024618e3236a4c446099d3f56f50ff53f4de2f45.nq.gz
│   ├── 02f0e7baa25ef2410a68479543e96ce0c8b9ebc5.nq.gz
│   ├── 03b39306d733e2663d09d7b0b87001a438f4ff8e.nq.gz
│   ├── 049e3a8975fdee286270e51eae37ac50529f5b77.nq.gz
│   ├── 05f78d79469f431b8e2eebe7ee38d65e3689173f.nq.gz
│   ├── 0aa92cc6f11a9c2630a29cf17b39bd163b1e6d6d.nq.gz
│   ├── 0e93b58377a6501ec208ef4b28540d26a979f07c.nq.gz
│   ├── 10d6d9b2505f049662ba1e88be91a42a509394ff.nq.gz
│   ├── 188397fdee5b10a3f9d56f386c9050a761831bac.nq.gz
│   ├── 1a8ef617965a357ad198b7bd8d1e368be961b5fd.nq.gz
│   ├── 1d7432abe309dbe90b034879015e5198142df5b7.nq.gz
│   ├── 1e3a03140c21a9be02ea703cdbde44512d940369.nq.gz
│   ├── 26ed4ea7008e194949a8d13af38833582c06cbbd.nq.gz
│   ├── 28051c300469750cb85c03270f0c6e25efa8da13.nq.gz
│   ├── 2cc4550ab577a6b860e3be0948e73c4d44e73d22.nq.gz
│   ├── 2f1a0636e713f2cfe54a6715c33fc1520bba9c3c.nq.gz
│   ├── 3351db8ad1968657c2d20ae6b74294162769684f.nq.gz
│   ├── 3474a9b71ad3becc25e3ac62df187dcf70db2bd2.nq.gz
│   ├── 3b2ce6a06d1b3675598a75fcb0e3f6dd2a7ad43d.nq.gz
│   ├── 3b7daf227c1687f28bc23b69f183e27ce9a475c1.nq.gz
│   ├── 3b81877c644a7841bd4daf74ed947193bb42ade1.nq.gz
│   ├── 40a96afc6ff09d58a702b76e3f7dd412fe975e26.nq.gz
│   ├── 411936e186d997a128a6e38de2f5e471f2f05edd.nq.gz
│   ├── 451a91ab6f2f546ed84992255454cffd641aab20.nq.gz
│   ├── 47f84f50f4302bf749b24e14dfe0f40f750632eb.nq.gz
│   ├── 4a9e5c992001a3653b20fdbed1033c6342109c02.nq.gz
│   ├── 4e9180423804e79dda634eaf4241855e6788ecdd.nq.gz
│   ├── 52549100fc45d70a0020a57029634e4b967583f4.nq.gz
│   ├── 54953f8b51b4b2fe5de0081d86866bfe0d854639.nq.gz
│   ├── 5775622d0ef85828b436dffcd21366f7538fc55c.nq.gz
│   ├── 5dd4be5251bc9b37f596091d3302d77f701a7e50.nq.gz
│   ├── 5dd7b2bc465d0990c180fbb66cfabe1b195971a8.nq.gz
│   ├── 6d00a50666cfe6033e15a048ce1c16af261988bb.nq.gz
│   ├── 6ddc166617fcbb207710b0e367a1199343d137ed.nq.gz
│   ├── 771b6397721fd579172217d47c512a5da2aa0451.nq.gz
│   ├── 89561625eeb45cd61fd88cab8f14bf65aa94f4fa.nq.gz
│   ├── 897fececebf37ff4ee52473c96ac919c46c42cb6.nq.gz
│   ├── 8c5d04f3a5e8de3c003f1516972e16535b5451ef.nq.gz
│   ├── 8c6341d139faba9a07557f3dcf481220e1e0b260.nq.gz
│   ├── 8f52c0d0a80238e9f410b848539b58502aa3f7a8.nq.gz
│   ├── 90b9e3f6f49529c3524d486a066e96b0c2e35588.nq.gz
│   ├── 92750894dc4ad926a85984d36a8f0de7097e753a.nq.gz
│   ├── 9396ba2d164527e3c220b0ddd37c3c76042d6b38.nq.gz
│   ├── 94958a6fd42e35eb347008d0ab96cf0088704ebe.nq.gz
│   ├── 962985d0dbb7009e7cb9adbb3f834774e0de8d97.nq.gz
│   ├── 986b1b10ecafa173a672b8b435a0efce7ae30bd8.nq.gz
│   ├── 9e9eb3d081ac7efa6b2bc53f756d4d1b17867d56.nq.gz
│   ├── 9f8880bef9963bbd89cd852b7a7d88cb32b5f61e.nq.gz
│   ├── a03bdad00d032ee911f3a19a4298b6c35fa0969c.nq.gz
│   ├── a5a87190e33b6e8623fff5e40f3a1bbfc30ed27e.nq.gz
│   ├── ab63c31ce692aed98f4e407e82f7b79ecca3f2e1.nq.gz
│   ├── ad5584078971c96b8f12b9b2ab15a9b1319649b3.nq.gz
│   ├── ae9e3a92e5577d49e84ef4ce97438bc7921dbe11.nq.gz
│   ├── b2cbdda5e3a1f1d2d8f392fb0c0fe0bd356edd52.nq.gz
│   ├── b72a6a70c69d5abf9b7dc8d4ef5a561935a5b8c6.nq.gz
│   ├── bb46e664092a12f9e525bfaefddbedfe3c4f51bd.nq.gz
│   ├── bbd99e943f7dcecdfde735203c4fc47b4ff44b66.nq.gz
│   ├── bc0c87aa8ef0f9ce5bcaa932a4dc449b472af0d0.nq.gz
│   ├── bcf5323526735f8a7026b961d8985c97f8ea4e8a.nq.gz
│   ├── c502b24d54504caa0df1bdaa400f4eba1d45bb25.nq.gz
│   ├── c7b903f02a8701ca0012abcff0313b807ad1183c.nq.gz
│   ├── c9eb99d6c1286c2810cbd0bcde61ad523dc7f030.nq.gz
│   ├── cd19c3a248d74811ff445a36c94e51202e4bb252.nq.gz
│   ├── ce4f4d4a782ee233c2a0b62e7e4fd08d8bc3429f.nq.gz
│   ├── ce5fbbfc4bbc335b2f4725ef89345fa8f538e6d3.nq.gz
│   ├── cfbda76d287fa1f56eeb5b553753d7c50d048971.nq.gz
│   ├── d01ae344ba3ea0971bd0986d8b067537754aeaa7.nq.gz
│   ├── d208b5c59acf74026a2dcbc2fe0cf0016385fbca.nq.gz
│   ├── d2e8d45e239e7f804f33d4b21cab5e297629c445.nq.gz
│   ├── d75f49eb75d7ae3562a1c7fedda6b52f3bf2fa00.nq.gz
│   ├── d7b3f1514d5e21a0f5168ae13515c32ce0ed65fa.nq.gz
│   ├── d7ebf18fe77e26159846e1f6d2f5e1780976c3ea.nq.gz
│   ├── dc8ebff67924ed928369984395c6e89ff6b4e66c.nq.gz
│   ├── e013df9cd2149f61007a5f78febe955c2d583f06.nq.gz
│   ├── e41212e37390ce830ed94d32fa51ed8215ffdefa.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e751723c35e0183eac0267218897478a1f30e5b9.nq.gz
│   ├── e81e791944db4a22ea5e7608c59d89604d2dc5d8.nq.gz
│   ├── ed8d95a20c0858b6e45da14f6a602dc30cb3c598.nq.gz
│   ├── f0b8b96fbbebdecdd1d8cfd8c77a74f9440c5741.nq.gz
│   ├── f62f3ea463b9c82cb061c7e370f3ecdbfdeccabe.nq.gz
│   ├── fac54589234e4bc51dfef547696aaf73d980f5e0.nq.gz
│   ├── fb09f4b9b93e66c5ad941fba8c961d99ba11f074.nq.gz
│   └── ffe8d472f2696f427c90e725835df1b217bc5a91.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 719a7c84b58ec6783b07e648fbfaf988ea4c453a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 94 files
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

[intake/intake-xarray](https://github.com/intake/intake-xarray)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
