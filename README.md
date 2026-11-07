# Repolex Knowledge Graph of kivy/buildozer

RDF knowledge graph data for [kivy/buildozer](https://github.com/kivy/buildozer), parsed by [repolex](https://repolex.ai).

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
rlex download kivy/buildozer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 76bac28545c66bbcc671d49aca553a747d69608e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 76bac28545c66bbcc671d49aca553a747d69608e
│           └── chunk-001.nq.gz
├── blob
│   ├── 00151d588d7cc7270d6423c5452ebec7753f7c92.nq.gz
│   ├── 025d5b0834bd48f40bd34313805cf4858fa72700.nq.gz
│   ├── 0ad12aac96496457a8c16c605c15a866e5d2d07b.nq.gz
│   ├── 0b2b7b20024f899c86ae547c32c67a6e7c296b62.nq.gz
│   ├── 0cd7a9fbaa4956e575c330e34377e7517e0526fe.nq.gz
│   ├── 0d57ec67d02f98a09d038a675233ec1401abec93.nq.gz
│   ├── 116cefe4cf630bd17c46953c659fb525585e5524.nq.gz
│   ├── 16dafa0c767bcc3b66d6e89466e82b93ac71bba7.nq.gz
│   ├── 176977fbff271d022460d57c1edb0232814cea0f.nq.gz
│   ├── 19ea037d006a57ab72245a8ee68a8e7e0dc81846.nq.gz
│   ├── 2252057b84b7ad08c5c068d616e6a41704058db5.nq.gz
│   ├── 2338387ee5a04437b6eb995ddac10a6eca5298d3.nq.gz
│   ├── 277af4df02768919c3963f3c4f9b4fccfb9caa6b.nq.gz
│   ├── 29a28f57d2d609a74f884d4070f25c09b33aa2aa.nq.gz
│   ├── 29d18faa24b01a0961febdbc549acede3d161a63.nq.gz
│   ├── 33edbdc59fd0133cbed18a2d75e837b624768714.nq.gz
│   ├── 343d344560702186d10a8e8519aa552cf6b4ef48.nq.gz
│   ├── 3497fb4340a3f463317d1d336eafb34aaa25fe49.nq.gz
│   ├── 3515184aa2d0eca324083bdb94ebb225a2491d71.nq.gz
│   ├── 3599620552a264401d291c73789caadf9412125c.nq.gz
│   ├── 363ab59f1f146c7fcf8d7cbc2059cfabdacc683d.nq.gz
│   ├── 383c38e18f9a11d627f1c1c8722f647ac621153c.nq.gz
│   ├── 38fe41524de6cea8289975e5ed949571cdb812bc.nq.gz
│   ├── 3a75d55b6e2d1ce8afbd9ee2943cb1fc16484c09.nq.gz
│   ├── 429189ce050d3642ba1ba7475d19d51087371ec0.nq.gz
│   ├── 43f7456fd9ad64934efa64585d8f7377b032f25c.nq.gz
│   ├── 477285adc337dfd62538d0ba9ee93a8a76530fc5.nq.gz
│   ├── 4bbaa56966c238ba9ef792941efafac1877a8213.nq.gz
│   ├── 4d8b5bb193b0dd9985d9218515aad3068567fc46.nq.gz
│   ├── 4e9814d60c66714704b7bc1494b70c57b33a3fd7.nq.gz
│   ├── 4eddf2f1c9fe3de7d004dd7a4bde42b79ce6aa7d.nq.gz
│   ├── 50ce28ed82d072597332141617d9fc8a2d06b762.nq.gz
│   ├── 562e2e3afd01912ddd2e26c7ef474565aac18311.nq.gz
│   ├── 5705022ebe779f96e84f646d73f85d966ce63460.nq.gz
│   ├── 62068cd293f38154def4db68294f076fb7c6fde5.nq.gz
│   ├── 62b20d7fda31fd5432e7455517a071b64385d7ac.nq.gz
│   ├── 6598f20a7f52635cc61b900a7afd3e2ec38f2731.nq.gz
│   ├── 665086481d658f12eb5cf505f624cf48db4eec38.nq.gz
│   ├── 693682062b0b4316e234660edd2d2baf1991c245.nq.gz
│   ├── 6ab02adf8a27b89d9731dc6eb2e3b28113b10bd7.nq.gz
│   ├── 7260898aa20ddb3d5f0a665ee1651471bceed54b.nq.gz
│   ├── 7b477f698b4371432cf023257a08bed34ab23fb7.nq.gz
│   ├── 7e7f5982d364dd9909202eb8bb4826d1a929a773.nq.gz
│   ├── 8380fa2a88d52619a93383884243c7c42ead5b8c.nq.gz
│   ├── 8804092401bd7d335cb9a9eac5b330d1ab08933f.nq.gz
│   ├── 885f6fcf3ccbb62ea4a1be10bdeeff1d471c4c73.nq.gz
│   ├── 88e77d82237e6ec3643e0c1ec5ae9f346d19d4ed.nq.gz
│   ├── 8ae8b96fa172d2f0eee6ea25ce400677d8b04db4.nq.gz
│   ├── 8ea35d375239c3010aab738cb1067f857daa09a9.nq.gz
│   ├── 98fe5fff3e2c4dec6ea63c48fee87623042a6e4f.nq.gz
│   ├── 99a5be6225e7c09680c09fcb85b8d6adff9b3ee1.nq.gz
│   ├── a1da8bbd01e00bbb14e37881dee5a2854806b730.nq.gz
│   ├── a39701ac455a0a99fc03dc3b2a8af79eec7345a2.nq.gz
│   ├── a3fe17e75a3b93e16ab363199174a29e60043764.nq.gz
│   ├── a5669e9d7da54378871e5065c09747ff0663c3f3.nq.gz
│   ├── ac420c92e059e58ed45e474f75503f4c08c1bb8e.nq.gz
│   ├── acd4fe55fbee6f72794b0507308c82018cc2290e.nq.gz
│   ├── ae2f37283058b16fec3cc0ab33026fa026520ef4.nq.gz
│   ├── b06fd931549b70213557e126e7039d21bd3b8f53.nq.gz
│   ├── b37c33fcd981e3b06f01575712ecc97909f422ac.nq.gz
│   ├── b66c6222ca07b3bdcf811b07aea75d1497b72fc0.nq.gz
│   ├── b913f2e2f273b6cde78cfe981493e490f5197bbf.nq.gz
│   ├── ba20f72752ac5e1388480a4154876db7694a84ea.nq.gz
│   ├── bcf30d80fa42a174ee2b992427951b698c32cfda.nq.gz
│   ├── be04e3778c41facf272b8147c85d1575e65e4f9f.nq.gz
│   ├── bf94abae2af4ee5f94f3e4e00d8b54bdacbb1694.nq.gz
│   ├── d0cc1246cb5ea28b995d1326fe08cd085e630289.nq.gz
│   ├── d3048fcb858666c5276196b2204c204d68a46995.nq.gz
│   ├── d46865493164fee9b77e7e22277cc75b821a0d59.nq.gz
│   ├── d5d6b13c8523290257544a9fc3b75abf911b367d.nq.gz
│   ├── dcdd7404fe018f763c139f2cd2ded92b61a34dd4.nq.gz
│   ├── dd41c4fc8be0158cf05224026836f09366a23081.nq.gz
│   ├── e0ace4a95e9ac0bcf51a27a12de15468950b70f9.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb7f2b9b1987b499db5439402c1f0cc957b760c2.nq.gz
│   ├── f081a705c259f23d6c902ef672aea035afcc060a.nq.gz
│   └── f5406671ab7c2b106b09f59d26ccb60c0868f66f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 76bac28545c66bbcc671d49aca553a747d69608e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 85 files
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

[kivy/buildozer](https://github.com/kivy/buildozer)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
