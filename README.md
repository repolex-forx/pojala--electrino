# Repolex Knowledge Graph of pojala/electrino

RDF knowledge graph data for [pojala/electrino](https://github.com/pojala/electrino), parsed by [repolex](https://repolex.ai).

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
rlex download pojala/electrino
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0bf75954b56440f0a0ec6aa83f2ce50d56ab52e2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0bf75954b56440f0a0ec6aa83f2ce50d56ab52e2
│           └── chunk-001.nq.gz
├── blob
│   ├── 023e7f1feda78d5100569825acedfd213a0d84e9.nq.gz
│   ├── 037848aae68b7c5ba539cbdbd446562bc1fcccc9.nq.gz
│   ├── 03ac0201eb740327c4f912e849ed5f4e06d65e39.nq.gz
│   ├── 0bae544034608bad13e058b04e712f42ff29694f.nq.gz
│   ├── 0e8d0276435f81fabf05cbed359e7700b0b7524f.nq.gz
│   ├── 0f86566d369a65030e4867bf65d43641e76fa583.nq.gz
│   ├── 120d02380f2163a8c25a628839408241b048c42a.nq.gz
│   ├── 12650971940cae2c3ec62da86c20a96b88464b01.nq.gz
│   ├── 128fa626bffa9392dd8b34580559b04221b6dcba.nq.gz
│   ├── 130a027eb173f1016c3d294fd27b2dbd59bb1c57.nq.gz
│   ├── 1408de767332b8f93c261ad52be3bfd6e0639e75.nq.gz
│   ├── 14133ae5df797fe4ebb3653198da8f64cde26dd0.nq.gz
│   ├── 1863d50cdba7d67ad3493645692aa03cb7969f4e.nq.gz
│   ├── 1cd81da1ed2cd16b101fec765d4225c04072a19b.nq.gz
│   ├── 1ff0c423042b46cb1d617b81efb715defbe8054d.nq.gz
│   ├── 21b4dac09ab83f80ed47f8948069f8647f823134.nq.gz
│   ├── 21b83c7a2b842ce8047ec4aa9406290a7ded9a57.nq.gz
│   ├── 272229b1d753d96a29f53f63ffd7a1d649cd575b.nq.gz
│   ├── 2766751726e86318ce60e932e0794f7466179d6c.nq.gz
│   ├── 27f85f255a2f42833fd4bbe901419946b5f54673.nq.gz
│   ├── 288995b397fdbef1fb7e85afd71445d5de1952c5.nq.gz
│   ├── 288fbf613300675aa0b28469b25e4375c26ee3e3.nq.gz
│   ├── 3198e72ce32f79b5f4c490f78494a1913ac73fde.nq.gz
│   ├── 32643a862cf0d6cace6ec154a22d662fb157eb9d.nq.gz
│   ├── 360b2c0e2cb1ba3e5fc3f61158c7fd4116ae227e.nq.gz
│   ├── 37a86bad5035351c0961a5b037dfaa11f8b2c264.nq.gz
│   ├── 434c2a4c50cae889abcff06404edef68d59ca4f1.nq.gz
│   ├── 44f43ba8100dcaefa61e15105e5ec0a793ea17f3.nq.gz
│   ├── 46b5ea85bd8d9305963523946663607d587e63b3.nq.gz
│   ├── 4ecc964ef86ca92949d7113fe8f81b60825028ca.nq.gz
│   ├── 51aea5f9a5ae166a57c0a2c1b79cbc5c9f448522.nq.gz
│   ├── 591661e8b3416b409495efb6ca6356eac4b15003.nq.gz
│   ├── 5dce59b72587e2ff7104ea7bd1ae7a71966e57ea.nq.gz
│   ├── 5e0e2720d377d0237724892f99832c6dac95dc0f.nq.gz
│   ├── 5e4ae0ffccf78a376ca4a24dcccc73e7f6401305.nq.gz
│   ├── 60b1005bda656989bf33a345db69872161cb5ed7.nq.gz
│   ├── 625b70e29e2a9f316698d27be2b2d185b30ee195.nq.gz
│   ├── 65d38d0211242db5d73fb93ef7363f87f23de1fa.nq.gz
│   ├── 674d3115885f289168752bb689ee6d1d45238017.nq.gz
│   ├── 67ae415e1bfe374d79abf3ba7dbfc603c395661a.nq.gz
│   ├── 697b24c6c185414d6d2b24e173a21c4146d3806f.nq.gz
│   ├── 6d205f9455e964854035159ca4ac496c7bfaee6d.nq.gz
│   ├── 6f912b57f20439a7e413b32d27446c25beac71dd.nq.gz
│   ├── 71923e493dcda27358274373f47cf93316552fda.nq.gz
│   ├── 735f57adb5dfc01886d137b4e493d7e97cf13af3.nq.gz
│   ├── 7385b56c0e4d3c6b0efe3324aa1194157d837826.nq.gz
│   ├── 762c00b8094169bbf5369c55a7dea7cc1a87f349.nq.gz
│   ├── 7646adf93743918a23af8f81bc6b7f5c1445568c.nq.gz
│   ├── 7a80c6c7864c2b021d84b9b9b881bbe075535707.nq.gz
│   ├── 7aa1895a4424ed30d40f981ef55667d42adf58ea.nq.gz
│   ├── 7c40ffeb1e5b042e2d24b5cbd2343a12039e809a.nq.gz
│   ├── 7e918cb45a8f7575912fda6e4a6ee7997aac4d37.nq.gz
│   ├── 7ef08f36bc6729e3db187137af2e935f52c25319.nq.gz
│   ├── 8433ea1d93675c41be32ef58a68fbca4ceceabbd.nq.gz
│   ├── 84e8d618cbe920121ce431bbd1e130709a75087b.nq.gz
│   ├── 87cadd19b2451948b933a06217c853c42215c61f.nq.gz
│   ├── 88a45011d17ad96eb9fd154859e3048a1016de0c.nq.gz
│   ├── 8ad849de3746aabf83ad0a9f3edecd478073753a.nq.gz
│   ├── 8ec764233bd17f5b15a24e0df800861b108f8026.nq.gz
│   ├── 8f5c6b30ce64614f70a1f012b67b723c493ab04d.nq.gz
│   ├── 96fc41e8c3415fcf13f26affe05380365fd1ac28.nq.gz
│   ├── 97246f93b0772e478944e577a45785fb5c8662c3.nq.gz
│   ├── 9cb27ea56b53cb4feee18c09eca7b1c8e337bdf1.nq.gz
│   ├── 9fef56d7337d2634e4a46ab99dd4e006debd2827.nq.gz
│   ├── ac76aca5e4b4ede784775ae4263452bf727ec1e8.nq.gz
│   ├── acf9cd00eac147fba8724a80a51d426e04bed197.nq.gz
│   ├── ae4c1dd3989ec4316f0f3f322707fd8717732dac.nq.gz
│   ├── af36720458d7250fa5a9bfa9e8419c700071146b.nq.gz
│   ├── af49fec1a5484db1d52a7f9b5ec90a27c7030186.nq.gz
│   ├── affaa76c61ca8fff1bf7db3bdf815f5cdede3710.nq.gz
│   ├── bb8f716b836697f0c4343e20909f49165378e2b4.nq.gz
│   ├── bbef593edd20a6d3419c1c2cced7cfe7c9b14d28.nq.gz
│   ├── bc65880f080fb01f522a10167ee2e355cd676fb4.nq.gz
│   ├── be9c37043a2a69382dd11e0fc795037302b22f2c.nq.gz
│   ├── c10ebeacabe1941593c5f4b5a8567a575c4c0934.nq.gz
│   ├── c2e44fc01ceec71a260394334e3f6f3638e47adf.nq.gz
│   ├── c538b83d30a9c130e4eea30861c75170d7bf5a8b.nq.gz
│   ├── c5715af712952360114c76cd79a1ab9da8d08846.nq.gz
│   ├── c686766a52c0e0d0bbcff9e9a0c8d0b6cb093c23.nq.gz
│   ├── c7ef22faba8178308d91c7c4522bc44c6968cf2c.nq.gz
│   ├── c9380405cc7f4eac6ac98bc7898429e4b833be1b.nq.gz
│   ├── cba32e9009b0faeb5faa71ad79d2a941b1a6da85.nq.gz
│   ├── ce342a2ec8a61291ba76c54604aea7e9d20af11b.nq.gz
│   ├── cff5f99ab8a57b87613d2ce19be7d1ee81a2da01.nq.gz
│   ├── d5f25ef9498317cc51da7e0418210c9dd924d03d.nq.gz
│   ├── d62cfd6c3565722dbb33b3bf644ef843a706dc69.nq.gz
│   ├── d729001f45a14745741b75ddd02ac968f0aca041.nq.gz
│   ├── d76f6c39c5c5e119553cd262396ca5301daf265a.nq.gz
│   ├── e26ef0c2e83d7f0be141ee47a2848257cdb4f657.nq.gz
│   ├── e32916adec0de24c28a0526fc54712103782f092.nq.gz
│   ├── e49a50e7499c086fcc8142cad380712a1bf0bbe7.nq.gz
│   ├── e6967a9aef690916ddcd82bdd72f0141542b1181.nq.gz
│   ├── e88dade28bdfe1d03eb027aca7ab2329a976b06d.nq.gz
│   ├── ea077939813b2b0c5e922cc39a4ce7b59833d6c4.nq.gz
│   ├── ec0d6e402057e644df98b348c5c3a37ec8d603fd.nq.gz
│   ├── ee0f3a8dff27f7b22acd69f3ff53535332a52413.nq.gz
│   ├── f18473d2d751355ed3ca4e6787e4788da4319d14.nq.gz
│   ├── f2eb74f2eb158376105509ca54be608b01f268f5.nq.gz
│   ├── f2f1032ca2b3e09aee481108d100f4bda46df0fa.nq.gz
│   ├── f6c02ce97e0a802b85f6021e822c89f8bf57d5cd.nq.gz
│   ├── fa724be64e27dcf1c7dd65e1f2e9b1d11a7642cb.nq.gz
│   ├── fab4dff0d6e95fc375dc5e40cea9c5eef8c14320.nq.gz
│   ├── faf93309a09b61590e924444209de91d4bec7d6b.nq.gz
│   ├── fb02f4f162d18e4a8826de2de090efeccbd9e2e4.nq.gz
│   ├── fe2b45415124ec4c223006e19defd56850da95d9.nq.gz
│   └── ffccba2f7c60192ca24ab98798c8c4008cce8504.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0bf75954b56440f0a0ec6aa83f2ce50d56ab52e2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 114 files
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

[pojala/electrino](https://github.com/pojala/electrino)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
