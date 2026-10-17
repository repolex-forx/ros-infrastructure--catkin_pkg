# Repolex Knowledge Graph of ros-infrastructure/catkin_pkg

RDF knowledge graph data for [ros-infrastructure/catkin_pkg](https://github.com/ros-infrastructure/catkin_pkg), parsed by [repolex](https://repolex.ai).

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
rlex download ros-infrastructure/catkin_pkg
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── de8b53fad247540f7c3112ff0c4478d847372c54
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── de8b53fad247540f7c3112ff0c4478d847372c54
│           └── chunk-001.nq.gz
├── blob
│   ├── 059db0f7b33e025365f9177e00ea322481dae0bf.nq.gz
│   ├── 0a9df03f9954f591a58c71c045dceeca94a7965a.nq.gz
│   ├── 0be973f6c0162cef89d4c88ea550bbce83a9a713.nq.gz
│   ├── 0f2b656037282d865e5f6306bf6424fdf721a548.nq.gz
│   ├── 11aaf2815c10414912eb51c85f108a1e3555d3f7.nq.gz
│   ├── 12d8ffdc23a30d074ed536925eec1526b0cf1b1e.nq.gz
│   ├── 16d97bb1d41f1e8596194ce747a5c180bf7723a9.nq.gz
│   ├── 1b4e9e833ee000afd6cc8f691d8e9cd1ca9d128d.nq.gz
│   ├── 1f6e2c8c94e71a6a0d9b55a35f34702fa97f714f.nq.gz
│   ├── 22f0b099fc7adf424945d08e6c4c9906ae9d80bf.nq.gz
│   ├── 27b91bc5855f776a7943bdcad0fcb58d0ba7faf8.nq.gz
│   ├── 2843c697cb6b7358db0fee219c00009d174efa01.nq.gz
│   ├── 29e5b76d94d995650fc5ca2d28140d9cd188f515.nq.gz
│   ├── 2c52a196c360b3b98a09fb632b3886125466400f.nq.gz
│   ├── 2c7817f7357b97a46fa8d879a08d0c0f52b43c0f.nq.gz
│   ├── 2ef3944270780280605a58a992b6683152411870.nq.gz
│   ├── 304f45430447713adb23bb40865307e250814cd5.nq.gz
│   ├── 306735c57c5df563675ef8f6809c36e8b62b9305.nq.gz
│   ├── 36b514494cf31ed362859a75ae7540b32732e81f.nq.gz
│   ├── 377bbcb0f0bbf48b30e27203e8313ce3ab33cb6f.nq.gz
│   ├── 3b3e3bcb56d003d47eb51abaaf5716983ddebfac.nq.gz
│   ├── 3cc149302144d4fa1cea512c3b4334fcb65252b1.nq.gz
│   ├── 3cefe4492d9c1c674a0029d3f4871e682321c405.nq.gz
│   ├── 3d277a40b7fa00dbbd4baa009d0f8f1cb23e3337.nq.gz
│   ├── 4729c3ded7827498e17051e50afe6f70fb61906c.nq.gz
│   ├── 4744a1d5f01f6b95f88372d6f592ffef910f1290.nq.gz
│   ├── 479bf6be158d4ef7db5159df8c85a7d8b1f8ef38.nq.gz
│   ├── 54c8f12cc4ab8da8e9d7a375fa250d13838d13e1.nq.gz
│   ├── 58bc9cb2f7417ec925fc713a172d92a18df4109d.nq.gz
│   ├── 613218b2dba8077e301d62bb2b81b7751056e1aa.nq.gz
│   ├── 64a76dfc4b9316d6dbf99f2af53c44502656067a.nq.gz
│   ├── 64d2ab32d28056291d2959499ac71f2672923b4a.nq.gz
│   ├── 673d11eba6535d9055c3afe4a2af6fca0a9210e1.nq.gz
│   ├── 6eb0e19dca2320d42a8d27b348d9ab0edf4765b6.nq.gz
│   ├── 700c4cbf5c6bde997734a6cac656d757a96f7d0f.nq.gz
│   ├── 73e48d474d55e4a9de6748ebd8265130e80a6d5b.nq.gz
│   ├── 75d7175cc2434cb72b4b5c23809c0a1ab0d3e8b2.nq.gz
│   ├── 7664c008fe1157f51784cab9047e6ad674409600.nq.gz
│   ├── 772ad2adf83ff3cff1ed774165643db7dac15443.nq.gz
│   ├── 7855782048b0fc92448216878b4fb92887df0e5e.nq.gz
│   ├── 79ab20b74a472e9938b5ce21003bf3a4be1ef387.nq.gz
│   ├── 7ae51ce4522f6079b596dab98207111041928f18.nq.gz
│   ├── 7caf14e4d2d2a2b72cb3cbe3bf7f8911d3e8cf11.nq.gz
│   ├── 82e58ae3fcfd699adbdd6d5de4d81a0516cc4ea0.nq.gz
│   ├── 837ec13bd92abc1e7d7ed4a746ec42b86c645d4e.nq.gz
│   ├── 84bd64d42bec71e0f5e650958011a7a129d07447.nq.gz
│   ├── 89f93a4bbed3cf3576dbdd4de33757a3dacf8c5a.nq.gz
│   ├── 8c87c0dd38c2517221af6736c69b8053488ea936.nq.gz
│   ├── 900af3cb1a5af6423845729adb97333b9af09813.nq.gz
│   ├── 913b54fc6d29e85507632282028f1eb9a86a457d.nq.gz
│   ├── 92a122f34a8b80e742ebc49ea0c026f3b01983d3.nq.gz
│   ├── 9aa73eaa1797eac3282247fe8fc48d5dc0c62c75.nq.gz
│   ├── a01806b0d1f0a0e0970af808c2de81f5820b5e0d.nq.gz
│   ├── a2530c79978a6a37305abb9fa2cde74e66aa610c.nq.gz
│   ├── a3286ed9737fd8f172a2073d7eb32ac5888c6b80.nq.gz
│   ├── a499174f4a3a28ce0dfb71ac9ddb0513d72dd430.nq.gz
│   ├── a5b49c90ce14cccbf0a9bead47ab0a87a89522bf.nq.gz
│   ├── ac22b2334dd2226cc0f85a3f1f107fb5708d0865.nq.gz
│   ├── b63ca7784cd8e3f6ffd63e10841c0c238303fc8d.nq.gz
│   ├── b9042c50077006f4b7781cca9197d9beaf6c561d.nq.gz
│   ├── b9b003ebb5a284721c26d8b544ec57d87f47160a.nq.gz
│   ├── ba569dc1a4d667569e4c63d8e1ef12e203332d1b.nq.gz
│   ├── bc9cf6757421c0750acb790164c1c6579c15f2e5.nq.gz
│   ├── bcb5d53a101a2ee07b5a7a7f95cfeabaed1073c6.nq.gz
│   ├── c2408266adec86b63a1aef3c49454353dcbfb0bc.nq.gz
│   ├── c7e6094373fcfb66d6f81aba930ab8db0d99131f.nq.gz
│   ├── c7ece77615924d658f934181877fa33eba9af408.nq.gz
│   ├── ced3331fdf3fb028b75bff1ef8d4c766509a11c3.nq.gz
│   ├── cef55a5d50ccf676e84ab39a751c283c6f0afd9c.nq.gz
│   ├── d40302aa6df9fcf91be84f2d5f68ca2b67af7c76.nq.gz
│   ├── d539d2f83a8d838a3def3d7539ad2f37096774d2.nq.gz
│   ├── d5d45ae4728e7c602ffcdacf316a0142a85fe0a0.nq.gz
│   ├── db99a47ec7c7fa18fbed46ba453758f9b5659ec3.nq.gz
│   ├── dddc99510234f629eba0aa026c239a6954216ee9.nq.gz
│   ├── de8e0a5aac826822e6084a9d4a14d1bc6e1fd51a.nq.gz
│   ├── e2fbe9547b6436aa00ba7befee1e350c505120a5.nq.gz
│   ├── e57b1a4b97e274a65aedc8111a5bd226d509d68e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ebdd02ee2bcb0439c24dccfc106670eddaab316e.nq.gz
│   ├── f4b5023ddb5a983e64c1a04272744f759d415ea8.nq.gz
│   ├── f4db133e64f26f6af495811f3f704ef6a60f8ca6.nq.gz
│   ├── f76606fe774a19ec99560257602bb2e58f2357dc.nq.gz
│   ├── f7d204e3a579af9f46decfc6effd5a4166c6bc42.nq.gz
│   ├── f856d93d5fd72ba300d12859bc5ced5feb93f7af.nq.gz
│   ├── f9946e07ba18ab58bf1c3aec80f8040bd2f7561b.nq.gz
│   ├── ffbcb6019f3b691459e346d8b8299900f338d6a6.nq.gz
│   └── ffeb402fa3b3a80d7c4910f1e639f07334ade354.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── de8b53fad247540f7c3112ff0c4478d847372c54.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 95 files
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

[ros-infrastructure/catkin_pkg](https://github.com/ros-infrastructure/catkin_pkg)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
