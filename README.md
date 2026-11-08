# Repolex Knowledge Graph of zenml-io/mcp-zenml

RDF knowledge graph data for [zenml-io/mcp-zenml](https://github.com/zenml-io/mcp-zenml), parsed by [repolex](https://repolex.ai).

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
rlex download zenml-io/mcp-zenml
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3de0643d36407566559c7d9e8e01114e2f5412e9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3de0643d36407566559c7d9e8e01114e2f5412e9
│           └── chunk-001.nq.gz
├── blob
│   ├── 023ecca0d41e11c545eebf5e9873fa8f30509a23.nq.gz
│   ├── 071ef4e17ea0b74b2fe67928260ddfcc04b36136.nq.gz
│   ├── 08578e62c88b80cb7193b6e1ffceef48a949fe4b.nq.gz
│   ├── 0a2ff30c691b053e3b10221a4348e43727e21d52.nq.gz
│   ├── 0bce94b5e47af9b30aaab9a14e9b6e41aa77f103.nq.gz
│   ├── 0c53688d84b3e28c00ae738c1d2385fd8f610bf6.nq.gz
│   ├── 1ad3a7026cfa079c2cf03c56633da6941e27601e.nq.gz
│   ├── 1e93325eeb51fdab72a818dc23b67e0b678479cd.nq.gz
│   ├── 1f138c42e90e9442ac3e8ffc59274d93b63f3ccb.nq.gz
│   ├── 24f6941a0a4014a62d099c97f05cdcab4fb90cdb.nq.gz
│   ├── 28a7f8d1a26cf35d4791e024b38edc557556a6eb.nq.gz
│   ├── 28d71500e677ebf89ae0966e8a82d93844759d3d.nq.gz
│   ├── 2bcb067a676d6223b819561072cf866aaa1f1046.nq.gz
│   ├── 313998601410fcc6ebb9f406e21a6f0db385ada7.nq.gz
│   ├── 3538f151ae11378b3e52c9f07f46f896a5e903b6.nq.gz
│   ├── 3b1582e0638e3bf9218fc5d2c441ed557c1c0fad.nq.gz
│   ├── 3e3c2f1e5edb083aab93646ac7b076daa38516dd.nq.gz
│   ├── 3eb3f266f2ecabab5f0394ebb4466b768db5034d.nq.gz
│   ├── 4358e0e110f399cdf02dbe19d84eaa5374a316af.nq.gz
│   ├── 440b234077f477fafd8c52fbd03d5739dfe1fd60.nq.gz
│   ├── 473b9a4503128db4a925710b931061f06c0cc287.nq.gz
│   ├── 4b58eaae3758642186ada390a211c73c03cf950e.nq.gz
│   ├── 5306349c46a1653173f8f2bf9d795716a18e2f35.nq.gz
│   ├── 62ed75166be2a013fb749087f4c97c44470310eb.nq.gz
│   ├── 6d62ac44e3c8bd6c8f984ed15e5654173e1fe671.nq.gz
│   ├── 75fd0db8a533caf3ad9e99a6a64af76027467718.nq.gz
│   ├── 7c7d96681e4a205bca3da3ea5c618eff9e55f24b.nq.gz
│   ├── 7cc59292992ab50b50ffc6b54e05abe4abf84ada.nq.gz
│   ├── 7f6f58acc2202ba0549dacd83218a13b1656fa2e.nq.gz
│   ├── 7fef03e33bcfa03177fe14eeea1881ae5f407c7a.nq.gz
│   ├── 82259a09b94545e5c8a1c52637e65a50ccb1e899.nq.gz
│   ├── 8236bb591f6dd055ce1680d61bb981edde98bf24.nq.gz
│   ├── 91ee4de1d30257949f3a445d311d8ecb82c3963c.nq.gz
│   ├── 95a4aecabee7b8f7e2251877088c0e00a6843ff6.nq.gz
│   ├── 97795ac34576c3ccf65182850c046b6aa4e3a230.nq.gz
│   ├── 9792e43651e1b3b061de9090e0378eeb47a5e882.nq.gz
│   ├── 9941c1d6b41fe8b81eda74fd881634f86fe0ca99.nq.gz
│   ├── 995ba23d36194383bca35cc30ea64a58fcb2bad6.nq.gz
│   ├── 9dae3f489575f95460db2dfca3e3101a63c38968.nq.gz
│   ├── 9fb892240d22ced8fe8c2967de67f37a0c9f926f.nq.gz
│   ├── a16916407c76c75ee37e56665be2265822966a8e.nq.gz
│   ├── a689c83e1747c5d5f52e714678676fd33e242767.nq.gz
│   ├── baddfa6b768f581ed15517fdf69987545d7f299b.nq.gz
│   ├── bb0ef861e54274ec3b56bc89cf509964a659f75b.nq.gz
│   ├── bcf052b9be2d2855f557ec5e006f6ad470cfaf4f.nq.gz
│   ├── c3ce73d6a8d8f192994837b958aed1f95ca51765.nq.gz
│   ├── c453767aa60c28716d37bbe55ec5a60c23d25c8e.nq.gz
│   ├── c8551ed00ccd4d811938b19e99555d1803d322eb.nq.gz
│   ├── cd209b9ba6a0df3662ec00c57979969d625879d9.nq.gz
│   ├── ceb23678251a4543ae017d6a74b1279deca21760.nq.gz
│   ├── d1869b3448234cf98b5f1b0a3cb33acc3397105c.nq.gz
│   ├── da11c3182cdca933c8d265c6e19f79a4346e947b.nq.gz
│   ├── e7935fea9a3806998e01cfae96d98f402d92d1c6.nq.gz
│   ├── eae83634c7373b4b3ca18f26d3a91d26692ca162.nq.gz
│   ├── edb68e84d1fec656e28a809c9d66753a28a70c62.nq.gz
│   ├── f319df89209bc55152c5e6fec6a8f9a4ba29ec9f.nq.gz
│   ├── f900edd0cd636489a8931af9fcee6f91c565b5ec.nq.gz
│   └── fcea2b4ed24aa3f6e29e82047d2daf71235a78c8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3de0643d36407566559c7d9e8e01114e2f5412e9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 66 files
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

[zenml-io/mcp-zenml](https://github.com/zenml-io/mcp-zenml)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
