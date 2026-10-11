# Repolex Knowledge Graph of pytest-dev/pytest-bdd

RDF knowledge graph data for [pytest-dev/pytest-bdd](https://github.com/pytest-dev/pytest-bdd), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/pytest-bdd
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0e04014fd56b325d702b6926d5dc9a8705636c2c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0e04014fd56b325d702b6926d5dc9a8705636c2c
│           └── chunk-001.nq.gz
├── blob
│   ├── 03ef2dcf64d250081bc5ec055bcb494940675948.nq.gz
│   ├── 086c42fb2dd378f77145aa4e1572c674c46b0915.nq.gz
│   ├── 08f4584bad244afb78f72109b7658a05d2cc3cbe.nq.gz
│   ├── 0994c36ffdbe7dc5cc7054a4f316f7f800063781.nq.gz
│   ├── 09be7c853899c5b559146997130cde91cd3ba976.nq.gz
│   ├── 110ce307eaf5e4fb2af2910f2326325d3b104d54.nq.gz
│   ├── 153f13b7b339308c9c73221011a96e897a84406b.nq.gz
│   ├── 15b74558aeb8f3ebca7ef65ffd780804c7faef81.nq.gz
│   ├── 16fb813b07f891c36988bdb7f6ac473b454a494d.nq.gz
│   ├── 1706868e9e03123961f9a72577ae148a4d3bfd79.nq.gz
│   ├── 184e75bc0ce94d62c2d1037605d75a959f4b2644.nq.gz
│   ├── 1ad2a735185aae663fb322297f0d26ce587d4838.nq.gz
│   ├── 1b150a229935ea6773d7f5d1bfba55fd452f7f59.nq.gz
│   ├── 22ddfc636d8e0176eb37a939f29022d66ad22c9b.nq.gz
│   ├── 26b348dd086582deac21abf20843fc833bb7ac4e.nq.gz
│   ├── 273f7f4971cd580a0f0ebfbbcf4a067a90d6b9bb.nq.gz
│   ├── 2fb3813e39f5356f83894300cc7a1ea227496376.nq.gz
│   ├── 308cad0fd3563746ea6dd7527a7a94946046c46f.nq.gz
│   ├── 38a02ddde41868824dbae187afe77e9c7e4ca332.nq.gz
│   ├── 3e6d8dbe39ea89524b8da3b149e453f2406342b3.nq.gz
│   ├── 3ea5b8f8be19823bf168f0982478c99d36d3af70.nq.gz
│   ├── 48e1cedbcdf802e3a228296428569e964283390c.nq.gz
│   ├── 49dcc472c8aced09a010df54ee3dedf1c287205c.nq.gz
│   ├── 4c1b51a34ff4ef29a94cbbf48806974b2a111804.nq.gz
│   ├── 50c7211a198446142395f75a76fa9aeef3913316.nq.gz
│   ├── 514b554f07168993b44971a66d3b6d83396139ed.nq.gz
│   ├── 5515bcb14686ba400ad7be7e0cb41d4e7e5d8a12.nq.gz
│   ├── 562575b3368d7c10b2dbfe1e876a6a276b004a1f.nq.gz
│   ├── 5bb3d2a02ca75c2097d10477ccc9daa4742f817f.nq.gz
│   ├── 5d21c814dac4e5ea02b711756fa4022f64cbd154.nq.gz
│   ├── 64b87257c70f055aff35fa5944779527afd128a7.nq.gz
│   ├── 69395c51d1cc10823e5824cd235568d25c39e68a.nq.gz
│   ├── 6dcfad946788c4aed8708e23e10f3ea98f3ddea2.nq.gz
│   ├── 768d2eda108fd061a00316ab9f021aa14507d084.nq.gz
│   ├── 7a229b1921af9236cc79e1bc1e94ee2a41d31404.nq.gz
│   ├── 7ddc368033392db563040e83ac6c5b3704434baa.nq.gz
│   ├── 7e5e7cb11f86a12579245f6c89de28339c1df2a7.nq.gz
│   ├── 811392e65a4a980c719e7239eb66992b34fb5495.nq.gz
│   ├── 86428bb87bd722e940a9556ac997d9d4f14a6c8a.nq.gz
│   ├── 898ea8dc081e322bb7b7330ace5413466a87b934.nq.gz
│   ├── 901a02291298322b7827854a948a4c305a51ebcd.nq.gz
│   ├── 904cd05d139db59bd3b821beecc0078a5848c449.nq.gz
│   ├── 93a726bc77a331c72dd8283ee8a5770f7aeae1ba.nq.gz
│   ├── 9591162d1d9ea3fdf92e0bfa02dca6e079a83c64.nq.gz
│   ├── 97e015f0283dae401c87756f2a3e27ce4fe54008.nq.gz
│   ├── 9b7f04a4b2f40670611f92a99b2c1afaade20bfb.nq.gz
│   ├── 9f7901539172f2a0960d7ba672ea71002ac4bac7.nq.gz
│   ├── a20fedf14cd3c50803790b6b347579d42bd58b94.nq.gz
│   ├── a5c56938c2596aeae712f1867d5a839e84bc1bf8.nq.gz
│   ├── b02c125b7486c3ae683b50f3054b13c8fc729e28.nq.gz
│   ├── b329d88d253f5d71407d09a3ed40fa2a421f4f1f.nq.gz
│   ├── b38fb93d60c39b2412f8662918442b6659af19af.nq.gz
│   ├── b46a8221dfd803420a6a1fece5b3888d2657d8e1.nq.gz
│   ├── b933b6483d5ee30a8c58703c1faa9dc6ad0c93db.nq.gz
│   ├── ba407bc6b575ff023fba16c27bab86fd5de8f91a.nq.gz
│   ├── bbcbbe7d61558adde3cbfd0c7a63a67c27ed6d30.nq.gz
│   ├── bd092f510c1816330b7fd75cffd0e1cbe938700d.nq.gz
│   ├── bd4ea9a8326cc4e96e4f57deb02f8f1f0018a4d2.nq.gz
│   ├── c07b782b0d84b479ef8f408e20f7257aa3e438f1.nq.gz
│   ├── cad940ac00c261954ea794fce566df58fa478210.nq.gz
│   ├── d0aaa1ef54febd9cccc7b559b79a172d4989bb54.nq.gz
│   ├── d19163f1a178892fdf8c18af3beaf72c7837852f.nq.gz
│   ├── d1ad12002fe3049d1765bf53527104ed7e79607a.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d7b3a1b7b0c81d468b55adbfcc102485a9de9a4c.nq.gz
│   ├── dd09d1b6faf231a3fce59585a6f0c2f70b5057d8.nq.gz
│   ├── dedfd5bff90dc0af30ba71131d4cccd5380899e7.nq.gz
│   ├── e2c381c3aee36e7e02181161ab87e2e1cdaa3b94.nq.gz
│   ├── e31937e4a4384f9d1e3cc55ee47f582b7e00030f.nq.gz
│   ├── e4ff553f4c4206fc8bfd6be1c0b599c5643fcb32.nq.gz
│   ├── e55e0b899cc0c0c9b821b56002c03da30a044b9a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea99250fe6da1a67ccd9259815c2b1a2d65006d3.nq.gz
│   ├── f3af990005e26f8c2f3367a0fb55d970fce874a7.nq.gz
│   ├── f5915f0d38cbdd9518fcc250b5cb2c8e1134d883.nq.gz
│   ├── f7f5257ed8e17e9bed651955f50d9b7100bb0b52.nq.gz
│   ├── fdc86c9ad8011d2978836474b68b58d7b95fc49f.nq.gz
│   └── fe4c0b95adfd14e899fc3165e6b79016293a73f1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0e04014fd56b325d702b6926d5dc9a8705636c2c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[pytest-dev/pytest-bdd](https://github.com/pytest-dev/pytest-bdd)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
