# Repolex Knowledge Graph of scverse/spatialdata-io

RDF knowledge graph data for [scverse/spatialdata-io](https://github.com/scverse/spatialdata-io), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/spatialdata-io
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 95486860987c59ab535cd52bb293e4d7fe99e04e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 95486860987c59ab535cd52bb293e4d7fe99e04e
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ad6a6ea9418df96256615a564065e38c8332ea.nq.gz
│   ├── 04e4c45235dbf28c50e76db8e73d807a42bde635.nq.gz
│   ├── 090bd95ef1df14828a8d204f2fa5b5b8bc5b4b7e.nq.gz
│   ├── 0acb81f3e2aadaa0e947724499d8fa312ea4adf6.nq.gz
│   ├── 0e2e2b1edbbf828c6e4d579fadf6fb5a30248d98.nq.gz
│   ├── 11957ee1c0ee9e590ae4c3e8b64e7aa926379bc9.nq.gz
│   ├── 122f5354fc696f6d6dc521d3db388fb228417c78.nq.gz
│   ├── 15bd37f20748b440c3b8b755b0782bbfedbd6485.nq.gz
│   ├── 184657e63d0238083e33fd645ade96a726f30f62.nq.gz
│   ├── 1b660edf2b44033b48c62b76891079541f25249c.nq.gz
│   ├── 1c10cc53e7c22c8aa404f68aac6248b1e54a4668.nq.gz
│   ├── 1c116e575fc66aac90e079dedac49cf696d24210.nq.gz
│   ├── 20d9f859e6983828434e517c86d736c29b92d72b.nq.gz
│   ├── 266581e562d6d9c079b9acf5c7a444e69a4c97ec.nq.gz
│   ├── 306f7847fa34dcc2616aca1e2f423949eb334160.nq.gz
│   ├── 31482b7bbe48aa8b03dfd976c663947db3c228fa.nq.gz
│   ├── 322793040792b8440f6bb6db6e29660b8e54b266.nq.gz
│   ├── 36dd4d8ba2db9fcfb535bd1097fa66b77756a319.nq.gz
│   ├── 36e2a88f90e74c91849ebe1e69a5a50c07e3a105.nq.gz
│   ├── 372f533c86285f1ff858cfaf627ace03e93a8ab2.nq.gz
│   ├── 38107e9cc3f40d29ebdd82d5945bd78cbf49265c.nq.gz
│   ├── 382b0f639fd3d5f26f3f5ca19d6bf9f81f50fff4.nq.gz
│   ├── 39e3a51180c3fd175a12d1399051d4bf4bc7bfa5.nq.gz
│   ├── 3a105fe1a4bc82ee58638b81a5f0aa95f8c6c2ad.nq.gz
│   ├── 3bb744b7ba32eedf1c8ebcc3a14ce1fc5381c059.nq.gz
│   ├── 3da189e41923021edf8ba0e3a6ee4c35467acc04.nq.gz
│   ├── 3dad176f9c4dfe0e07ba4003bac15e983192fa71.nq.gz
│   ├── 41dfd8901541ef322c356c73122c2081cb2f04da.nq.gz
│   ├── 428ac9000c0bc98a84af461900dc7c0c2567140d.nq.gz
│   ├── 44130120a555d74174302c03184f810106aba314.nq.gz
│   ├── 5252ad33af4da717b9c3124f6cb1395d7aad1aa6.nq.gz
│   ├── 57547f474bbf2c23718f51a0ceec376dcfb75762.nq.gz
│   ├── 58673ae913dbb51a473d98cfceaf5d3e3d575b9a.nq.gz
│   ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
│   ├── 5e4c26adfa3718e541287cdc46e4a6273885ffe6.nq.gz
│   ├── 62b5f309d7fe6d1bcaef6d1bce1734291f0137db.nq.gz
│   ├── 65531804ffd2802cb1fededf5408674c5effafca.nq.gz
│   ├── 65fa872f7d061bec09a2fae251f6344c64587a4f.nq.gz
│   ├── 66272e603e11827951dbfcc058b04739035fffb3.nq.gz
│   ├── 66678e378b55a7e2b28d2087164af8999aff39cb.nq.gz
│   ├── 67eb948d72ad9ee53fd1cbe38e72bcccaa753334.nq.gz
│   ├── 6aa32280c138497db407f82b81c58981a30ebf0d.nq.gz
│   ├── 6dca75df3d5254f7f9cd4a8dd3eff82ea0369c0b.nq.gz
│   ├── 715bdc4e0126a960d122c51ea6d99e13f067c258.nq.gz
│   ├── 764f5efdc8436ab8f47af1f2376f4af3cd9ce303.nq.gz
│   ├── 76fe3ec38cc58b10542b8324b70e8ca02d8c0105.nq.gz
│   ├── 79a1c72b81b957de53fccb7475e7f07845090e63.nq.gz
│   ├── 7d60755c4c13722aa6478b4343a068b199d2655f.nq.gz
│   ├── 8a98211caa0b2a7cc365c355f7ce1c57c5cc9ebf.nq.gz
│   ├── 925ed07725de5521c44ab3d5b43780188463a2f3.nq.gz
│   ├── 954237b9b9f2b248bb1397a15c055c0af1cad03e.nq.gz
│   ├── 958d8f6760bb1585da31f05bb9c9bda723eb83a6.nq.gz
│   ├── 95ff16506bf77144ee1cad2f6a9c0984f899f78f.nq.gz
│   ├── 9a1ca1b6e4036904e00f1a4eeccb651f09442fee.nq.gz
│   ├── 9c7135e1dd6c94f7bf8c6b94042aea4cb664ead8.nq.gz
│   ├── 9d784121cc5c441b69a56ee5b25cb2c4daedb8ec.nq.gz
│   ├── 9f8f2208c4bdc0f0b0cafb4c0d0b5c79d32c32da.nq.gz
│   ├── a4caca8a5d104be7a21d705e87bf6047b3798af1.nq.gz
│   ├── ac2e7e0342f4809316f689b728d756099205a2c9.nq.gz
│   ├── adb20e764365f9e2ed8ad04691f0be0ccd6ebb82.nq.gz
│   ├── b439da2030275869d6334bf8a84a07fb0d3e035f.nq.gz
│   ├── b66485563369a8ed09d61a319b50af32563f2b3d.nq.gz
│   ├── b8c8d47fa0a99101c675af913b08144664399119.nq.gz
│   ├── c0adc4332bf264ff04a590ae4de057e199370be8.nq.gz
│   ├── c6d9c51411d48ce28c55aa9d57239bb5be7f0c95.nq.gz
│   ├── c7268d64268206286fca6d1a07481077c3b214f7.nq.gz
│   ├── c764b42bc4f94671399c0dc93585a027539b71f3.nq.gz
│   ├── ca3ba70cf494d39e4d6636baa74bf6426ab47d70.nq.gz
│   ├── cb764d42d73335c18eb8d991b9b54d063a632d9e.nq.gz
│   ├── cc32eda8a90cc20e1e9fdc7039b83be81e3d1445.nq.gz
│   ├── cd6700dd54f7f1e3ed6515c85732550b5f6a4615.nq.gz
│   ├── d0c0e2917651ab1d38f689317e32f463c392c3d2.nq.gz
│   ├── d298d1ad0c7314b9eeb59e52e6130fe34767c277.nq.gz
│   ├── d454d7418f293a957188999705b05a5967c1d238.nq.gz
│   ├── d7a14736bf7450615e3c8070ea60d51dc8618092.nq.gz
│   ├── d95e5af09445cd22c732cc612e4696dcf5b1d60d.nq.gz
│   ├── d9e79ba64848091a9bccd21dc241c61c669dad7f.nq.gz
│   ├── da9231c7b8d3a1f4a5c9637e78c9384c7a0cbe10.nq.gz
│   ├── dd4ef30e3d52b93025ed10ecc3fd6953563a69e9.nq.gz
│   ├── e46613d2d4937a85b1a207a34e5b685dbb7065eb.nq.gz
│   ├── e60010a6784ffcf4b16a731e68754806266b7513.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eaf4f0f82629c785c14f16748bc914af3d9e31eb.nq.gz
│   ├── f0a5f9f72906af89db4ca515489bbd7c18730cb5.nq.gz
│   ├── f2d6e6b118b77a0bb36b8e0b476091708b59755b.nq.gz
│   ├── fbe1adc56383b0c75ab6da69b6aa9438fdb4a5b5.nq.gz
│   ├── fe7b92b74451e1f81a31ddd6a90fd821b5105078.nq.gz
│   └── fe9168e1644a712d3dfab2e002a5c5135cdf602f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 95486860987c59ab535cd52bb293e4d7fe99e04e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 96 files
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

[scverse/spatialdata-io](https://github.com/scverse/spatialdata-io)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
