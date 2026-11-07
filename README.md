# Repolex Knowledge Graph of ansible-collections/community.cip

RDF knowledge graph data for [ansible-collections/community.cip](https://github.com/ansible-collections/community.cip), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.cip
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c90a6a679e230228fd301e4414f40f57ba966774
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c90a6a679e230228fd301e4414f40f57ba966774
│           └── chunk-001.nq.gz
├── blob
│   ├── 06214abae7fe8320d072c57d7e188e01b1de66e0.nq.gz
│   ├── 0f5dc71a8b250c6ee6a3b1d52b8a59efefd35cb8.nq.gz
│   ├── 177e9c63d4d12578ce379ba1ffabc568ba904a00.nq.gz
│   ├── 1f0938ee8b293ed26a091781061d521d3659d28a.nq.gz
│   ├── 203a0cfef80a08c40224f16b2f8da359e9448295.nq.gz
│   ├── 22b5e063223795c91b5ec175b7e20ffb97dbfe8c.nq.gz
│   ├── 234e0bebe396963dc01375644fb65038e384dfb4.nq.gz
│   ├── 23d324264b94ed0a5acde7f9fcc7ae50467667d5.nq.gz
│   ├── 2d4b425459836acf9368e7979db804df70197681.nq.gz
│   ├── 38c76ecd205ba788b77c18f6df33143cd24f0215.nq.gz
│   ├── 3b6e1105a47cf592b6632b5a327df6c90532b645.nq.gz
│   ├── 44d9c950573d8dcc29e4918a83734b5b18db2edb.nq.gz
│   ├── 47371f7ab8210ddecca85a7bd400512ebf272b81.nq.gz
│   ├── 4da34b7b870c3bab945642cfd4c10a0c201560ce.nq.gz
│   ├── 4f7584ce7f00ae7e127b937c5a7f45c9af6536cd.nq.gz
│   ├── 5aa14625e00258eb659751d4c0f1943ad202e3db.nq.gz
│   ├── 5baf20715c49e0a47c80b1f92706c99d1f3a9bea.nq.gz
│   ├── 5bbd8c0437fe9962ce5737fe5829537ac74425a1.nq.gz
│   ├── 5f04fc8ce9819b2ced0b05b8cbfdb4fee8ae0b81.nq.gz
│   ├── 6db86e4ad3bcdd9a0227b5906084d20bd87a2cdd.nq.gz
│   ├── 7096926105cecb4e9287f3bf6a463191ab2adc27.nq.gz
│   ├── 72923e7198985b7d7fb845747df29298a01e8a51.nq.gz
│   ├── 7639b99fcb43040f44d7015f8a414db392ef36f8.nq.gz
│   ├── 775d977492551715358c05b213d81b5b5d14466e.nq.gz
│   ├── 77e25783046f219692c73b44e2c10e78e425c139.nq.gz
│   ├── 78499d5b11d9cb62a46a27133111d22b35efb01e.nq.gz
│   ├── 7c6c193970f7e3c135b947b803c294b1c716bf41.nq.gz
│   ├── 7ed0dcf76081628dfebd23b4642bec10050dc9f1.nq.gz
│   ├── 81f6e183e0ecd9d211b6d35503f15977a0b04c34.nq.gz
│   ├── 8748771436e55bc8c5dae7617766024943173b41.nq.gz
│   ├── 96ee6f175a09056a68c0d343cb86f954cd63be0f.nq.gz
│   ├── 9b624e0b84008cf0e4f26c1c1da3e8714f443ece.nq.gz
│   ├── 9bfa05d82dd9343566dc175b0fd32e442e945289.nq.gz
│   ├── 9c2e9855e625b0baddb5684d0777a62d65304802.nq.gz
│   ├── a7c50faeb9645230419d2e8bb5a78ec7ada5c8e0.nq.gz
│   ├── a8043298b9114fe12b2da8568b5d389883b63e41.nq.gz
│   ├── a9223cc6097d0a95ae04d96c9dd06b37ea554d12.nq.gz
│   ├── aa0e54ce3893dc2b50ecb2b4ff0b2b381c6c8e24.nq.gz
│   ├── ac7ee2d0b4856d3fd74a7b89c96f123865f743fd.nq.gz
│   ├── b319b68948ba73a51e43b8233e95d27f912467ec.nq.gz
│   ├── b83c843827ae9021458d0aa816d313410a0cffc9.nq.gz
│   ├── b91c14d7c5e0b38a354acf9619db58e797f015ee.nq.gz
│   ├── bcf7a771a40dfc41ad41a2395b9782351a75f5f8.nq.gz
│   ├── be386ba859719391063de3e23b0fc42a9396d684.nq.gz
│   ├── c09a66b900bc6c7291aa97bc7d8532cdc0d4de2d.nq.gz
│   ├── cb3a12e19cad9faae1c91000525a5ecf029ee922.nq.gz
│   ├── cbb874440e50d0e4a502c2d75749c6d3ec06ad7c.nq.gz
│   ├── d30f6aa45d3305f0c75967c596075d8e83dd80cd.nq.gz
│   ├── dd7bf09cc36d3b994bcd3b1c4705d152d9c0562c.nq.gz
│   ├── e4dd6a095066ca4ff4c52a5690e7f2dd7bc08d34.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eef19e50778d409c719a08180b0be9a6cb15bf3e.nq.gz
│   ├── f7165f06de17c6411b805048375829669868d00f.nq.gz
│   ├── f9992fabb2d7155fd39362af070d5e868c34696a.nq.gz
│   ├── faff92e33f5d886d986aee367b7fbddd4fb3909a.nq.gz
│   ├── fb538271b8494d9233811b19d7b42073f20af647.nq.gz
│   ├── fbc9011bd673037b320e0b5fe2dc2576169d9c0b.nq.gz
│   ├── fde0a9b9b285da8a537b07a016658f2a4bda11c6.nq.gz
│   └── fe461b4243c04e5439aa1643853b3296e4a1ded4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c90a6a679e230228fd301e4414f40f57ba966774.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 67 files
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

[ansible-collections/community.cip](https://github.com/ansible-collections/community.cip)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
