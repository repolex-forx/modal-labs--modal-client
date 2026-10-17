# Repolex Knowledge Graph of modal-labs/modal-client

RDF knowledge graph data for [modal-labs/modal-client](https://github.com/modal-labs/modal-client), parsed by [repolex](https://repolex.ai).

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
rlex download modal-labs/modal-client
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 47cbc08b809a4a6efd5e5f0f271ec67276fb8e56
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 47cbc08b809a4a6efd5e5f0f271ec67276fb8e56
│           └── chunk-001.nq.gz
└── blob
    ├── 002758c61d221a0bbfaa62c92c20d1989be8be36.nq.gz
    ├── 00be3072e56e4356c05f4270de2a3ebc77467794.nq.gz
    ├── 0174580db40aea3f8f2dbdf232b9fff89258dea0.nq.gz
    ├── 02409a4d202475769e805fdee65f51908ec9db5d.nq.gz
    ├── 02507449fb789895a26f4cfadea5b38ca0344b61.nq.gz
    ├── 0273a989730121f3896436d37b1e730bf2c19374.nq.gz
    ├── 02c75a3eee0ec22e03a8b9ac5c22f1a6172ea4d2.nq.gz
    ├── 02e44432b820b67afe885542ad5cb87d7cacee81.nq.gz
    ├── 0318d24d0d356e9d3f6db3e3f460c199698da45d.nq.gz
    ├── 038b480b622f5e43831dfab0bf2dde59547d7980.nq.gz
    ├── 039c57b717cf216d9d37019b846922173d97eece.nq.gz
    ├── 052f1e8e1924a13bd090008eb59cd702e4dfb33f.nq.gz
    ├── 05b6b8cb7bc14f16c78807a5db4079e17c1287d4.nq.gz
    ├── 05da7fc6edebedba09fedd14ca630c945b8ab75b.nq.gz
    ├── 05df19043b4f2ac196d77df84d28223023512dbc.nq.gz
    ├── 06097a3b8c7989f2eec0e8b8acabdecb9a397e41.nq.gz
    ├── 064b6d5dbb3386dac0bf8943af7a2b0f0404b837.nq.gz
    ├── 06e1bf0a1dc8741f372bd5c66a6f848d590c5ed9.nq.gz
    ├── 07ecae5bc858c76541684ee9762d519af775c96a.nq.gz
    ├── 080fc90e8b8c1915eccdfdb3082d3ed39c1208cd.nq.gz
    ├── 0834738be332a408b72b212360072370892e1844.nq.gz
    ├── 0869254deb8441dfa0c4312dbed5fc4029329248.nq.gz
    ├── 0878b32f4cee2f22f925bd26a80e75f60a24d5ef.nq.gz
    ├── 08cb3d72e7cc7b43d721e27b36ad90e1c5160518.nq.gz
    ├── 09bae014315ab4c59c35f0d01f0ad21c73c58e1e.nq.gz
    ├── 0a5621d09c7b64265dbe2bd564bbab593974087f.nq.gz
    ├── 0aae3f31235a6bb5fd3470a4e6653849f3ff1a6b.nq.gz
    ├── 0ba0747a6c65a75a10938e9116e441e46de7e97c.nq.gz
    ├── 0c87bb3e50c6e94cab5ba128781f229e3502719c.nq.gz
    ├── 0df5800ee7560d841a07fd572fa1b44373d4a8a4.nq.gz
    ├── 0f193ae68684db92d74db4ae4555cc09b2f8e42f.nq.gz
    ├── 0f42223bd237c4e711ade926f33e32d90111e5ff.nq.gz
    ├── 0ff6045ba6d13a3102b8390ef5f9db7ac376dbd0.nq.gz
    ├── 0ffcd47cad706352f217e79d5ab052e82bd4629e.nq.gz
    ├── 1013ccc79859b0cb062c824af0b336a71893e0f8.nq.gz
    ├── 1168835b439ec25e69dd8c44a9545d7be855903f.nq.gz
    ├── 12325a125c2212d47913b921a2fde363eab22e04.nq.gz
    ├── 124f164599af0f665cb91be6b113ac4149811dfa.nq.gz
    ├── 12924d06974b196025c97192a6c6e294815f4bd7.nq.gz
    ├── 134f67710bd48134cbc4921c982cd38f0a5f584a.nq.gz
    ├── 1351b20ec6d0b715b477fd8a08ca7941919dc12d.nq.gz
    ├── 140268f7e276fd701a9c97a5d33c5b2092818273.nq.gz
    ├── 1405b8b4723ced4410648857a718ed2f3cc91e43.nq.gz
    ├── 14217b9706a6af3961a9fc9c787142facc922b39.nq.gz
    ├── 1439dfa279d93236a7847dede885425de10c4b86.nq.gz
    ├── 14929cdef10c07272cbbfd5b82c0040b07375ef2.nq.gz
    ├── 14f581a5616675f9872e9ab2d513b67b3bb40cb2.nq.gz
    ├── 14fd83551b2e01e8e0b888d1b1d6f4f8e156810d.nq.gz
    ├── 152f6331cf83e5beb98996706ba3cff8362a9c54.nq.gz
    ├── 1571c691269d82cf2c85f8703cb0b94996a990db.nq.gz
    ├── 159bd50e6784783256ad00b8eb1499662f0d97f0.nq.gz
    ├── 165c9e84daa1138e5960f24768fe9216d25c3b7e.nq.gz
    ├── 1716371d2fec089d2b202d97e748cc204de3bb75.nq.gz
    ├── 1769beb03fe6e25002f9f2031f39d34365506451.nq.gz
    ├── 17c04333792f39377a884cec53af6531b88fdba2.nq.gz
    ├── 18cf315bcea6cf075c859121028c769f532b1900.nq.gz
    ├── 19af5a6d2db37f5a3dc99d1b3f43b791f872117f.nq.gz
    ├── 1a24f6299c384d90e674d7cbb6da7bd860b4f8af.nq.gz
    ├── 1a695060083550cf54a85a945c4dc2ed5797d455.nq.gz
    ├── 1ad90861ba44c349ab1dd33f848cd2d38624495a.nq.gz
    ├── 1af60e4243268938cb59b7ca95f72b5f608d8ca3.nq.gz
    ├── 1c4ef0b959eeb62dd095a8355789d17e81d4b9a2.nq.gz
    ├── 1c88f5c0d68976894bb3b69c23bdbb01137f6819.nq.gz
    ├── 1d218b3a70c8f9a6e03d5c3e41737f2e3c1e2e66.nq.gz
    ├── 1d83ed3d927f6b527122a68640ee6488eab7e5cc.nq.gz
    ├── 1eb3055feba6ba0ee28dc543d036cdf27325433c.nq.gz
    ├── 1f1377c024cca7974a242cd1b8741db8fbcf859f.nq.gz
    ├── 1f8f9c11113fd5c98d893e90ee23c5d4d528d7ff.nq.gz
    ├── 200a4a5b650635c7f2c1d18fcd957e36f0495bb4.nq.gz
    ├── 2096d5af4a7b7cedb9291d57728e1c5b50606d2b.nq.gz
    ├── 21563c77f001b2ef3d32222328ab027ad8a76b51.nq.gz
    ├── 216207cb8ad7b4782c5f86f1237905f1321cc165.nq.gz
    ├── 22206d0d8fd01bb787ae8cdefef9227fde7e50ab.nq.gz
    ├── 2291d7df3ed5fbefe4590a412d7d7bd86473e07e.nq.gz
    ├── 229ad39a747d1e4071f7c1a442131a05c878243d.nq.gz
    ├── 22bf7e8f00581a845c5240b922bfa006890e15b1.nq.gz
    ├── 23522933ab0b9d089a10041c2d3eb2c384479b26.nq.gz
    ├── 235c2f0a6d4de0f00155177a31acb60e09d5cf2f.nq.gz
    ├── 23acf22bd51ed3ca862dff76d26c426aa1796a86.nq.gz
    ├── 23b3631158b6c3cfd33493b39e4946985e0a044d.nq.gz
    ├── 2469c2d6d1cfe08d9cef9fa77d42f73b3c98f3ff.nq.gz
    ├── 24dfd9f99594486615364db7f06f2da5eb0552c9.nq.gz
    ├── 2570b3eac0c76286638957bc81240f1f9640f9a4.nq.gz
    ├── 265534849261ffd53c7c94d32ec81def9bc0e895.nq.gz
    ├── 26a4a40cd276790ff8bddfdb20016f913ccda3a5.nq.gz
    ├── 26d490e6c846c804f5d12ff2ca7bc6af6b53fe90.nq.gz
    ├── 2769ea5a60fc1491d4b9ebe1637867910eb4df30.nq.gz
    ├── 280b4e4ea77544ae466ba9939c57dc4f712aa9d0.nq.gz
    ├── 286434a8fdb7cb2e9bc239a773a8af3b6a9af5e7.nq.gz
    ├── 291a98d034dac895eafea0be420d1e97699153d2.nq.gz
    ├── 2955a57f0e3b2c659a9bdeb81f5d261292dc5c0b.nq.gz
    ├── 29a66e3758eccf7e8f90773eb2695bb88cc577a6.nq.gz
    ├── 2a862783530cb7c23576ee3ff3e85b921004dda7.nq.gz
    ├── 2ab206475367dd0e8ab48563c3c22c4267434344.nq.gz
    ├── 2b5229da0049c04134d4df8b5b9f469fb5602a79.nq.gz
    ├── 2cd98e6090d0a79db46b1151717c226b70b7145b.nq.gz
    ├── 2ceae91bf1808c8ff95c15278f78018e4dc16550.nq.gz
    ├── 2db86c585716cf71a39f3366d0a56edd56c99c71.nq.gz
    ├── 2db8771bc37e401ffcb6dfde586c1ff75c403901.nq.gz
    ├── 2dc3843f7ad6dc3773ae6c95301148a23737370a.nq.gz
    ├── 2e386c0944805c77b5e2d0e1712445dc13858451.nq.gz
    ├── 2e469aa54aaf21756ed77649d3b7c6a45c7a8116.nq.gz
    ├── 2e873abc64173112bb98cac59c1942ca80840acd.nq.gz
    ├── 2edfd1065e2672e432e65a1e78e6cc16cb561117.nq.gz
    ├── 2f3e4de825c959bde04cea8c3ccd1bfc9fabc95e.nq.gz
    ├── 2fa08a7fea92a2a84d3fbe357787240f9d5777bb.nq.gz
    ├── 306275b2a7f34ff89dd362146017bfc091193b42.nq.gz
    ├── 31030c1067a1044aa8fa6b966846852c896d8aec.nq.gz
    ├── 31250618965cbb83af94578dfad07de5b01b87fe.nq.gz
    ├── 31973a804a87298d541826e6331e7bc082a2f6fb.nq.gz
    ├── 31dfeb3b35b860ae74e1838adeb9da8367d531ec.nq.gz
    ├── 31ff6a5f8c160c9cc97f2fa6433fb312909edbcf.nq.gz
    ├── 322caee4089216190f65ee2fc7649b85a1160c29.nq.gz
    ├── 32bd10115ce15d3bec9a52b8fcf8a4eb652e7bd8.nq.gz
    ├── 32c7a8959284162d92020e36f5e835296d665469.nq.gz
    ├── 32edec3fe213bdabee2bfd717a5803fdc4f8c473.nq.gz
    ├── 32f0f13d6e3f39518ee0f73bdc852228ff9d22c9.nq.gz
    ├── 330673f1a74dde292b7a5d4b30842b762f048eeb.nq.gz
    ├── 3392187aa82bea159c53f95147efba7bbdef8bc3.nq.gz
    ├── 3394cffef7e7ddc70c1b58a6fa40bf202ac53483.nq.gz
    ├── 33cb877e2943d14b704d1dcd57cf2e9bc6bec9e4.nq.gz
    ├── 347fe7867941104a89a3f1b50687ce37cae1471d.nq.gz
    ├── 3492dab588af8866d16c8a3f227233e78acfc99a.nq.gz
    ├── 34a47c352fbe04fc9a7413d83a3efa895420b131.nq.gz
    ├── 3573a6877d0c47800a5c75dc9dd7b4a818b71bc3.nq.gz
    ├── 35d9b902c5722fc37d39cc4736317b243c10f07f.nq.gz
    ├── 3604ac4484511a4bfec82d8b18a8ea72e225c403.nq.gz
    ├── 3657361eb913559f6353f6c90b960662c521b113.nq.gz
    ├── 37475ee6ff8c9783204b5e2fb68ff66a2ec52348.nq.gz
    ├── 374ecc0ec2ac2ef7f127c020ce91e7001e1f73a7.nq.gz
    ├── 375a64149ec657f4fb314f573bd3c9b8fbf38c9d.nq.gz
    ├── 39640b6abb5488305ee0ad5eef327a7055bd82ec.nq.gz
    ├── 3967b6318596337c6fef72e0508d011faf47816f.nq.gz
    ├── 398063e3dbd653146ae9e4fabb0131c434851ad5.nq.gz
    ├── 3a8f9452961ee0036dd40b25ce6181c2ea625933.nq.gz
    ├── 3b32dccbcb854c7c473759411aced03c27476a6a.nq.gz
    ├── 3bc01707badde71435c54ffd90982e89d6b3d443.nq.gz
    ├── 3d37e4a91c9e5e939a5f0c4323a2b2989d411760.nq.gz
    ├── 3d4d47501e39687c73a9c63e76376e5096384150.nq.gz
    ├── 3dbc18dffd7aef2243eb51efe0b442cdcb2aafd7.nq.gz
    ├── 3dd5528362ca625604aec64f142bce2b48ef9894.nq.gz
    ├── 3e9b89e76941a80a52a9d95b5df4a1b996255462.nq.gz
    ├── 3eef9af6076673581003e87dda24674b98db18d7.nq.gz
    ├── 3f9af201bee23207aee508e1c71254bf5924ea94.nq.gz
    ├── 3fa0e7e831239ae4c6c6b6deb151fb1a92809123.nq.gz
    ├── 3fd6e36bb5e41f245feba7ddc35c717a737842ff.nq.gz
    ├── 40124ee8c27b90a46ea306fc3e5005e27d92a2c7.nq.gz
    ├── 404648b8c57c08018aa5242498f85029d7ccf64e.nq.gz
    ├── 40f9b2e7ca1d12c7d792676854ceb04ca3bcd179.nq.gz
    ├── 41ef55583157944d65429e130e8aa585ed29dc38.nq.gz
    ├── 42052b49c3e0c6ae42e8ec1e254da797adca94f1.nq.gz
    ├── 4234702ed8ac6a6cf200f985c1df55fa04c30de7.nq.gz
    ├── 42671f1e698739ee952f88fc9164badaee1d9d4f.nq.gz
    ├── 427abda34d20ac3fd09d5c21520a50a43f3ae67b.nq.gz
    ├── 42cb7a5be3c579a254388994e0fbee3a270e119b.nq.gz
    ├── 4332d01331df687f4ce7dff694849c502577961a.nq.gz
    ├── 434756b19a388fdd66e65945400b27a571323079.nq.gz
    ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
    ├── 43eb31e95c3d6fec7febc88f903aeab29f66991d.nq.gz
    ├── 43ebbe8d6989c6747d687ac3ad4f5cfeaf0cd27c.nq.gz
    ├── 443f1c02c6668c4f31e90a3b6e5481b717ee3fd1.nq.gz
    ├── 452f2cd23d79c58537addd30f2b9837f5a1bd568.nq.gz
    ├── 460b3f974dc7226726595119f6a89b28b7ea5107.nq.gz
    ├── 4684552141539f7729d44e160dc485f1d6cd2ca1.nq.gz
    ├── 46d336bd1ccf37e66aab59097921985a51a1e883.nq.gz
    ├── 47956ee26f0b6fa7f8f367e3a24970d3d2a0bc75.nq.gz
    ├── 48b785129434f7073d798878d7093942ee255e5d.nq.gz
    ├── 494f6dde1ddbbc69639f4b2be5b9eb20dab9969e.nq.gz
    ├── 49664b6cf72d288c507cf7b06bab468ac6fd7279.nq.gz
    ├── 4af8adb1dd1bba4a62c6d9cf246e92b1c10dbba2.nq.gz
    ├── 4c7fb6f1ac357e7256ea9abb677f669bc259b2b7.nq.gz
    ├── 4cec5a6ac254995bc3f10e221da335e57d01f682.nq.gz
    ├── 4d65a0c59482c8a55b139d0f6a2c914f1d36591e.nq.gz
    ├── 4dd5639ae2c0834d38b1a70f58c783070154ac37.nq.gz
    ├── 4e8df8545d65c72cdcf436de4a3cf34783a41c94.nq.gz
    ├── 4e984eae979072cce9c9f479eb164cc24749e985.nq.gz
    ├── 4e9e5012983b8005d6bab6cd09035f3a32b2b4ac.nq.gz
    ├── 4ecee6b241dd6b7aebee8d5a00849dcefbab30be.nq.gz
    ├── 5045ebc799ea3ab69ac5f5a57aa7402999d9691e.nq.gz
    ├── 50883797f067e4e71d283da0c8bc28deac19295a.nq.gz
    ├── 51278e18f5c3968f7f9a15a93213da8773b92cc3.nq.gz
    ├── 5213c98d1c0a0ac9a15e0f4d01752d87ba0ea667.nq.gz
    ├── 52ea466238863fb51399ab3057d6564f08295dbc.nq.gz
    ├── 52ec44a1c6609de24b36d4b513353ef5d3b8716a.nq.gz
    ├── 53f8714f0e540847faa4a55e5c6025949160f6e8.nq.gz
    ├── 541101c405cc8e9cc5d287c791af3c31560efe1a.nq.gz
    ├── 54ab9c4dfe4daa86c992e4559a8c68591bf4d483.nq.gz
    ├── 54c063175788e5c7ce9dda0e90709433df7022b4.nq.gz
    ├── 551d203e534f4888c049088e3d654bc898f62a1c.nq.gz
    ├── 5599cb079ac8c612494d7f89f6c6ef4bd8fccf27.nq.gz
    ├── 56a0eaeca9977c52cba61de819a58e58cb7cff5e.nq.gz
    ├── 57b762d929b326da6e5f9d721be75689399c7472.nq.gz
    ├── 583b2b7f3393a816707b77b5761489c64706e643.nq.gz
    ├── 583e58321cef10ec9871ebe33a45f58d760f93e7.nq.gz
    ├── 58bc9318051d399cac7fbdce3fbd53b4c32edeba.nq.gz
    ├── 595504927bbdadf99f0f0ed0fa19c10184114e4d.nq.gz
    ├── 59dcb4ce57f645e31a55c5fb88dafbc8d54c85ec.nq.gz
    └── 5a02e768e4fc03f2859ad655690e85740efee52b.nq.gz

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

[modal-labs/modal-client](https://github.com/modal-labs/modal-client)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
