# Repolex Knowledge Graph of beeware/colosseum

RDF knowledge graph data for [beeware/colosseum](https://github.com/beeware/colosseum), parsed by [repolex](https://repolex.ai).

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
rlex download beeware/colosseum
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 191d742dae03801da728d541b8f61c784ad98e26
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 191d742dae03801da728d541b8f61c784ad98e26
│           └── chunk-001.nq.gz
└── blob
    ├── 0006bc27b42386323872de71288c268e1af8b108.nq.gz
    ├── 013bc5190b6cfa84352945a1a5f35bfbb11de2ec.nq.gz
    ├── 01687e30c6a76af3b18af0613ab519cef0bdf78c.nq.gz
    ├── 0184772f763fa727c8bc7e7525616672bf0bb196.nq.gz
    ├── 01eb9e473abd5df5d3710730f496699a8626905f.nq.gz
    ├── 021deb541198ffd35c76147f608719cc3f287e53.nq.gz
    ├── 0239c8448306240ef2c362bbfff71204025cb3d1.nq.gz
    ├── 0472d56aec11d8ec928c93424caf8d384c8db1b5.nq.gz
    ├── 04b4603c9f90a65a2f18a2533262b8e4592fa334.nq.gz
    ├── 04cf6e86c71967c913d9860b6d4976861042b85c.nq.gz
    ├── 0536ef60d5db4fe7c5080f5ac7f30a997a32fc3a.nq.gz
    ├── 05ef0e31cf1f7459a542cea76e8e1f4495f8b1cb.nq.gz
    ├── 06647e4717fcd3a086a923f63c3b572c1cd9b1f4.nq.gz
    ├── 0696ad123052d635e0a655aa59edc307adf679d9.nq.gz
    ├── 06edbd36fc1a5a5f9ee58da8125b0fa4e5bbd0d9.nq.gz
    ├── 0894d5c06e890f3f155133313e46dc54407e7959.nq.gz
    ├── 08cd276c7ed6ad99cde66ce8fb8a87af42227036.nq.gz
    ├── 09f05bf2224176c84d64dd7f7e63bd3f5f4ebc7c.nq.gz
    ├── 0ac70ca93efdd4466f76269849a473eaefaeb183.nq.gz
    ├── 0ac8b941d81f1d691e0254fabb3047f2f450bd3e.nq.gz
    ├── 0b1d8122f8e1d8d972f3c098822e41343f8cd3d3.nq.gz
    ├── 0b6f1fe4d1e1f957584102c839282a51039f2688.nq.gz
    ├── 0b70d5ca1e1b89258cb9c981055a4b7d3ed1b61f.nq.gz
    ├── 0c83d4d6dde889d1ba9b085fbacd4b28051f4023.nq.gz
    ├── 0cad5e1590bd484d6740ec779613c6cf14086d6f.nq.gz
    ├── 0cb16dec3232ed0283a34bf77c9c9ebfd86535ba.nq.gz
    ├── 0cb6e91d7a59be19af63fd37cf919c0270b76f22.nq.gz
    ├── 0cce842955d8f33070f82f09416c5964ede95b40.nq.gz
    ├── 0de29400b340fdd4b768bd738a74efa2b1658e52.nq.gz
    ├── 0eb9b6ee4b7d0c9caedd5ab7130a1a73d8af7390.nq.gz
    ├── 0ec6f367715148f9e756ecb8b9808067a03142f3.nq.gz
    ├── 0f7f86d5d6e9286b78f7af02de2fab824ff66510.nq.gz
    ├── 101e818a5402d4237941f8c92e9359f6d593ab25.nq.gz
    ├── 110e5d6c9caabd1259cc2eada33056522f791e81.nq.gz
    ├── 11649e707306a14338f8ed24ed7f0ed4424199f3.nq.gz
    ├── 11e98862615ea38a5bddf4610539cdc8b1f37fbb.nq.gz
    ├── 11ee5dd056e1dced1fbf9bbb6ceccc338b0d6308.nq.gz
    ├── 1264a7255c9b2d49bef6d6d4f1f0693faefe3639.nq.gz
    ├── 147c7025fda601c5f3ca90133d2d1c135d9147c8.nq.gz
    ├── 161af2a618d9cb267b26ce01673c854699e7c625.nq.gz
    ├── 1659bab721ca2b2af23b1dac5e8fc71e60794f86.nq.gz
    ├── 172f4f45d9369171e99b41bd001deff17d81159e.nq.gz
    ├── 173ba3ae72330d49bedf048cb1dbe64f89d9af10.nq.gz
    ├── 1812f5aa865593fbabf3d6edde69d6cc2dff1ff2.nq.gz
    ├── 18dee2f6f8d957e86f3596cd9c814d931b489b2b.nq.gz
    ├── 191d4e3320de234174d32bfb16540d47294520d0.nq.gz
    ├── 1a3b39143a51a7250cc81be6e37cfdd85103513d.nq.gz
    ├── 1ae4f3354ef4eaa9cef5a6a4b98561494b82c734.nq.gz
    ├── 1b1ed929dbb9da73a881cbcab741d4cd86cde66c.nq.gz
    ├── 1b43026d6e08c77e6b779981d17889745ef5accd.nq.gz
    ├── 1b75e825485a9879aed3f46b9e750b92571cba9f.nq.gz
    ├── 1d1825fc3844f4f51df6f2936673d17ebe56b12b.nq.gz
    ├── 1d193704bdc98736a9fe80bbeafaed933a7609c1.nq.gz
    ├── 1d6f99bb40f49b26ea46f4d549aaee296ce50f52.nq.gz
    ├── 1e24968b528f5ee8b49a4877d8ddc26dfeace45c.nq.gz
    ├── 1e2e1a44eeddeabb6cc500ceae864bc0c186e8ff.nq.gz
    ├── 1f726eb46c165c4b9b403d5e3c47a22927d48bd1.nq.gz
    ├── 206af28ada445ffd483a2d36cff65853266b85ad.nq.gz
    ├── 2079e1587005c950a3fe82e976bd1e7275625f05.nq.gz
    ├── 211589096375c317b5851e861a43a603d3a4906a.nq.gz
    ├── 217c35055bf0582fd9b54fd47f973513279424a2.nq.gz
    ├── 22586da3ae61cec25af43c3165a965f809ece12c.nq.gz
    ├── 2264c3527e0bf75c66defac6cc72b0f81f61f6c1.nq.gz
    ├── 22b62c2eb6145bdb45f8abc39ec2c6959cf6023e.nq.gz
    ├── 22cc7aa0e248daa7c3dcb735d39ae7d29b591206.nq.gz
    ├── 23509c67f412e165ff02eb2dfcef601ac7e3d954.nq.gz
    ├── 23f0b54714bad7d7b43b4ffeb6668fbcd7c4819e.nq.gz
    ├── 2492b18e6b89ee4246a9883d254e2ef5acfc3f36.nq.gz
    ├── 250871f17a64883f94456cbb8a95be5c61b25bcb.nq.gz
    ├── 252e42b00f67247e6b092f0c8dd63f01cc0e64c6.nq.gz
    ├── 25d148c2380a347dc9abe40bdb5aea61770157a4.nq.gz
    ├── 25e5fe0e3e8f5868defa794f7a16eb24012c7695.nq.gz
    ├── 26472c2f3703afc9a5a9cd95533fffc1f0397422.nq.gz
    ├── 266d27f771ca206679a7644be351f359a7bb4b03.nq.gz
    ├── 268f60ec631fc0300d7ed5dc4d2682c0ec5c9aaf.nq.gz
    ├── 269000e2749df6b2e41c0d6187f37dbbbaeb0bfd.nq.gz
    ├── 26c27854e2b745adbaef85e65a36eb8400307336.nq.gz
    ├── 2822bde08977847fd9dd3992a94b567bfb5a69ed.nq.gz
    ├── 28235e49249b6cf2e1885590f69ef2bfa28913f4.nq.gz
    ├── 284b257ef700a56b2a3d450210815628ed507dcd.nq.gz
    ├── 291a8bf14e9dc4e6d7a0915421203e5004ceca76.nq.gz
    ├── 291de9d6a77c0e8cee4603218ba8e2f127af2718.nq.gz
    ├── 2929900009ee8ea053b39ae5815d8ec768302382.nq.gz
    ├── 29615713ece7cc32c35b04af8c11f6bc381f1025.nq.gz
    ├── 2a083d3b95d0f09c2bf3abbc6fe8d65da1aa09c0.nq.gz
    ├── 2abf4b5cf29210ce6cc0f470a6c624afcdcb7cec.nq.gz
    ├── 2b263c5ace58621a420df400bb3591476c6deb9d.nq.gz
    ├── 2bde44c20d9eccabc016619e26494d131ce80b3a.nq.gz
    ├── 2c2f3be2492cdf42ab0c2c756b48b412a66f581a.nq.gz
    ├── 2c684681d0f3d405ba4af8f33ba10e2d61c6f52d.nq.gz
    ├── 2d78eb2db759403d6cfcaeaa17087a1825b33349.nq.gz
    ├── 2dab7783f4c2fc4682957b08d8cc909a733974c2.nq.gz
    ├── 2ea03bd0b5481f76707d8db1c44728aeadb685cb.nq.gz
    ├── 2f0ef9283a3603ab8ab22289f4c86f4f2aa1dbb4.nq.gz
    ├── 30110ebe053b8b8d32fb57201638f4249237e24b.nq.gz
    ├── 30159c2fb92e846b27a8e9c9b2dd4635050a1e47.nq.gz
    ├── 3067dcc41b3fec93b258d4d033b5e58315b7e173.nq.gz
    ├── 3139b8b00dc69738378af0601fe8c95c45174b45.nq.gz
    ├── 31e9d7bb6c6ba38fab77329f941945be13c3c794.nq.gz
    ├── 326bc133c1eb42a0f401a463fd692e76a278c484.nq.gz
    ├── 328b411506cc3b0fb7159fc36f2b992c81972b93.nq.gz
    ├── 333facea90648eafd0ae51d29116d1565f0eb906.nq.gz
    ├── 339e873d9b06e5f81ad5427927e9c77b426a05b3.nq.gz
    ├── 33ee6712ddb6a6a58c5532cb71f7dc03bd2a1377.nq.gz
    ├── 3416b5f845ba5c35e303268b4f8eed0a1579596c.nq.gz
    ├── 3458d322ffbdc76b4e29105c156ed1880b251ece.nq.gz
    ├── 34608fb94140612c758ec6f6e12b0c59fd7b8455.nq.gz
    ├── 3531667c61f98f37b191be63d20ca0f5a6068d1f.nq.gz
    ├── 359b26b9e0eabe6e9a4a3f6237a31811308ff4ef.nq.gz
    ├── 3618df1fd2af6a44cf90b6d092309f1afd16e050.nq.gz
    ├── 363c0a0b8838d8f9fea66b52950caab2789fb14d.nq.gz
    ├── 365deb489a15504563d10bbc12bbf2c8dc5124a2.nq.gz
    ├── 366593b38b3f2f226b29bc17042bbec8c4ba954e.nq.gz
    ├── 36ca4cca630e7e0aef89c5d7078fcaf283865d3e.nq.gz
    ├── 36e7ce93381663fc06e974ff87fc223ae5a4f2ad.nq.gz
    ├── 372a43b8cd45c78ad614d4d0327aac8343c711c5.nq.gz
    ├── 37b0513f6f6eaca90655009bfd2aee403edc3bab.nq.gz
    ├── 37ffb789c5d521d4c0cea167b1358ba0cb2e97e6.nq.gz
    ├── 3803021a80c4d338a20bb3d86c13a86a47ba71fd.nq.gz
    ├── 38c465ff5b6a89b6317af8f3f111eb96687a840c.nq.gz
    ├── 396dce05eaa66d46cc9977740ccfe7bdca0b6dc6.nq.gz
    ├── 3a1169ff9250df59e078ec2eb69c0e804020e5b3.nq.gz
    ├── 3a3b1546031078fb6101899a9fca1427a62e5f4e.nq.gz
    ├── 3a48497fdc52d85b550173f97f7d68dea64b5721.nq.gz
    ├── 3a4bc7f3147355704c6992af36d99e7f69fd301e.nq.gz
    ├── 3b82386af3fa7dcee0772fb381b5e2ec0b2e0c88.nq.gz
    ├── 3c083e68ca1b5462fd8b9914e3166c5667d9b9ea.nq.gz
    ├── 3c6c54ba6cce6d599b4e1a093e46d2102b617b60.nq.gz
    ├── 3cd9c322d3a3bf10a4b549ba3804b293b81b0d81.nq.gz
    ├── 3ce4ef6d62323b86162bdac50bf26368b0a527e8.nq.gz
    ├── 3cf12ed3289cc46ccb9b678c2785a186cc4f3c50.nq.gz
    ├── 3d7ecb2c1548c1e1869ccbedcb5a07130005e39a.nq.gz
    ├── 3dcc78de3ac1e467a68ec1392ce4282406ad6ef0.nq.gz
    ├── 3df9941d43e45263499700718e6cd17e436af176.nq.gz
    ├── 3e6dc013053f9a17d5ce9422789db47c33428463.nq.gz
    ├── 4044aebf048abd1abaad4e4e88747aea6004e8d2.nq.gz
    ├── 405067d74180e95c07a6375e26fcc85f19449f27.nq.gz
    ├── 413b3cc11fb1d73e45ef02a300890904eeebef84.nq.gz
    ├── 43bdffca5254b3faf3d4255c9859b9274caad694.nq.gz
    ├── 443d6293f2607cbb92943b5988a80935806870c2.nq.gz
    ├── 46747f37ecfb9536832ffd353972380aa19463d4.nq.gz
    ├── 474b6c18b33208a4c83f7e43f6e9936c3a7a3f56.nq.gz
    ├── 477a1d5f0ba034e7be0c570dfe94d2faa92e5f69.nq.gz
    ├── 47ac9af0fe3a9535baa09b3c28c28acddd455248.nq.gz
    ├── 47f832f87cd030d2d7391da270ed738aafd41527.nq.gz
    ├── 481a26a29f9709ca299d7452f032accac736c8f3.nq.gz
    ├── 48711302b5080dbdc4899ac3db1443f3226f62f6.nq.gz
    ├── 489e2775b9f1c61c8337feaccbcff9bcebd74225.nq.gz
    ├── 497743656d9f281e9b84f348cd8521ed7ac53039.nq.gz
    ├── 49a98d56cff1b008093923c39a500ea35ff7bfea.nq.gz
    ├── 49e089ec4a2ab65de6c832d53539d2235d74f8a6.nq.gz
    ├── 4a09c81e23ca735b7d235c71f9ed7feca8081af3.nq.gz
    ├── 4aa2365d2f25020b0b9af8e4f412da228c1ac632.nq.gz
    ├── 4ba856a0e5d337790f8825276cc5abfebc234c98.nq.gz
    ├── 4c06fbf36f87648c981abd25e4e63fd767e1b56b.nq.gz
    ├── 4c3254a6b85c1cbe8dc83c9ffed85d48f15fdee7.nq.gz
    ├── 4c42eb529fcaa01c7e37769c72deb9aa9ee4443f.nq.gz
    ├── 4ca784e743e400b10afcd282d2c6abe16071c36c.nq.gz
    ├── 4e33c7e9ff578e5b9b54e762d43d257a32f690b7.nq.gz
    ├── 4e3bf965343bf8eedef9e0c2115eb04f116c7752.nq.gz
    ├── 4e6916f4167894aac6008546e2b07b3a3b574b6e.nq.gz
    ├── 4e7411f98d0931831ebecdfda20ab8f4456dbb75.nq.gz
    ├── 4e931de3822d1649472df13a4f4761bd0d4b50b7.nq.gz
    ├── 4f144d0cb78b4c17cfd2218b9b5b93b7d146ca1d.nq.gz
    ├── 4f157f6976abcf35a25e880c995a1ef343acf0d5.nq.gz
    ├── 5050e0254744590d03ed775361e92540ff494f60.nq.gz
    ├── 5109fe3fcdae4b427ffa0044c755f9028bcb1e84.nq.gz
    ├── 520cdcbff0d71b7bc95ae9f65de7efbf707e2ecd.nq.gz
    ├── 5260568b08d82aeddc328c353338a39e7d808a92.nq.gz
    ├── 526461b30918beed30c64d6601ce683742bd6dd6.nq.gz
    ├── 52719efccc7b5cd90824b5336bf42f11ad8c0654.nq.gz
    ├── 5324cf7990c884e39fa71a8d565b54971f13d5a5.nq.gz
    ├── 53306c155f61668c5f76631be09b785704a8024d.nq.gz
    ├── 53388f10ea75ac4117a393eb8573b5abac1a4088.nq.gz
    ├── 5386c6cc15dfc9df6b35a1db6948079d58507ea2.nq.gz
    ├── 540a350036c1265b77a1a3476e61a56ba7723ee8.nq.gz
    ├── 54bb9dbc2a9922c4a17f8c8d6d172812e5d6f13a.nq.gz
    ├── 5517e8a1e02f6e2621ad5b660eb9eb37c9abed53.nq.gz
    ├── 5539f1ed2efb5fd0bd07015bd0a7b7fd3f91f6e0.nq.gz
    ├── 557450f83f160e781bf48a001f4e2b7d2a6db638.nq.gz
    ├── 557f87adebd3dacafbc43888426e3f5fe6089172.nq.gz
    ├── 55eba6fdb7bf9b6acf2f18a859a5dd2609e84bb5.nq.gz
    ├── 560093be5a137440cce0c200036d9e939a86c03c.nq.gz
    ├── 590d3753741f460655b2444faddf72adbcdaa43b.nq.gz
    ├── 5b6831197b7b78ed847c36344e9c21523011c38e.nq.gz
    ├── 5ba17b5e965b8fbbd09eda622096cec8852b1ce4.nq.gz
    ├── 5c6eb95cbbc39da4ecd6610ceb0e3e98efc2d2c1.nq.gz
    ├── 5cf85f18b91bfe1d8da0e5c2d55b37de6ccc0e8b.nq.gz
    ├── 5d168ced9dcf86ec5c5bf7138af503af5d93ba96.nq.gz
    ├── 5d817c6eefed2dd4a64c70021d9a76e6c0f2ab87.nq.gz
    ├── 5e67714a8e63c4eaf9997e0cd20dd2e432d65e28.nq.gz
    ├── 5f838f233eff8a15025075d73c5801351c703bc8.nq.gz
    ├── 6049b7a0634c72f568640ac3708b6d084c53262a.nq.gz
    ├── 60db56be59a6f475f0b21180ad45977a7e31326e.nq.gz
    ├── 6142febd6d45a315ebb055888d06d29cc6bde5de.nq.gz
    ├── 615e2aab93688dbcb5715d54a3a92cacf94be0e4.nq.gz
    ├── 61ca8c89fc942620494fe0ab4f4ead03a826db9e.nq.gz
    └── 62f741a7b64a7dbdcef45643ed99db18ac8d12d5.nq.gz

7 directories, 200 files
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

[beeware/colosseum](https://github.com/beeware/colosseum)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
