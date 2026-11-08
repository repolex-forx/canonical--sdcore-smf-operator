# Repolex Knowledge Graph of canonical/sdcore-smf-operator

RDF knowledge graph data for [canonical/sdcore-smf-operator](https://github.com/canonical/sdcore-smf-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/sdcore-smf-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fbd23c366f886f6fef92d14d9af6cf45c347e4fb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fbd23c366f886f6fef92d14d9af6cf45c347e4fb
│           └── chunk-001.nq.gz
├── blob
│   ├── 07e10a08514124ce2ce63de2bd3fccecb89797e1.nq.gz
│   ├── 0b4c8167e48858b98a393b577849489b77c3867a.nq.gz
│   ├── 0b680d508757e960bfc1e7190cc29509514d1562.nq.gz
│   ├── 0da145eb10952836a212f32b8aaeda6f2adc9bd8.nq.gz
│   ├── 0ff992b299b3f0224c0a4575fb68ea04de62af99.nq.gz
│   ├── 11ecc7d72a89e4e2bed474b9698aa71b056b9e91.nq.gz
│   ├── 13af703428e23ce7d56cf7a1bc7061b64a8f6a18.nq.gz
│   ├── 2055a28de90818ffa33b0a2ff4e1fdbd93eb1473.nq.gz
│   ├── 23cabbd6d396c1bf9fc736ada81f7dafa80a2d7f.nq.gz
│   ├── 2c7c49f3e5c9a786d70748a1c01476518e077be7.nq.gz
│   ├── 30d2048bd9ec2fca44858f38e804d76049f8ac7c.nq.gz
│   ├── 356f4e013d6f743daf94f7cc49e1274905c2ae9b.nq.gz
│   ├── 3bcd8a9f726c1e7ff32172d0ed5d95ab6436a34c.nq.gz
│   ├── 45e50cfedbf7af092eea859ab068d292160ac862.nq.gz
│   ├── 46fdfb6ff31d8f845aa61ec8d9c441011982757c.nq.gz
│   ├── 4d394c33b8ea132a10ef09db97c9509d10e14fd1.nq.gz
│   ├── 5411236d6b63bc4bd54f36ff39cc6f7912a44507.nq.gz
│   ├── 55969d643048afbcfabdfa8a3314e271294fff2f.nq.gz
│   ├── 5a7c31d9beb1c7370116ff99e7780bfdb72a4791.nq.gz
│   ├── 6063f72f417271a6cba967b4e767ccd955d209b3.nq.gz
│   ├── 7bbbdf45bed96dd74d8c9566653b60262bd9277d.nq.gz
│   ├── 7c97b0c6ec3be11b3627fc6d1289357a39447ab7.nq.gz
│   ├── 8938b982a36e91872f3a51ff9c2c6a8e5edd4f5e.nq.gz
│   ├── 9bdec77ac5b29e31199d9f45b0a26f8714ffe787.nq.gz
│   ├── 9ca56a8830a92c94a3be6a6aeb3dfe77d9cd869b.nq.gz
│   ├── 9ddacfdd3a3125a476b88ddbeb2d0efd42521007.nq.gz
│   ├── a81c4625c094f11963e67c498ab3809ecb84c1f2.nq.gz
│   ├── b27f4d1d070bf448907539080278b4ac409a4279.nq.gz
│   ├── b71b4cc509157430395296c1b5291bbbf183dc69.nq.gz
│   ├── b79340cfacc5c7f6b2b3a06bd3d310d1665169c0.nq.gz
│   ├── bb82f45ba91a9b4b6e60d3e2d7bc7a5ee3283c16.nq.gz
│   ├── bbe77cb69558e274639017d0079c3ebd6bc948a5.nq.gz
│   ├── bc4b5a46de8057cbc11051996964b8cca6173a9a.nq.gz
│   ├── bd418d4c38a2ac7224a9d96b73029764359b499a.nq.gz
│   ├── c0d8645d1be721ddc8424dfadc7b811b63619f41.nq.gz
│   ├── d01d3ec218c3341b0efcc04120cea0290c5f3ca3.nq.gz
│   ├── d146025c7dc4e61eb913043ca644570032d59589.nq.gz
│   ├── d416e72111d79598732c2046a74b463543d9121f.nq.gz
│   ├── d54e174965cd46628cb383227260a3687f776d53.nq.gz
│   ├── e5251e8aa7150b593ca996c0836e508f5782cd37.nq.gz
│   ├── e633ee90face0dd9d2066a040489ffc54aeeb23c.nq.gz
│   ├── e71e17279d2943dbd39b786ef1599eb9d3db8f1b.nq.gz
│   ├── e8a04a7eee7a49475fd1737b79b4510f9ac8cb46.nq.gz
│   ├── f0571dc2b05049fc3780efcdffbafae38febe7a8.nq.gz
│   └── f8141592b3d01b79a419cf1614719a722d5858ea.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fbd23c366f886f6fef92d14d9af6cf45c347e4fb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 53 files
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

[canonical/sdcore-smf-operator](https://github.com/canonical/sdcore-smf-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
