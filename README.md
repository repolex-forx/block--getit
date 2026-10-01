# Repolex Knowledge Graph of block/getit

RDF knowledge graph data for [block/getit](https://github.com/block/getit), parsed by [repolex](https://repolex.ai).

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
rlex download block/getit
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f1611b11198bf981f03e48896c5d13b418d596d4
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f1611b11198bf981f03e48896c5d13b418d596d4.nq.gz
│   └── repolex
│       └── f1611b11198bf981f03e48896c5d13b418d596d4
│           └── chunk-001.nq.gz
├── blob
│   ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
│   ├── 081cbe83449cf8e625a3e2e79b6b35415c4e1503.nq.gz
│   ├── 0ba9db25329d0b336e39ca8cde8470c5b7bc45eb.nq.gz
│   ├── 1822665f0f8175c1c583af81e56df4bc2eb33ae1.nq.gz
│   ├── 1a61f5dabf8d650488d80378ae60997082980116.nq.gz
│   ├── 25f0bc5ed80683a81f46e6bfd1cf8ea0b56c6807.nq.gz
│   ├── 31559b7d115e3c105b328cce9b9dcd9774025061.nq.gz
│   ├── 328d6d010fb58309a85667762a9b53e9759788a2.nq.gz
│   ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
│   ├── 3bb03b13c01b373d8f4ad3c16a8789bd58a86115.nq.gz
│   ├── 40c81b89159bb5b05459dac4adc6145b48af5b24.nq.gz
│   ├── 47ccafc11b6e546a481c3c2151fbe894322d88a2.nq.gz
│   ├── 47e4c5a4915f1c106cf29759e9fb9bf0b710363e.nq.gz
│   ├── 50284b70436acedfb243c4ccd64d6e87a6bbaa8f.nq.gz
│   ├── 6065f337c87bb44d479d8c6e490d574b259f824c.nq.gz
│   ├── 659b36b065b2432d374a6700e386531120365744.nq.gz
│   ├── 6739a45c80c63419ec49d82485d1b160e5965897.nq.gz
│   ├── 694e6905a7e729bdb51740224f49c0bc0aa6b212.nq.gz
│   ├── 6a81f4e21b7024432e1aa42c667ed75eedd1164e.nq.gz
│   ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
│   ├── 6c025bc563895062e8e9558416c1926d60ee2245.nq.gz
│   ├── 6ef247b5f24a61afd3aeeca2020c75ff13301a87.nq.gz
│   ├── 7845077a8d74b49d7cf883844d17f0e379783254.nq.gz
│   ├── 816066f4755caecbea428ebfe33fecd477e0bb7e.nq.gz
│   ├── 862ee3c28647e7a58801a75236855c269c1448ae.nq.gz
│   ├── 865a3174b5ff36e4e29acbfdd54a9e368595848e.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── 9fdcfccd997b78a6f3234b399536c92b8389989b.nq.gz
│   ├── bc68c0d6291b5b698c18eee364ce04302f3e1910.nq.gz
│   ├── c680b0adb7ef5379c01f8057c81b5dc97e178676.nq.gz
│   ├── cddf96399ad93327074bbf961e3dc04d20ab1ff5.nq.gz
│   ├── ce8a976a4ea32f1882dee4fc2097afc13f3c0e77.nq.gz
│   ├── d0190605b96e388f42dfb2ed6713a5aacedd027d.nq.gz
│   ├── d3040413333d2ac5945e75f19601616b32c72b22.nq.gz
│   ├── dbb2c93e46d41c4fef6997842c11b9584a04e38b.nq.gz
│   ├── e4c9326424bcf20e95f8971da5653d3305db206e.nq.gz
│   ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
│   ├── eeb991a97c654e6eda45f539f4cde282153164d2.nq.gz
│   ├── eed0bad04eff1a982ab9ab9e81e8a300aeae577f.nq.gz
│   ├── f3f308370dc3ae78f7600fbc7ebe49e2f3cdece6.nq.gz
│   ├── f83ef8d4532216f2181142ae0bfdeaee074d8558.nq.gz
│   ├── fb6d193b736e9328861731e2583ac518d06b928f.nq.gz
│   ├── fcfc9173746b49fb0f878b6a476ae38a8d66d845.nq.gz
│   └── fe28214d3352b0ed40820a4999317694c8b1ef57.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── f1611b11198bf981f03e48896c5d13b418d596d4.nq.gz
├── filetree
│   └── f1611b11198bf981f03e48896c5d13b418d596d4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 54 files
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

[block/getit](https://github.com/block/getit)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
