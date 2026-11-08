# Repolex Knowledge Graph of UKPLab/acl2025-con-instruction

RDF knowledge graph data for [UKPLab/acl2025-con-instruction](https://github.com/UKPLab/acl2025-con-instruction), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/acl2025-con-instruction
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 43124193a652b583c03a2123c74459177a1c5dba
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 43124193a652b583c03a2123c74459177a1c5dba
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c56867dd1fd88094df9556f3d1c57e71a7ada8.nq.gz
│   ├── 02e5237ece031af23fcd76b5b4e0d9b0bc5f55cc.nq.gz
│   ├── 06160f2422b5368f30fb967f7cae635208a1dc69.nq.gz
│   ├── 069d0d1c10da42f5d278598e8534f166d1f9f5ff.nq.gz
│   ├── 0d03bf268c448d14aeb9becbc045bcde4ae6c9b7.nq.gz
│   ├── 0d39a67c24f01c1af1e9cb675f380c3a1d1b2422.nq.gz
│   ├── 0d9360dc35d158ea1ccd025d9520994762579eec.nq.gz
│   ├── 0def682ea3c497e36aa85f1c53eb2cfab6e2fb87.nq.gz
│   ├── 0f796a3880341739677a5fe3bfbcc90515a0f324.nq.gz
│   ├── 10208996d0a0b069bc4e4e90124185bf733d42c5.nq.gz
│   ├── 120c6893b8af8f69dddc51b2734ed561b78c6091.nq.gz
│   ├── 18134a0ee512a1db7667888eb18a841396eadb42.nq.gz
│   ├── 1e324210e229eeba23b75791bba82df7c6e639eb.nq.gz
│   ├── 20f167f65c6edd89723dc59e2d63af3a22dbbaa5.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 23a59bf4ee0f365de9fbf3838836b170058126d6.nq.gz
│   ├── 24b0fffcc11a2045dfc7f5ac6cae4f057aaba6d6.nq.gz
│   ├── 2563f89c6cedf5e73508afec8f9979105df9b745.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 266bcd644e5fde3523eb38efe468caee0cdbf32e.nq.gz
│   ├── 29ea06170f23a845627c7e3dd52d3a5bdb379767.nq.gz
│   ├── 2c2c40295e0351f25709ba25554c9329f15bf0d2.nq.gz
│   ├── 2ccfc926ca2615796fd0822d0bc2e140a38aa1f7.nq.gz
│   ├── 2dc2a8fa00f487a8b3db7731a440640af682db3d.nq.gz
│   ├── 2e022183196245a9e08210f1c35be158a7363be5.nq.gz
│   ├── 2e254da152ac644ff54fb5fa57e625d9e6ba31d1.nq.gz
│   ├── 2f061838c11d27e165143aa093861ec210d02f8d.nq.gz
│   ├── 31cd4f48e6055cd6d00a162af30b1c8139e26b57.nq.gz
│   ├── 31db2eff8d1c4b3ae645583dfc5e156e818b6f1c.nq.gz
│   ├── 374be090510b302de9882d880c755787a8eafe11.nq.gz
│   ├── 3bee468d34515fdcbef1a8b8803c9fc4f7dc0b34.nq.gz
│   ├── 3c9b49565c629bc20894b06941d9a25899761628.nq.gz
│   ├── 3dc429a6613bf85898a47643fe31d4439fe9d973.nq.gz
│   ├── 4003b3efdaaf1b47494a98c42e67ff429515345a.nq.gz
│   ├── 4006cf917e26c365080b0844c56fab78c48457c0.nq.gz
│   ├── 45c94f6d8e39f3b7ace728febbb20e6294eff290.nq.gz
│   ├── 468f4bb120448a036bd5b5c7955464fe2e13892a.nq.gz
│   ├── 477c668b62a30da69a6efc630c736fe319970bae.nq.gz
│   ├── 486da442765c7ccd33d9f7e11c14d27a9179b406.nq.gz
│   ├── 497a702ab5efb88b8f67333eae81645eecea78cd.nq.gz
│   ├── 4ae55d59c2c8bab80299272314a41bbeb959d8ed.nq.gz
│   ├── 4b71e3d5618a262e4746f58e5d10947b73370dca.nq.gz
│   ├── 4cef27e61ea9ac6f982e68a89dcb12432298bb71.nq.gz
│   ├── 4d1f016db1028101d45ba7d68cb3f0bcb558c2bb.nq.gz
│   ├── 51e7d4858be581e6a4e24380b0189024625ca5f4.nq.gz
│   ├── 5388fd6f650c5f44207c85a8a4a9b3fc0abc7cdd.nq.gz
│   ├── 564eaa5ab3b2ee01a63c7c4a5ea8852a1e952aad.nq.gz
│   ├── 5acbeddaa246a1e85868f1cc07a4045b35fabb94.nq.gz
│   ├── 5b32cb501799175e3829f92b014795ad1cbee79d.nq.gz
│   ├── 5d25dc7e31f90f947d11c76f6906bcba1265ec83.nq.gz
│   ├── 638b078837f175039b2db49a63821288d9681daa.nq.gz
│   ├── 65e8f8ccb245c2f2e2bcf921fb79ac9cdd819346.nq.gz
│   ├── 6615d329884861b4f3ae9c5646c835b2448fb8d9.nq.gz
│   ├── 666dd9691bde7d54ddf2871e311d6f621e29f099.nq.gz
│   ├── 667c715caf80ff43b82a749a6c2ff587f0e22473.nq.gz
│   ├── 68eb69b23434984ce6053d307b6b6b7f709a7e7e.nq.gz
│   ├── 698546e995d365d1ccc2c25a87e6c5cd681e6eb6.nq.gz
│   ├── 698e9f972a96948e15606d89ceda254e571d2692.nq.gz
│   ├── 6a171a558f6a2db926e56026b27c8a2cc3de9a48.nq.gz
│   ├── 6b090faed0e630b03b2294545050f1f4f5032cad.nq.gz
│   ├── 6f44ebaba1aa493b8bab3baa4e827b76752b1869.nq.gz
│   ├── 7217e5dc1bb683453204a20890f01f5806ce12cf.nq.gz
│   ├── 738e17472714295673e65675d5cc944f834c1a4c.nq.gz
│   ├── 7b6d6fc69b336c0a5d103be9fb13a0e0897c76a3.nq.gz
│   ├── 7ecc6ac770a62294c02eccbb272ff361816bfd43.nq.gz
│   ├── 80f9dedb22582266a9daa4b5a74a2b7ef60f99a4.nq.gz
│   ├── 8147382a3152de03c24b4cd91f9870ced1a95d54.nq.gz
│   ├── 827507004097c4358241b61734d2425840cb7829.nq.gz
│   ├── 829cafe545fbc5b6a622128620b975639019a6ef.nq.gz
│   ├── 83f482b28c84d4ff9dc9e57ad2a190f0e2e9d37c.nq.gz
│   ├── 8a32ee34b1603953ed79a91dec01453f67fb93c4.nq.gz
│   ├── 8af4559c65fc2728b11fd2097a109981ee1ef686.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8eba06a74ae5a4c6cc4622e0e943b2c0b209f4c7.nq.gz
│   ├── 90fc681a20ee72131862772107f6be572f010c99.nq.gz
│   ├── 911c6bd6967774bbd6150cab86b02ff101c5ad51.nq.gz
│   ├── 9144329893c51f402ff2e2f65d9fb7baf177bd52.nq.gz
│   ├── 92602258ccd953a1d7137056aaf15c8de8166e21.nq.gz
│   ├── 938706438b1d332505fdd0e9670df72c31eee1b2.nq.gz
│   ├── 94a0ec8b1b1e4226fa0f4bd9e853902fff7f6769.nq.gz
│   ├── 9b3703a912d40f58fb0fb57d20742e53d9fe7671.nq.gz
│   ├── 9ccc7363dcc9155dec920e64a9820737d3fff0e3.nq.gz
│   ├── a3297b7c295abddedfaac7f6fbe882d7b672487d.nq.gz
│   ├── b115b8f2327ea9d972f9e41bcbb03c68be6b3508.nq.gz
│   ├── b2b19059e140ab1b6a4aada7e952c43430b5c710.nq.gz
│   ├── b977d285abcfcff0a3fe5bbe638b5d0cd55c291f.nq.gz
│   ├── bab427fa2247421401425f45478abfff855812a9.nq.gz
│   ├── babab6e12b4bb8cfa74a7edfa5e56cd1b3e2bf6c.nq.gz
│   ├── bc425a167f3e75d5ad30366a36980eeae1a5f55a.nq.gz
│   ├── bd1cf37edf2e845604047e92cdb3294ee6c2d4a9.nq.gz
│   ├── bd7a4c8085ddb7b237b17b054e5eaa0569018178.nq.gz
│   ├── bf2baf1682420e2394d551f31d11e85cd283889e.nq.gz
│   ├── c07efc122950da37455608b609dcf1f2b4103d56.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c0f3b6532f2509f2bb8de0c0e512a0ec4a3f6e41.nq.gz
│   ├── c1f0e1881e9ce25f65a5789cf141641f59367a02.nq.gz
│   ├── c2ff17c915481fb556aba6ec816a9e08f519c515.nq.gz
│   ├── c6181a9342e85e0745d701da068b8e0d3ef8c41e.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── c676ed5592bbc8a9c5a58e063f6a7584582d68bb.nq.gz
│   ├── cc98b6933cd0df2705fd39225f24282258cd3685.nq.gz
│   ├── ccf206bbd7a5d6376eef82d61b3ef8bbe0f71c6c.nq.gz
│   ├── ce2853a41a1d232ff823bdd3afeb4823132b6672.nq.gz
│   ├── d0cb9fd8eecb3620b653f0940c0b4921dce9dfc6.nq.gz
│   ├── d0e1d115446a4c27e8636b3aa1f7907b05747a32.nq.gz
│   ├── d18e260d1ac75b909a5fd02f00b490ad84cfba31.nq.gz
│   ├── d435b7d835bdfb2934e32a93f1e8eaab39420ad9.nq.gz
│   ├── d4bf1b4c47ccdb1401b18f8397868ec016d1c43a.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── d6e407a400a67020d801e6c27a3c32a2ee38f30c.nq.gz
│   ├── dbd91789f0cde61dd13a7f9a5f7a69488ad07279.nq.gz
│   ├── dde17ac636d38e406f4ebc67ccff83714a9260cc.nq.gz
│   ├── de97345cf424fe72cc90de30f42d127ff20b99ef.nq.gz
│   ├── e30e958da061a4f0a0bfe34b12d2fcaeba7ff2f4.nq.gz
│   ├── e3d50829fb0fdc705f8792b42535461fd7140c5b.nq.gz
│   ├── e5fb37cfdc64e4a03828bc0adbc605f1e030579d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7883dc886b96d078883e01aefd16792133e204a.nq.gz
│   ├── e89507c49df413945453959d48b51a71b9031ef7.nq.gz
│   ├── ed3a9d377ba3c30e6eb8b2a35e08e8dc814a0725.nq.gz
│   ├── f47c06cc18baa434989aa2d46756a0b678957242.nq.gz
│   ├── f8351e41ccd4a64dca237bd8f8be0702b23989dc.nq.gz
│   └── f8fe2cb434cefda404c506d541959e2fefc86884.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 43124193a652b583c03a2123c74459177a1c5dba.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 131 files
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

[UKPLab/acl2025-con-instruction](https://github.com/UKPLab/acl2025-con-instruction)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
