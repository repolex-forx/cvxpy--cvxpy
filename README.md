# Repolex Knowledge Graph of cvxpy/cvxpy

RDF knowledge graph data for [cvxpy/cvxpy](https://github.com/cvxpy/cvxpy), parsed by [repolex](https://repolex.ai).

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
rlex download cvxpy/cvxpy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ccf24bf121a2b4c5ffa5df0d4a8e0ac1e26fb813
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── ccf24bf121a2b4c5ffa5df0d4a8e0ac1e26fb813
│           └── chunk-001.nq.gz
└── blob
    ├── 003d7cae13ff0000d0c17bcea40d93f79ad8e21e.nq.gz
    ├── 006d72d04d3a88aa6fbfacf298cb12a5234c8b0a.nq.gz
    ├── 00eec80875fcb209de0f6f746d0f4d299cd2ce8e.nq.gz
    ├── 0107bcedfaf01fe7146099f018ab3dd26a061443.nq.gz
    ├── 016874556d0f65c532c95cba60373631a3285166.nq.gz
    ├── 02f0a77250811be978027c6dc15453a931b74d52.nq.gz
    ├── 0348b41db05b7dcc88432b34c77c8aba97c35c5c.nq.gz
    ├── 04462b98022617e728931407d9349a5e99669dc8.nq.gz
    ├── 058ce4136c85a6779ad80fb1eef2f568cc72aa9b.nq.gz
    ├── 06d6099842300c55bb6fe4ae01ad15d477d73812.nq.gz
    ├── 06f1a0753c2f915660cd761e1c2b70537fae267f.nq.gz
    ├── 0726ca1c5605b4ca0e6db8a86b8bbef7c5b7598a.nq.gz
    ├── 0797a1ed1370c6a5f215bb48cd7c3307a0336e56.nq.gz
    ├── 081e918f1329b162604fc5bf9a36302feaa479b0.nq.gz
    ├── 083798590d7630d433811141d29b308ee89d1a34.nq.gz
    ├── 086c7ac4898541bec9916b0a1675239b7308b975.nq.gz
    ├── 093a9adde8ecf59d0cf1fe48eb86d56e2f6fba57.nq.gz
    ├── 0996a32482ba5e7e1a75c3e622f1a3e106f01c28.nq.gz
    ├── 0a12934e6c0c9f0b73f822e60c8bbd560ad71baf.nq.gz
    ├── 0b83027f23819b34d8bb1b8334e2f686d856da78.nq.gz
    ├── 0b9b33d99dd9c03296521e33eb2fb7986ff003ce.nq.gz
    ├── 0be293d17fa51110a211fb99b22ad3e8c67c4560.nq.gz
    ├── 0bf62ab5788455d3b65b13dd5bddc3b089cf45fe.nq.gz
    ├── 0c8a6d9a99122f66723060be46ced3a3328994bb.nq.gz
    ├── 0e07b20b95d74ae3cf3f003e8ab0bbf0d7387c1c.nq.gz
    ├── 0e3b7c0874201f738fba73c248954f27cb632c52.nq.gz
    ├── 0e5f43002eceb4ef12fe2b5011c674bc273cc95f.nq.gz
    ├── 0eaf3035374cac0a070f2b1e785e76dbfb4071c9.nq.gz
    ├── 0ec57a0794f01e498c6424a0110f5512856f622a.nq.gz
    ├── 0f4adcd4739f4bffba92d64f21e69b69f687d2ce.nq.gz
    ├── 0f522bbb766b4a8533e4c060cb4499d9c6075cb3.nq.gz
    ├── 10856ff5e5d3fc63bf79a112b2baac4c4d8ef2f8.nq.gz
    ├── 1135743a9cd47b85ebacefb0cff608cf87c14fb7.nq.gz
    ├── 118bf763763efb204d8e069e4dbfb77fddc7f424.nq.gz
    ├── 11a240e3e034e24748c80367ed69915b8bc768d3.nq.gz
    ├── 11d8ed32db6bd0064a704372da91acaabe2d5cfd.nq.gz
    ├── 11da1b1890652b648b23c3593eeb9877e72e2df0.nq.gz
    ├── 11ffd47969d2b06999b2a53cb8c35798657c6f30.nq.gz
    ├── 1202defc5d045840bc28d044f93b2f5cfb32f818.nq.gz
    ├── 1236ceb04676f5e180b589f8ca70c3d9362710cf.nq.gz
    ├── 1238345e3fa24974576865db091701ccf2973eb7.nq.gz
    ├── 13c55f4b115880c0becb6246bdc1fb86c9f404fa.nq.gz
    ├── 14692365ffbf3a53eb67c0d64a961e098d14578b.nq.gz
    ├── 1485e7edcc808575fe4b9dda92b77d52f1a8d768.nq.gz
    ├── 15c834c6a68e8869471c81b1006baa637393c4a7.nq.gz
    ├── 16f5c7f81820ac9020351037a64ba59d0d623812.nq.gz
    ├── 171cc602cfc745c490e218633527a8247d9ab68d.nq.gz
    ├── 17963fad4d42c979c928b053b45fcb3b099b30f0.nq.gz
    ├── 17f8e44364ddeb2ddcf41ede841868f10595504c.nq.gz
    ├── 19712eee23e1e346b1705fbf8e9923a2dba24943.nq.gz
    ├── 19b734ca7e002da98e829e666340bf847245ef53.nq.gz
    ├── 1a127f81ea2bbcde2dbe2fb28e90bf0f93348de9.nq.gz
    ├── 1a98f4d44f234f509715966aab23854d203ad981.nq.gz
    ├── 1b5d1b897c207b44a3173908caebe2942b1f5bde.nq.gz
    ├── 1bda5b0c80e73f11f36bb600f4d0f9875e850c0b.nq.gz
    ├── 1c28f4f95e42f86265803b922a81bd89a8e8659b.nq.gz
    ├── 1c7ce0c11527f245988119f1676f3b5f15c19a7a.nq.gz
    ├── 1ce6fd1b00979ad42bbee67372981a23a05ab8d2.nq.gz
    ├── 1d6082ffed4ecbfc34f707b0eb22b68edbdff83d.nq.gz
    ├── 1e47a075d6c666ad590df968f310933c66232f15.nq.gz
    ├── 1ead3e2d693dd9a8c8bb24b2ab3c5f0cc81eb40b.nq.gz
    ├── 1f21139346e7394b6c522dba3a4368125232fa99.nq.gz
    ├── 1f55a90a5cd83da1a5c2e90e9da4ff3ff6246757.nq.gz
    ├── 1fc19ffa1d61762a53dc9ef6c97b5ce29ff79228.nq.gz
    ├── 20c789b10c760d814516c65f539cfefc9e352f0e.nq.gz
    ├── 20e0cddc7218494caeda62a58485036b8a06eb24.nq.gz
    ├── 215db35b03f3019df6f15df235f58e2486042c06.nq.gz
    ├── 218660afd55c3e1973b4b1415ebb3fc3f4170bb2.nq.gz
    ├── 22c6401693b35d58f45eff3d68317e747d27c693.nq.gz
    ├── 230d022978da1e831ed24f291f553b34eca644a0.nq.gz
    ├── 234619accee0e875a418eda983f870b25255c17e.nq.gz
    ├── 2360d5bda0662c05452894d926634fe787c4513d.nq.gz
    ├── 2376c6c0996594987afd77519f5421cdecf954cf.nq.gz
    ├── 23bd1880ed361c676ccfba62efa47371f2d73d86.nq.gz
    ├── 249f3575c6dd912ac9a52a932d2e68010e523a63.nq.gz
    ├── 25066d4a8a76a5af5f23e64ae8a663d3e7b004a2.nq.gz
    ├── 265230eb0a173ee5c9781cfdd7e418d270e4e65b.nq.gz
    ├── 26d89fcb88a8853223c14c15fc4a1dd4189a62fd.nq.gz
    ├── 2724e9186a9d9c22be2c1a8145b4dabe044e4687.nq.gz
    ├── 277657f5364b5a6ed843dd3eeddee14c873f6101.nq.gz
    ├── 284af9536c90f7ba8ddf74875177ea31c65cd475.nq.gz
    ├── 289ec510a8ac733646e6f5915fd35fb8812ef559.nq.gz
    ├── 2998fa9adf8d11d0d4989c45dc025d75e431f41f.nq.gz
    ├── 2a3d9de244b1b574ccac3800bb5cc083bc16eb21.nq.gz
    ├── 2a8c93ba8bc2127d82591a3a6aaf95f6ade00228.nq.gz
    ├── 2ab0f2a76b7a1a2c4c4d9ad5073fd30ee970128b.nq.gz
    ├── 2ab988ed96d014932a4d3e1b91f580323af903fd.nq.gz
    ├── 2ae33f88392d3fee5d226372369f73565b05086f.nq.gz
    ├── 2bf0a2bdd2b1f903d866bc1b4920f407c8fcd8f8.nq.gz
    ├── 2bf0c1ffc4a27651092faa72725444b0dfde8f6e.nq.gz
    ├── 2c47eccef537a4c138b7a21ab86c7f65de544cee.nq.gz
    ├── 2d628eacfb2043815326f5eff1858b7f137299b0.nq.gz
    ├── 2e0a0bd24f02a0b4f9fe79e3bad2de01907c0d84.nq.gz
    ├── 2e313e31442318b4a54551562567238e604aad8b.nq.gz
    ├── 2e9555b5374dc723aa181d30194056c05bc96e18.nq.gz
    ├── 2ec24180fc87ce715f980d084d34c4295edf51ad.nq.gz
    ├── 2ee1fdcfd1c6833d735a7039c4f4cb39a9da8c23.nq.gz
    ├── 2f6e52f86deb18cecd2acc3a1c8cdd6c06ceaa5f.nq.gz
    ├── 2f9cc449176fb2ea3cbe83d9c8dc2441153fdfc4.nq.gz
    ├── 30229da3c38ba743e5c53bd2676e77d9dd9ae9f8.nq.gz
    ├── 30c3f23cc0d7b1cbb96f74695be50003341d7254.nq.gz
    ├── 31b34751b103adbd30f9f5d1470eb99caa1c73a8.nq.gz
    ├── 3206d6633e62c29f4466155f47725511a34ba640.nq.gz
    ├── 323934507095bd32045c37e62eac654939f9b574.nq.gz
    ├── 32574b5257df431256da5cda468afa93b0f74356.nq.gz
    ├── 32b0c635b8aba0620087e0fd7ebbf298bff02a33.nq.gz
    ├── 33ecf10f610d4515edee6402360a34927d8abf2e.nq.gz
    ├── 3481f337e374c1fc3eb0b9e780ddb02da963a9e5.nq.gz
    ├── 34ea0d07cda93cf459c44a99b45e32f53d0abc82.nq.gz
    ├── 3627761f571eeaba16b584334ef2d4b46a95d6ed.nq.gz
    ├── 3660c6f66464e549d5237ceff0cf858e4bd4fca7.nq.gz
    ├── 37426877ad4338463f796209fe884b5fb3499704.nq.gz
    ├── 37e3a2512a829af9a2836f92150de79922b075f1.nq.gz
    ├── 37fcdb59119ff83758ce004d7526b69a73dbb275.nq.gz
    ├── 38bc4aa9ea01f508488409d1de71a9fdf82f3a02.nq.gz
    ├── 3978953e12f92db94dc99da14a86ceee01daada1.nq.gz
    ├── 3a7a329361eea0cd6ba25b81d663a8409ed70384.nq.gz
    ├── 3b6742ff5522720d4b76cbc1391d8c4cae6016dc.nq.gz
    ├── 3d47a2b94cbc22de5a5295c38e9ec5bdbf353930.nq.gz
    ├── 3d71296c025d5e2a536e9de625329d762107d5ed.nq.gz
    ├── 3d8e24f5a2ea640658a65f70f21f656c40185fea.nq.gz
    ├── 3de33e58d5981a2106bf7e14f8ed40102b6ea159.nq.gz
    ├── 3e816756135b2cbdeadb4d13a64fc677196c1acb.nq.gz
    ├── 3eaba5300214ca5b0bfd9dc923cdb50e7c0116ef.nq.gz
    ├── 3f35779918ef38b17b1dbd5f9c2bc89cf3cf868c.nq.gz
    ├── 401d318b549243079339f922123ae43b6df20a5f.nq.gz
    ├── 40310902a01bdb2f7d97fc53c48dbcab02c1bee4.nq.gz
    ├── 40cebf54e509a60510a93b825948d7b99ff9f6dc.nq.gz
    ├── 40d0b776c69b864d313af59a8adb291a79714dd6.nq.gz
    ├── 40d52ba1224213e0b488db3c474695a7508a0f2c.nq.gz
    ├── 40dd7649008fa0e0cd8f5c6ce3eee050b5141bd1.nq.gz
    ├── 419290ae9d014f4c71751419ae6f89e5ce18fff7.nq.gz
    ├── 420ab240cc068df3d5b9ed6e897b500bd960f802.nq.gz
    ├── 42732eedd5e4846436130855ca7ff8be1d0e7471.nq.gz
    ├── 42c045b6666be0c3fba1e1349f73e2200b1fe8b3.nq.gz
    ├── 44092c77e60727497017f5df1a5d6b0d1c4d011a.nq.gz
    ├── 44874d8e45db92bbe8a79372271570c628008832.nq.gz
    ├── 44c2018ea1f1bd35514f6072f607892e0e3a77c1.nq.gz
    ├── 44c4c87b563ed7691757ebcf20d9cc5b53a0afed.nq.gz
    ├── 4570c9b634bd920753aa4d9ab063c4ab49ab4ecd.nq.gz
    ├── 47414ff909dce26f10934d6ac99940abf5854c32.nq.gz
    ├── 482a6b045ef5a530517f55785b2ce27b448595d8.nq.gz
    ├── 4952c6633e59c77d3e752969a1eb4cbc91721c43.nq.gz
    ├── 49760a9b7d12da920d28177ba7f7c82cc7762025.nq.gz
    ├── 4980a3ede0ad4d159bf87cbdc1b5abfc003f32e2.nq.gz
    ├── 49c72b3f1c626564482500066d90fdcc2da406ef.nq.gz
    ├── 4a2b238b9737a73ab99112f818586daea23f4db2.nq.gz
    ├── 4a3f0cca8c4e0d325e4584c41abf90ecc0133fb6.nq.gz
    ├── 4b3ca2ce17875372237cb3f6fa09b26d9aed5ba1.nq.gz
    ├── 4c6a75c5f5ffab9e3d10598f02020562c38549ef.nq.gz
    ├── 4d5bba79c7d25fa3b48717b692018e2ff64271c9.nq.gz
    ├── 4dce2ef20eedfa847cab9814494410bf7f99e094.nq.gz
    ├── 4e2b117b4c005f6c89f8662fc6fbb3c22be4a1e3.nq.gz
    ├── 4e5bcc213ea564104397472e35e5a00a635f4380.nq.gz
    ├── 4e9651f83d517269d73d5fff307c3a55a887728b.nq.gz
    ├── 4eaaaa78449031830cea7446210226afcd2467d0.nq.gz
    ├── 4f57ce639577ec667dd4176205b11ade23927a7e.nq.gz
    ├── 509130184b9e5424d229c2b9f99f4529fd52ebee.nq.gz
    ├── 51a2e5f1b6f9587ad54fbc889e03c1d11e02d4f4.nq.gz
    ├── 5206656b6354f6a281246f183101435e1b04c1a4.nq.gz
    ├── 52b8c2a4eb8e57f9ebd7ca27ee6412a89908314b.nq.gz
    ├── 534887fb550193fb86b803456e7120a612ca1842.nq.gz
    ├── 536673cfaa0f2abeb459f17945781dd8520b3256.nq.gz
    ├── 53dacfa43d8932e31c2ba1cf5dac9a09bef3237e.nq.gz
    ├── 550318b8bc17f4e41606b1d5d64e077b2d589e24.nq.gz
    ├── 5519b1579e9ac4b295e2760535d9b2f49b48e745.nq.gz
    ├── 5541c986a08370eb779b11dc9e625281fd90e4cb.nq.gz
    ├── 555c6ed10d96fe753e3733351af63a732640894f.nq.gz
    ├── 56d66d6aee216c0d7f3e4e113d1a0dc4794df760.nq.gz
    ├── 57ffb144f71db1edf60051dc2db0027633e6b4e7.nq.gz
    ├── 584f50087bdf79be820dd7bb30bf2f75a0697955.nq.gz
    ├── 5874c1469a52f76df0f72374f94823f2c8bc759c.nq.gz
    ├── 58df485dc89f8eba6cf302d84b85a0e68f4ba3d3.nq.gz
    ├── 5921e15f9df46319ceb5436296b3271ca4dc9e65.nq.gz
    ├── 59312a82db0703389e21ae6e1b703b261802eadf.nq.gz
    ├── 59717b4fe6cc1c788491efd1dfd528d461449921.nq.gz
    ├── 5984d83c3a7dd36a22096a4b37c9b870bb3e920e.nq.gz
    ├── 5a2c941b4ab8123739e6a09c3dc523c0a475e36d.nq.gz
    ├── 5a9fc7ecc6e200e8ee53e3e89dd3dcdf3d6d54ea.nq.gz
    ├── 5aa671ab1d5c6af5b2eb344956fc20b50d39f35a.nq.gz
    ├── 5b4f6cc9f3f81e4857ba64021c4c34a8e0f23af9.nq.gz
    ├── 5bc037f00d18c992606fed9fef11f989fec373d5.nq.gz
    ├── 5be44b7dc3c9c504a80c116acb40a55c016a4676.nq.gz
    ├── 5c0638dd1675218d96f16c20f6a6cd2bdab72e49.nq.gz
    ├── 5c3441b9266a4e1929a29f373e5c509f77c5e0ef.nq.gz
    ├── 5cd370acdd9ae2d1a1a1f1b92139211be634c156.nq.gz
    ├── 5d928d63e8e58935b3fc257ff3144099afdaadaa.nq.gz
    ├── 5d99a164487b3f0eef2949cbd4f8195d1d171649.nq.gz
    ├── 5db5b6ef048d3834a669d8cb5cb9fc8488dbe0aa.nq.gz
    ├── 5e245b4c1669089d37b18fa5eb34fede41c74244.nq.gz
    ├── 5e7ae023de3afd5e95d34f32be6e920c2413c608.nq.gz
    ├── 5eef0084c63af56322dec0e553f25bd919f084dd.nq.gz
    ├── 5f16c811a0c7171f41363f3f727518533481b924.nq.gz
    ├── 5f5d4f701b5e8e14cf2576b05644cded95ff279d.nq.gz
    ├── 5fadfb55f8ae4c826a5bc7ab2e596e39d5955bd1.nq.gz
    ├── 60226b585ec926312401d025f9472eb5251870b6.nq.gz
    └── 60b6bb83c7974e6ff2b14582d28cfaa5af2738ff.nq.gz

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

[cvxpy/cvxpy](https://github.com/cvxpy/cvxpy)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
