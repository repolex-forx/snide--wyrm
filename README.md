# Repolex Knowledge Graph of snide/wyrm

RDF knowledge graph data for [snide/wyrm](https://github.com/snide/wyrm), parsed by [repolex](https://repolex.ai).

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
lexq download snide/wyrm
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fd41b56978f009e8c33cb26f384dd0dfaf430a7d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── fd41b56978f009e8c33cb26f384dd0dfaf430a7d.nq.gz
│   └── repolex
│       └── fd41b56978f009e8c33cb26f384dd0dfaf430a7d
│           └── chunk-001.nq.gz
├── blob
│   ├── 037c26da4aa94d882cd8060f1dedccb566d9b025.nq.gz
│   ├── 112f5adef8c87444ddb56f8519f199b8438109a7.nq.gz
│   ├── 11e4b9416b59eb448b3e04a41cb2b655063c91ac.nq.gz
│   ├── 1406d9d09e751d259daa31be895727e81b1640c1.nq.gz
│   ├── 14dab83b1a1bc77c8aa83f4b5f22a2ed2b9859c2.nq.gz
│   ├── 1810775ee54c4a280f96ee83af86474808d8fc12.nq.gz
│   ├── 1cf2ee624c16fdd9489ee5d6a6b98221a8136667.nq.gz
│   ├── 2dc5186c411bfae225ebf86e5afaccdceb6fc3a7.nq.gz
│   ├── 2e853537e5e53ad3e5070090b8312b162326e35b.nq.gz
│   ├── 2f1626698bbeee21be2756a3a8890c215bb5eeb5.nq.gz
│   ├── 34a0ecc458110474a65c4b0e64d6b9524216c9b5.nq.gz
│   ├── 3a57582f235a4c94a28e7b3ba7e9ff25e1fb7981.nq.gz
│   ├── 3aedcd171e6327bfca6963cf34b3fae217a9a2d5.nq.gz
│   ├── 3b4a81ca8bcc13b128254b07814d15145361e362.nq.gz
│   ├── 42a2af6ab7116d8859c13f401cdcace2b361fca1.nq.gz
│   ├── 504ccd59e7ee1dc8cdce80bf93f1ca3690c0db2b.nq.gz
│   ├── 5069d82545c45eaa190d7ed4028b0198efc4ea6c.nq.gz
│   ├── 52aaa1593e523a01f249823c8d7506dea07f43d5.nq.gz
│   ├── 53c2624c7cbee8cca12f11b21936663e629d5451.nq.gz
│   ├── 5797be4bbb53a6235591bf1959b13c7a8d34c4dd.nq.gz
│   ├── 59fc11709f70db20dd169d7983bdec23b84fae16.nq.gz
│   ├── 5ea1e2a3ebab08410d6de9de93918e164dafa6c3.nq.gz
│   ├── 738a8ce448f2cf0cdd448f7ffae0065b6a2fd525.nq.gz
│   ├── 7508d743b555010a0b786aacd211021fb238ad86.nq.gz
│   ├── 82b46457cf425a03f945edd370c1006acfc3836b.nq.gz
│   ├── 85240c9cf6b1e3a275d7b73b4608fbae3adaf82c.nq.gz
│   ├── 8921aec80059cbec580c9dfee55b7f4594c9811a.nq.gz
│   ├── 921f0738833c4c1d3d7657bf2e1918d3cc5a21a5.nq.gz
│   ├── 94ac46c8f8ada6a65e22fb55e18cb5376cd7ad4d.nq.gz
│   ├── 962a6679869ab9539fd3c26631365a7b5803f131.nq.gz
│   ├── 9a9738856c028d359cebe39bcfcac2722aa56f53.nq.gz
│   ├── 9b48351750beeb384140df30b847e337e3f32c55.nq.gz
│   ├── a8c63778926cf91a7efeb861caf1744db938458b.nq.gz
│   ├── a8e639147b7f989a5b1b61bd4d18b643dbbd8655.nq.gz
│   ├── b266585b36cadd5ea9e2eee0f9a2d8fe5c169410.nq.gz
│   ├── b6b1df4f8a19f4940d09cee8b8d08dfbb5aae2ed.nq.gz
│   ├── bbc5eb51a2a3eb89d6998101b9b8ae7413c519dd.nq.gz
│   ├── bf512b6f87d61ae1b2ab3e1c18aadb47d08c5829.nq.gz
│   ├── cd19587b5a15bd38bfd57dc88b55f1af7be65724.nq.gz
│   ├── d7dccc7df737ad1fda766e9196467d803909d1b4.nq.gz
│   ├── dc6685b1fe6a1aa7c2ea5dd4ab7dcda4343b6cd0.nq.gz
│   ├── e041d9612ea4d52692bfc6c6844d8afadacf6e85.nq.gz
│   ├── e6cf9870930f15e662de8b933084330f3b3b4bc6.nq.gz
│   ├── e86f73c91c66c743055e94544021e3d17bd2c361.nq.gz
│   ├── e88d547c4f8dbf92466ad8d58ea326d964e7ab79.nq.gz
│   ├── ee9efc3c88a2741566403e252d59aebf15774cf2.nq.gz
│   ├── f25684f841e9965eede489c0c1fd8ab503d4d124.nq.gz
│   ├── fc0f614614fa5fc45d97288a88cd33f3e188bbe7.nq.gz
│   └── fea110512c1f635c9a44e7b6f9822b5647942a2c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── fd41b56978f009e8c33cb26f384dd0dfaf430a7d.nq.gz
├── filetree
│   └── fd41b56978f009e8c33cb26f384dd0dfaf430a7d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 59 files
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

[snide/wyrm](https://github.com/snide/wyrm)

---
*Parsed on 2026-04-19 by [repolex](https://repolex.ai)*
