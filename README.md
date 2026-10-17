# Repolex Knowledge Graph of MagicStack/asyncpg

RDF knowledge graph data for [MagicStack/asyncpg](https://github.com/MagicStack/asyncpg), parsed by [repolex](https://repolex.ai).

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
rlex download MagicStack/asyncpg
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 13b01910da3fe01b8241c31cc86eccb1301a2d39
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 13b01910da3fe01b8241c31cc86eccb1301a2d39
│           └── chunk-001.nq.gz
├── blob
│   ├── 009598a86b87ca5f5926ad1908beb62783f17889.nq.gz
│   ├── 00e9699a031710ee3f8a9c119fc946ef6e5cfe99.nq.gz
│   ├── 01e4404759e0ca373370db1999f0faf507c15871.nq.gz
│   ├── 03654af137a8bdc3e9563e4506d5e69ce23f511e.nq.gz
│   ├── 04241953a7e71eba73f2dd2f708f1e1f58a15187.nq.gz
│   ├── 043454db08a1c72bd0bbda869407ea03c9ef7930.nq.gz
│   ├── 085ea2ba5f0c6895cb8739321ca21a95816a4526.nq.gz
│   ├── 0a1a5f6fb300a8e9fa84ca15c68721d1086ec3dd.nq.gz
│   ├── 0bc8de8fba893cc4ca1c453e5d0fe09e1275e1ba.nq.gz
│   ├── 0c5a97954656bc94d20c5221eadedd564be659d7.nq.gz
│   ├── 0ce3093ab5deab8b91a254a25abba8eabeece320.nq.gz
│   ├── 0eae4d30e0feb52e526ab0cf8aa858a40fabfd03.nq.gz
│   ├── 0ef6c7e32c420de87c29305ccfe63bc8a938688d.nq.gz
│   ├── 0f3290d8fb0d537fda30578514605965bc12339d.nq.gz
│   ├── 1038c18da0df1915bbb7b0ba16ae5a284aed086c.nq.gz
│   ├── 1463dbe4d18590a5adb8b07a94fbfd09f6c1a084.nq.gz
│   ├── 1c25d8d64a47ca9e5b2cfcc8c3a6160733502038.nq.gz
│   ├── 1c72988f4fc659f02e0ba193ab205180fb4b0e9b.nq.gz
│   ├── 1cfd9e9080eb20b753044803dcfa204d5db92e64.nq.gz
│   ├── 2097a596ee31b7d2db89008122a24b1ff3652e56.nq.gz
│   ├── 25050aac01de1673b35b62a9613c7fb29c64ccb5.nq.gz
│   ├── 29e9cb9dd105dfae5337f75eb73e943546ad3e1e.nq.gz
│   ├── 2a779e7a0f015f0da0f9867c8ab8b230ce77ea20.nq.gz
│   ├── 2b5356666e0355abb1ba19d9db6b53df2e3f485d.nq.gz
│   ├── 2ca5b0de00f834ca09c38cde0f06fb23ae04746b.nq.gz
│   ├── 2d19fc766d98a08d9d1437896bfb008a7b15f340.nq.gz
│   ├── 308f31094537b3f0d20e095a0b09815395b100f8.nq.gz
│   ├── 30cecc32af5ee8aba5fc337696b24352610eca0f.nq.gz
│   ├── 3141fe8b5eb5ee25ddf6049f199b4aadfd6fc589.nq.gz
│   ├── 369db733899b8e2358e74b8624c598cf9a4c5f5c.nq.gz
│   ├── 373ba203979ddefe5c5171ce077dcc1f3a0b2189.nq.gz
│   ├── 39b914b33d0eb084a5c1a02ec610028a7508a19b.nq.gz
│   ├── 3b0c1d3cc4143f574c0ef4f7ef2e927bef964ab8.nq.gz
│   ├── 3db97665ead962c91275a236e5e8b6fae3b83dc4.nq.gz
│   ├── 3eac0565db03b15488f7339164d49c02447a92b1.nq.gz
│   ├── 4145c6645fcaa7838e1f631978f7c6e4de69d693.nq.gz
│   ├── 456d83fa1f044b51a0942c8fa7bb441b0d025d2d.nq.gz
│   ├── 45b29e1c1c4b24176b683ba06d275f44dec5ed44.nq.gz
│   ├── 467eaa2cbdac6b3809572309ff9af6af23cce973.nq.gz
│   ├── 48d24588c05c53806c05ef30d94ec1fe0ba8ae7b.nq.gz
│   ├── 4abe164452e95c869b7e386c30ebb0df4a2aa274.nq.gz
│   ├── 4bcdd743570678f154504bb0fcc43039c78d665c.nq.gz
│   ├── 50d20ffccfd2c7e23a21f552ed74ec41bcda1b6f.nq.gz
│   ├── 519c5a09162ed5a49cbdf484107cb7632c7072a2.nq.gz
│   ├── 52e5f9e3c889a25b084c07e262c75297a578543d.nq.gz
│   ├── 562811e697763a6e589c4f0a5f021fc11e52492d.nq.gz
│   ├── 57eec6501b35fa649d11050152067ad96d7bf61f.nq.gz
│   ├── 5c1ca6992f9a3cbb7cdb2c939dbe62a769c528c1.nq.gz
│   ├── 5e5e89bf32b3acbdfa981295de47c79ba173e66f.nq.gz
│   ├── 606c2eae5ee84b97d0b01af6660d196d0049dc83.nq.gz
│   ├── 6446f2da101a24c237151e0d25b47c63254ba74a.nq.gz
│   ├── 64bc938f68869605db8d6fe02d91635ea610fb73.nq.gz
│   ├── 64ca921d845a17a7db8b3d2d0382ca2377d2e6fc.nq.gz
│   ├── 661021bda8bea41a9ad667bfb155a7e65b281854.nq.gz
│   ├── 67417a3f946e95dc76c3dafdc7f150fc2aea5ceb.nq.gz
│   ├── 6a7037efe385db109aa0d4b31c39539ea623468e.nq.gz
│   ├── 6c88d686b231d1e1031e14332cf3024ad841d0f6.nq.gz
│   ├── 717cd6f69fac7e9b4596cbea466f6dcaa5a9bef6.nq.gz
│   ├── 724b23a14d35ac4c36e845a37c9a25e902f031f9.nq.gz
│   ├── 725cd15a47b3a03a8e4a13b3422ad9c8c5896db8.nq.gz
│   ├── 73e795fc58a45be25bddc76aec0097579dcdad37.nq.gz
│   ├── 752fd007c9ced73a6bbe4bcee70049f7ba986b71.nq.gz
│   ├── 78caffcc3ef8cb06d69096b0270f3ec75aa0256e.nq.gz
│   ├── 900d940e7041b803b54149c788b8a50c16930716.nq.gz
│   ├── 90389cabcc09aea4c9f717583f54caa5cf3b4b95.nq.gz
│   ├── 910cf81fc9738818baee92688ab712b2debe6990.nq.gz
│   ├── 95fd9ab2b71a8c23dcf7b0936521ca83607f7b66.nq.gz
│   ├── 99ad3667d8ba0e650599f2f400519764ab67efe7.nq.gz
│   ├── 9b8b5673efdedbdb42bc44ebb478f70508546622.nq.gz
│   ├── 9d2af274ac33c85b1831c2ae43beb82d78925e84.nq.gz
│   ├── a1ad67d705778647b7ad8827f3d2a13201394651.nq.gz
│   ├── a36b65e4646010874e5f6c19d648a6b43bf0cbf7.nq.gz
│   ├── aaf464f6a97d662fe8391f78e3214a2b913d5139.nq.gz
│   ├── ad0cc4acfb1f4ab236bbea8552c4c2dc10134708.nq.gz
│   ├── af49e39b629c8ff43027f13c08e2b26788d1ab38.nq.gz
│   ├── b19044d478a587e52ba37929617275b096edb2c7.nq.gz
│   ├── b2bb93dbd059b4f706a86570de41fa1f197af5f1.nq.gz
│   ├── b4a5726f8a2b81b6d22edc109cda5280c1b8fc72.nq.gz
│   ├── b5a455aa984859cbc55c155f53eeb441080189aa.nq.gz
│   ├── b5eb1d2ede2b67657a15089f5762b3ddad85305a.nq.gz
│   ├── b9a48b36d0b623d347e3cab5a2fa54e32ff7a444.nq.gz
│   ├── bada7998f0c134b98376fb6513b7bed773718bc8.nq.gz
│   ├── bdb5744d50b76efa33314927e2804290fc55596c.nq.gz
│   ├── bf95537afd59a4c381549ce0dcaeb16f87f1e2d5.nq.gz
│   ├── c3b4e60c8a32ee74386c963dce900e44c5ed142f.nq.gz
│   ├── c4067fc7276cccfae49060e924e018ac09edbeff.nq.gz
│   ├── c412aff7b602a2da25f6a001ce9bc5ba252cdeab.nq.gz
│   ├── c4b66b4a1d9632d53943f7dc986532b692741f06.nq.gz
│   ├── c6a87c655d6ef52c2b59099224435f69a985b53d.nq.gz
│   ├── c8d0b650ffe3ca97966d61235ae110e779ff2bc4.nq.gz
│   ├── d0479cc7a72265e0b7160a52bf36a19c4bb83923.nq.gz
│   ├── d19f261f66193e64a8ca855a17a8e24b3895fd60.nq.gz
│   ├── d4e76b7a2121b0b1353acfb16ae15c4f882148eb.nq.gz
│   ├── d5936c7a1f5ac95fa2c7e44925ef3d1e430c9975.nq.gz
│   ├── d931386122bbcedb3bd8a39345d034ff836ed467.nq.gz
│   ├── db0d2ab0cac07f7f1e79d17ff618cb474d2de594.nq.gz
│   ├── dbf177d2c977aa4f21e7a6ad1d2d2be336f65d25.nq.gz
│   ├── de5f9db5ee78270eaf5be8f3c8717ea6f2aa4641.nq.gz
│   ├── de814c10737434e5a8aee74bbd277ef70f33592f.nq.gz
│   ├── ded56b9188075d39941090f461546b476bbd5f48.nq.gz
│   ├── dfaf29e01602f5c4332279cd2e3d268a337728fe.nq.gz
│   ├── e1f8726ef504045928d95ae837691629e4f3919d.nq.gz
│   ├── e215391bf544e85808f853d53ba7309f8bc4837e.nq.gz
│   ├── e2bb3b68b17b054750dee8365e1480b030597a13.nq.gz
│   ├── e398e0f6723e47b371815b289d361f6311776920.nq.gz
│   ├── e4a4a0e2f483c73958df68445799ccb6ae062200.nq.gz
│   ├── e52798fbd3df55e962d0cfea4934e975a080c64e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8811a9d6a9906728bdf9bfa8893b5d5a4ea8140.nq.gz
│   ├── e9475653015641f9759e415c33ec9a9b6ba9da84.nq.gz
│   ├── ea9bb94e92734078321f8c7ff9882e7f288e563c.nq.gz
│   ├── ec9c96ac821482c664419957a2e1dd22c7087331.nq.gz
│   ├── ee9647b42dd4daab34484369c8644c3e80b5cf77.nq.gz
│   ├── f2901c9e18983679068e74ec343418f8dfd4e884.nq.gz
│   ├── f2ac569529b6dd6eddb8236bb503601f14e56cbb.nq.gz
│   ├── f54925903a986269089fd6a76f3e1221cd138573.nq.gz
│   ├── f5f3ed1f0c774442c7f0dbbf25fe1ce11e2e39ab.nq.gz
│   ├── f66db159f60199773ee141beb5b7c46446e71e93.nq.gz
│   ├── f7445638dfa989683d4bced036119fb53e5c7ccc.nq.gz
│   ├── f84cf7c06bfcf5aa5d4915881b115bf2db8f937b.nq.gz
│   ├── f93b8ca7dbd95d7bc6b868f615c32e8acba0c379.nq.gz
│   ├── fdce3bf37b78ed63b591acc56cddc268e50ddf4e.nq.gz
│   └── fff523c98b29311e91940b40729840f61b03cc16.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 13b01910da3fe01b8241c31cc86eccb1301a2d39.nq.gz
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

[MagicStack/asyncpg](https://github.com/MagicStack/asyncpg)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
