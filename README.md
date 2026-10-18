# Repolex Knowledge Graph of Pylons/colander

RDF knowledge graph data for [Pylons/colander](https://github.com/Pylons/colander), parsed by [repolex](https://repolex.ai).

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
rlex download Pylons/colander
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4557c017658eb4f6a5dc289078af1a6f850f3f97
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4557c017658eb4f6a5dc289078af1a6f850f3f97
│           └── chunk-001.nq.gz
├── blob
│   ├── 02c7ef50c4831b178e03b98cff13a7ce47758dba.nq.gz
│   ├── 02dfffabba4df7dfc872503bd64c902c24b62859.nq.gz
│   ├── 06efc1fde09cb4650459b4e7d8a2e9d425d58a3a.nq.gz
│   ├── 0a8d474f743ca8b4190ac46c2e0aad46604963b3.nq.gz
│   ├── 0aa6c634fa7a6e0c384aedbd7a543d5ee938d3a0.nq.gz
│   ├── 0c2d36bfc707ccc70c03a01800d1ea9717acecd8.nq.gz
│   ├── 142b6ca357fee89f09803fc9ad7ff676500c37cf.nq.gz
│   ├── 1cdade82f7defaa05705cb52a04fadf1ca21725c.nq.gz
│   ├── 1deaa14245c9d5de8d6e577ba62a4c8af5d09fb0.nq.gz
│   ├── 218fdb215098265bcb749fe4dd223eb4c23d33be.nq.gz
│   ├── 23e65f23b35869c017e453fc28f63c0f3c404a78.nq.gz
│   ├── 2af76c93a392bad7dd5b48467373b30dcd83ddc1.nq.gz
│   ├── 2d163a24ec1fa77718bece5b6cf8f334af0fa0ac.nq.gz
│   ├── 2f4526e2b25b6038a76f94f3e98e23fd7af2774b.nq.gz
│   ├── 309e9be6d801758eb5a5f03056de66bad969f17e.nq.gz
│   ├── 35ddd3de194e185b2c46e160ff714ae2b906667f.nq.gz
│   ├── 3646c4b805faa5f5f4390d48eb3380daaad87e43.nq.gz
│   ├── 3946ef8d37a5770894ff43e3dbdb5d8ab4e587fd.nq.gz
│   ├── 39573e32d6619aaf2c19912a9849703349bdadba.nq.gz
│   ├── 3b6b22032d1737bd9671fb7d6b935ae6b0ae8e49.nq.gz
│   ├── 3e3904ef8c1fda762e6e568d902071c7bc051022.nq.gz
│   ├── 4020f8ff0d6c3e000954fff49ff3233bfdc2bab0.nq.gz
│   ├── 433411e9dc3a9256ffdd653bc73c2cec47bbc36f.nq.gz
│   ├── 43b24a987d1b4ff5831891eb3879e8d530d74585.nq.gz
│   ├── 45000ce770940b76168ccb4b00861c2b52d76691.nq.gz
│   ├── 4f025aef60d6aa527befafd7a47b073f80a16093.nq.gz
│   ├── 52d237a939a96e7a76e624a87d3f20bc4ef2bf2d.nq.gz
│   ├── 538ac9758c21ba1cfd6fe4d66f0ce385b05a314d.nq.gz
│   ├── 563eae9bda64794618b559ed619894521a1afd0a.nq.gz
│   ├── 5737055179c779b424f85fe92776d847c5e82905.nq.gz
│   ├── 5ced96e3b5d11a635acdcf19c4919fb3d70bdf9f.nq.gz
│   ├── 5f87d494fc33e78bea15a1403d97e14148200055.nq.gz
│   ├── 621aa8f509eeaa6cdaa536f0926e39af428eac94.nq.gz
│   ├── 6c3691a67067bd1486395a2422325b15f657d02b.nq.gz
│   ├── 717025d94134ff61de824e5316159b10b7edcfd0.nq.gz
│   ├── 738f755d684ee6f12789bb0f4fcd4ff2bda6efaa.nq.gz
│   ├── 74010c0c96c0b07aa431c13d4d6db3378912c1b4.nq.gz
│   ├── 76d521bd3bc73d4603864fcb9f12d4845ce5c5f7.nq.gz
│   ├── 7dba93a02e309b5ce090f7722dc12d6ce0be7ce9.nq.gz
│   ├── 7f1054e44cfdbdf3c5d82cf625e6eb1058833916.nq.gz
│   ├── 7f24842108748e91f82413a24da66e3273263d04.nq.gz
│   ├── 85208681f11a642e976a9b15a92a114c4d46a1ed.nq.gz
│   ├── 8bdf326b0eb2a8fa597003b821004064670036e4.nq.gz
│   ├── 9439cd40df5f8d0f0defdb827fba1fccb2d1cee9.nq.gz
│   ├── 95e1f0b9233765e0c2bb9573c655bf50d8bbe7df.nq.gz
│   ├── 99695219dfd5bafe342d8108cee6177e8f511bf7.nq.gz
│   ├── 9c9f06a366d3b2635e927ab3cc2fc73d9fea8d8f.nq.gz
│   ├── 9cd19e91a5033cae829e943fa687eda769bb5150.nq.gz
│   ├── a0e1fe3c04538ed441d4a5b98a16dd7cf72a96f2.nq.gz
│   ├── a21f36ce85b7bcf48e72d21c6535db8094817407.nq.gz
│   ├── a4ce87ca06d3249a90d0b4a085b20295286cc7af.nq.gz
│   ├── ab4592b5dae5f71375a270199f182bc912b17f91.nq.gz
│   ├── ac855296fd3ba6139763e0768674fbf37174ad27.nq.gz
│   ├── b8a5524f9d4ebc957091acf9c80c0f3ae34bd7f9.nq.gz
│   ├── bb381fc539bf51f49a755277508637223b538f4e.nq.gz
│   ├── bda52d26e6f6110d8e1f0f2b2f98195cbad2c0a7.nq.gz
│   ├── c03d845762f1ccc8a0a4194f56c9d8955a8bc2f5.nq.gz
│   ├── c5c62c89398e47de7d89b21faebb31b315fef747.nq.gz
│   ├── c782cb9fb69b75300e48b0ec486e23f41698cafa.nq.gz
│   ├── c8fffea0c02ff1a2f0783758fbdb6b25381946bc.nq.gz
│   ├── ce30bb66a1b02c3bb0c1ad5418d5d1731ad5af5b.nq.gz
│   ├── d14e33f78f6117a7aa9f3b88bbdaf3a9ab7ba724.nq.gz
│   ├── d7a8a12acf46c78eabb65ab702bd086d3c7642e0.nq.gz
│   ├── db7dd694ae630b013d62203eda96897590598ce7.nq.gz
│   ├── df21a06b1d4a77f63e23a87946a71b8540694a82.nq.gz
│   ├── e35d8850c9688b1ce82711694692cc574a799396.nq.gz
│   ├── ebf98fa31878bf57e73e2b73a5963e31937ca220.nq.gz
│   ├── f0f7a182644d82e7338d336f5e93837de6e1b521.nq.gz
│   ├── f1e907243d8dca30bd69e70a6e12e4d8ddb50f90.nq.gz
│   ├── f21a506a82ba04c4dd8d401c5921d978dcba7c6c.nq.gz
│   ├── f33b1b0b44cd5b6d730475aa6a9dc108ff6b7174.nq.gz
│   ├── f81159cb238340e6db09e415f9bc8d55c9a845a7.nq.gz
│   ├── fac1e18eba9c7544e4292954075415fb160569bc.nq.gz
│   ├── fbe0be81c15111901bf85de4a9641f1423dd7cf5.nq.gz
│   └── ff46376fb2941256ee54cca01f97a4501d9ef3ab.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4557c017658eb4f6a5dc289078af1a6f850f3f97.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 83 files
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

[Pylons/colander](https://github.com/Pylons/colander)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
