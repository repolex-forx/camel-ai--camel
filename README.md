# Repolex Knowledge Graph of camel-ai/camel

RDF knowledge graph data for [camel-ai/camel](https://github.com/camel-ai/camel), parsed by [repolex](https://repolex.ai).

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
rlex download camel-ai/camel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e5e55256e9446f744bf7309c478b084587dbf985
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e5e55256e9446f744bf7309c478b084587dbf985
│           └── chunk-001.nq.gz
└── blob
    ├── 0050c461057ca7cde737a38b54b19a74b20a32d7.nq.gz
    ├── 0065ad478c5908eb91d419ba9040c3fbe178eebd.nq.gz
    ├── 00c988353bcdc25802c5460c89061577f300223e.nq.gz
    ├── 0109fe996fb724a5950b65e29a4a44fed058080f.nq.gz
    ├── 01186b2a218236907ed133d510ebbed37d08f5d2.nq.gz
    ├── 015b8b963fb1dde394174a263a111fc24323970e.nq.gz
    ├── 017e2effb9347fab09e733d964bcf629f78d8ed0.nq.gz
    ├── 0184bdaf1b7c8be6a6240968dbb00a258ae06a5f.nq.gz
    ├── 024e409bb1a19d6f83e27be356247386469ff457.nq.gz
    ├── 0272dd38579e282dd00853eb1603e62b2356a856.nq.gz
    ├── 0363cca7ffea52b9dfbe816b3d1ef600fbcfa2da.nq.gz
    ├── 03ab41f8e3ee11f41c1ec2dcf6bb5bd7350228e6.nq.gz
    ├── 0441ea7db4b87f9d7847ac2636b7532e61cad153.nq.gz
    ├── 046016b919fa90883a2b17f00f052d3f57bae4a5.nq.gz
    ├── 067eb362db5ed1d4a065d18b817893b4642bfadc.nq.gz
    ├── 06df1916348fada8fc2125f89ebd6cc7833d8e74.nq.gz
    ├── 07c373c2259b98a78dfd4df41571b85821f1825b.nq.gz
    ├── 09552895a39dd89cfd11729de5fcc047c48dc60b.nq.gz
    ├── 099c611a01903ddf705a9beed41fda4653fd1237.nq.gz
    ├── 09cf637d7fda75afd39380b0110242cfc59e1a91.nq.gz
    ├── 09e13bd9d3dc1ea842ae84c3da19ff3067b1518d.nq.gz
    ├── 0a06bfa2d1a7311e01f02cfed854e88a53af601b.nq.gz
    ├── 0a0b3548b42f801b0ff8ab571946dc4600ee1bbd.nq.gz
    ├── 0a80184eaaf8b97ff32a69418e0f2d6d67ed465e.nq.gz
    ├── 0b023cfdda4118dcf5965296d9c3a20e40964ee3.nq.gz
    ├── 0c34a38e0fe75574cbd49932b3013a4b5a88863f.nq.gz
    ├── 0c8c01c2cfb34322f98ad4d27ff268cc63c4a915.nq.gz
    ├── 0cfe080faaca7316ee8b70370698e79bb4dab759.nq.gz
    ├── 0d16d65c2e8fdfe32999397bde1b1ee384e1d299.nq.gz
    ├── 0d891ad4603d194c9b2fa4982406a1ce8a9a98ab.nq.gz
    ├── 0fb50f864ae0f3f25663d1bfbd1915f89c1d46fc.nq.gz
    ├── 1023c8359a63deb7ce411e9d8fc50625cf261e12.nq.gz
    ├── 103d76ac7b120ccd16084809641702493489c50e.nq.gz
    ├── 1120685723aeb7fcb9a79a85d1c3f2554f2de43f.nq.gz
    ├── 11651d6c7bad065b3cd24761b34cede4a84a2fef.nq.gz
    ├── 117c2a68460ee8a1fbe5126d7dbd6465cbb3b039.nq.gz
    ├── 118a59bc1c4ec05ede867c0c88610affa631b8c9.nq.gz
    ├── 11982c0a1b0cab1f4a7d83278d9cac8a149dca17.nq.gz
    ├── 119a20cbbaf1e4216fed946034d34749719196aa.nq.gz
    ├── 129c1e1da75223193968f74ba88704cb26e685dc.nq.gz
    ├── 12bfd4236e2e693007097dbb93f3080a152bff5e.nq.gz
    ├── 12cab86179b1f9168f33b18af16f970538b7fedc.nq.gz
    ├── 14885ec3bd56f669a0317aaa18b25c2515875152.nq.gz
    ├── 149f63b2fe36ded4bd304ef94ac92cf66b5d861d.nq.gz
    ├── 14c8111caf49df86bef745cfc58caf933be69ffe.nq.gz
    ├── 1512b9fb8519dae6230efacf4a28439d17a3404e.nq.gz
    ├── 15dc954656df2bd5001113e3b7191e3f586325b7.nq.gz
    ├── 160f254f87a37aaeba48c465f2f1519045a99d09.nq.gz
    ├── 161c39f78a394e120e2487e4e10ec951ab7995df.nq.gz
    ├── 1683e1a3b69ccc788ef830eab779a603332e98a4.nq.gz
    ├── 16adad21ade3dcf44775f1b7d14a003786ddb98f.nq.gz
    ├── 170ce79cb7a5a5c9119ab53ad64d4e1bb5a68694.nq.gz
    ├── 17fde6194a00f71ffc31549d2ec912ceecbd5f81.nq.gz
    ├── 197380b7067a3e6b5ea706b66d22cce85a853d63.nq.gz
    ├── 19b498019c84a90eb080332086341747954b4376.nq.gz
    ├── 1a6d363259a1850676f378653dd7759c0c20207e.nq.gz
    ├── 1a749bd897d100b0916175cc62915939836ced98.nq.gz
    ├── 1ae706753eca5583d0860d52845e84f6577489e7.nq.gz
    ├── 1b4d2596a1878eb033672b234889f5a601f22a80.nq.gz
    ├── 1b5787803b9101b1fe29aaa93999df3e09668751.nq.gz
    ├── 1b8719910c193563d0e53bec3067f968f67eb78c.nq.gz
    ├── 1c66e7ed05444f2ed1b39eccabf43ed122ea2c30.nq.gz
    ├── 1c802a5502f189112fe8e7fcfe67865dfe7f9b4b.nq.gz
    ├── 1dc7b7be819fc3c2c0cc6ece084fc39272bf5a11.nq.gz
    ├── 1f256be514164d68a7471fcd1a7c2b3723046647.nq.gz
    ├── 1fd7596a2008601d30c3c58fa2c01c98c34f98c9.nq.gz
    ├── 1fdce43541279ee1b0327039ef9b8c7e60e9b1f2.nq.gz
    ├── 211ddd9cf2de396f01550498f1c094d8b187367e.nq.gz
    ├── 21ec4e05f468dfd81c4b9572fddcf1c9ad1d4d81.nq.gz
    ├── 221f569e82c7abb98871cde4035124a48c217815.nq.gz
    ├── 22b7546eb60b7fdb7bc2a7dc4e5e87141ee206a6.nq.gz
    ├── 230b9b1a1c21e05d02a1ae40b083dd8301294c41.nq.gz
    ├── 23c79d79b3cd010b2aca97a17e369aeb3736c871.nq.gz
    ├── 23e2af4bd4dab5ed059c02ba95d9d731b0abf3f9.nq.gz
    ├── 2411435886e3889f56ab121350396457e14021ac.nq.gz
    ├── 24d649d2cfa9c26c16e0b9bc644e50b0bf52f396.nq.gz
    ├── 2540f6c2f9c106ffca3e5c1a29f2192bb6b46f9e.nq.gz
    ├── 2681b76f7911f2130497e0c95a1bd52df2b614d2.nq.gz
    ├── 26cbcd0f3dc28c32014042df37857f551723b034.nq.gz
    ├── 275746125e676e499507c141864f18f1b2d562ce.nq.gz
    ├── 285d7497e0321a5cbd62964c6ea5294d33d42e6e.nq.gz
    ├── 285e4274e1da8d2ed960c63b67f36a300329a372.nq.gz
    ├── 295dc4543e50ce02e6d9d1583a74ce920b89650b.nq.gz
    ├── 2b5ee03aa5a2486b04b252127aaf9712df495ed5.nq.gz
    ├── 2b7df4607bbfe7016844f892c6d0d627667bd314.nq.gz
    ├── 2d2545302d99c744e97acb7867bff0322d2dc979.nq.gz
    ├── 2e1667eedbd74da4d40b1b8d539ef0a21c4144b2.nq.gz
    ├── 2e9ecc4fd84abdd12ba475e24c8a76ab4c95ee6c.nq.gz
    ├── 2eaf49584e601ca17adf8bc1536a1d953732310d.nq.gz
    ├── 2ee0c963ae3a1c7fb19280e2bf0d5caedddc2033.nq.gz
    ├── 2f12ccf35fd3d85fcd4b1875194410532bf435f9.nq.gz
    ├── 2fe0ee9950e8c9936f4f8368f1f59d20f22b1767.nq.gz
    ├── 2fedb6cf603eb84aabf07ad56711b439aa4ae301.nq.gz
    ├── 2ffbb00310d48ef6038dfd4f3bdcfc5662624be7.nq.gz
    ├── 3181ce8a7ed75cf4ac42fc472cf8287a08846a31.nq.gz
    ├── 31b230cb11956be0f023e95a74f36c5d85bbfbeb.nq.gz
    ├── 32d48b5222e680c2e6c63be4e736e48aa3a09149.nq.gz
    ├── 32d76f744fa1fdc78e365349cf930a221c717b78.nq.gz
    ├── 32f0f057b9fc6b369b0886d4391f467c8c1a23fa.nq.gz
    ├── 33434c7cbfd5a56337a33c73e7253ac8d06d57b1.nq.gz
    ├── 3390b4aa2402b528b6950d52ad42200563222547.nq.gz
    ├── 339fc6780d591149686012d72a3f99e71c5ab698.nq.gz
    ├── 33c48bc45beeaf385da7e2b80e6c43ccb5e55816.nq.gz
    ├── 340b6a188225a3d84943e844680df1dbe158f1c4.nq.gz
    ├── 34af069c742f1f977669de8b4a3646118f10ae61.nq.gz
    ├── 3574c1f81b47ec21c9fcd7f1d7da1a0ee0e75b15.nq.gz
    ├── 36080aced2cd83dc84bb5e7bf8b616988826956a.nq.gz
    ├── 3644914d95293b346c956ec45259bdfe3fa49ec7.nq.gz
    ├── 367ffe4d62f1fb62edc4329f28e96b9db725f802.nq.gz
    ├── 369ece5690c473f0870be9c7e66f796fa32c5946.nq.gz
    ├── 36b1a1819eeec283ba3593a28259e1a8826da505.nq.gz
    ├── 36cd7ec108cc6601240fc956127b4f1cf1622e9f.nq.gz
    ├── 3760641152a598bfd19240c2d3753c4c6cae3982.nq.gz
    ├── 376b2e8dd3f18055ac2ecc20904d8bbd97406e9d.nq.gz
    ├── 3784f8e881fecaf7f4320ba7668c27dfcfe1e959.nq.gz
    ├── 37aa20d9851e045f102115bdc80f176c3d605a74.nq.gz
    ├── 37c1f19b53f8883ccc9b8bc7704afe2df4c8028b.nq.gz
    ├── 3850509cc7e36f06d26cf85e64b364dd0744bbb8.nq.gz
    ├── 3904a7be87db3cd7db1ed83c44dd5a0db4d7657f.nq.gz
    ├── 395260248e5b62533f3c84192916c86233c2d9c0.nq.gz
    ├── 39bbb7ce22b64dab713c69b749cbfcee7626f655.nq.gz
    ├── 3a0b76d47eb12d2e970c88c90dbacdace12710c1.nq.gz
    ├── 3a0f80b2d5398396e2010d7eedfc252080e3ed48.nq.gz
    ├── 3a4188de4e5144387ebc0469657abdb51bb2de7d.nq.gz
    ├── 3adca25f44ea6f13598428f5d955fd40940b56c5.nq.gz
    ├── 3b172d343ba2159f1fa6472baa705fa4cbf734e9.nq.gz
    ├── 3ba46dc536cd25e79a50ae818f1bc99940feb8cf.nq.gz
    ├── 3c3f81a8c0aef830b8b372e882692aaded48517b.nq.gz
    ├── 3c5716da913778cb72ab6e8093acd449593f94a2.nq.gz
    ├── 3d8b8c3d3c4938f1814613d3cbfb539baf357617.nq.gz
    ├── 3ddde463d11df2816caace0f5ab5990954116412.nq.gz
    ├── 3e3f0a69b000b9b24a0ac0447e953420b13dbb6e.nq.gz
    ├── 3e83d0961c7c571f7d4236551b5879b46bc6fbd3.nq.gz
    ├── 3eddd140b45d6c0ee8702f7950c69bde008e7db0.nq.gz
    ├── 3ef2417fe869eeec43d1d533d8a05085a9294387.nq.gz
    ├── 3f3a438db68a95f76b347c6582e529399489d6a4.nq.gz
    ├── 3f8df9b311a3a96972a6450c2e6e57d370a45ec6.nq.gz
    ├── 3faaf4f0a7741cfa84a3441e754e2f0053eb5076.nq.gz
    ├── 4078a94134491513eafb875c36a3f391fa3cce67.nq.gz
    ├── 40973567d246485bd100840e70c666cd66a67bba.nq.gz
    ├── 41462bba816135c92844a39cb1851f015e6316bb.nq.gz
    ├── 42249ad03ad8a497a38ab9976376866abd046221.nq.gz
    ├── 422b9b4b6ecf4c1ff2c89ae6db170667ea48fcfa.nq.gz
    ├── 425e9b041be3f4f8b18f5172321f05db5c686783.nq.gz
    ├── 42fa12c7152d8c643f6eedf79dce93729858f5d8.nq.gz
    ├── 4360c320827399f2f1b20f2db5b01c6349e05b59.nq.gz
    ├── 449b604f31a11861ee27ecaa1b4ecbb20de8a30a.nq.gz
    ├── 44b3092c3cfd6fe4492b624de6f217abea309069.nq.gz
    ├── 44ede26d5913c3ace195dbd578351ca220850ea4.nq.gz
    ├── 456db4afb7566e966766c5794b63ef685fec478e.nq.gz
    ├── 45834771d910cd08e545fdb4f2b10e73ea48b70f.nq.gz
    ├── 45b96d038ca12b0131346deed03b1e412323e364.nq.gz
    ├── 462fab14ca7d556be9d020124913be1ac53ebdf0.nq.gz
    ├── 464d242ce2a1296bc5e3643511528f647a4e4479.nq.gz
    ├── 46cc6e080888e530ea864d948cd852bb198d044e.nq.gz
    ├── 4938b5e0f916c5f444367bf1fe0be7be1f1c4237.nq.gz
    ├── 4954da1c545eededc28974b47bf696c61258f6a9.nq.gz
    ├── 49b897d049435e1c24cf0f41f41f9368ecfb0c36.nq.gz
    ├── 49cfe6708e5271f6a7f93d35474a07c4b5393df2.nq.gz
    ├── 4a1975654fefd276267668b07495d620194e6906.nq.gz
    ├── 4aa5399c085e844eb169c4575315d22fa587473f.nq.gz
    ├── 4b5a5f98029029daf7e853d6866ece43d1e95a4c.nq.gz
    ├── 4bcf3414427e4e0ac6ea47cdc53688435af25c01.nq.gz
    ├── 4c1c6e0f85cfdd8272d3214786af87e58cf03c98.nq.gz
    ├── 4c21db1ecb74aac45041d3c02256890d66109f02.nq.gz
    ├── 4cc64c77a472e4cf8179e2ebed5b76c7bcf5c6d5.nq.gz
    ├── 4ce5829a9f4a6e6cf480940edeeacc82e747f5ca.nq.gz
    ├── 4cf4aadb7b5a74ee200e7c5385011301ba2772e4.nq.gz
    ├── 4d4b7837dd3b349ff72612e8446d6b55fe366efe.nq.gz
    ├── 4dbbc324dbfdb4688d904d2484a5195100d8ddc4.nq.gz
    ├── 4dbd67ba1c0b6e43adc4167c0f2f837353a3da95.nq.gz
    ├── 4e4192d58e72616b96d318323ce36e65183e2bfa.nq.gz
    ├── 4f000c2548c292c8fa7780e65c2dfa3f87cefda3.nq.gz
    ├── 4f31acf58264a5ef2bd42ba7859c0212471497a9.nq.gz
    ├── 507766a3e91258904a039a9617fc2786692661ef.nq.gz
    ├── 50c488bab6b0053883f86b91cd23a66fbef9255f.nq.gz
    ├── 525e248ad1bc1c87f2a036d438da03296864a991.nq.gz
    ├── 53564ee1e5da59ecc83633aec7bf2394e72c3730.nq.gz
    ├── 53a5fca5595618525e9adb79b38fe4aa2eeed523.nq.gz
    ├── 542bda7a92bf618a9cccb7d8449cfecbb0eb0d91.nq.gz
    ├── 549179e7c729a44c6ddaf48d7b836112ca4823a9.nq.gz
    ├── 54f1d1f6aa63dca70d95e9fc048016d9caaee1b2.nq.gz
    ├── 558e34fe79e25eda4f666d8b1798b16b470ecfa9.nq.gz
    ├── 582d82539fc1df44f4e0e5275bff3146badfb206.nq.gz
    ├── 5834f25db778e78ac765b4cddf367f34933c91b1.nq.gz
    ├── 5979092ca9aabb949d8e19eea8c4c0230ae6cc44.nq.gz
    ├── 599b69bb910916b04f9a825ab73c33b4d3ad4854.nq.gz
    ├── 59ea78d68bd658b807a4e601cfc122da156a146b.nq.gz
    ├── 5a2c20f6a8a94038eb84f9213a65f60f7f990eed.nq.gz
    ├── 5a38ed1492e50ff6d905915860f7671ae180cd8b.nq.gz
    ├── 5a3c9260d84c3dc36d68983443e368dad905f0e0.nq.gz
    ├── 5a5be87ddf5ee59582d124c2b7563bf2b8062687.nq.gz
    ├── 5c142b8de37e6aa41905bb393ce8c310ec2c8965.nq.gz
    ├── 5c9a190749a7fe8693744b4b6a50395f4c1b736c.nq.gz
    ├── 5cb3a0c2ba2656404648374ae50bc2d2b714f249.nq.gz
    ├── 5df68548945892de53dcc23351103d1e70c7ce87.nq.gz
    ├── 5edec2e5f707c42386ea7e283bba90f0c27ae24c.nq.gz
    └── 5f4031084e3b6f552b300a49f644d1cd9374b8dd.nq.gz

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

[camel-ai/camel](https://github.com/camel-ai/camel)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
