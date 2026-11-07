# Repolex Knowledge Graph of allenai/novelty-eval

RDF knowledge graph data for [allenai/novelty-eval](https://github.com/allenai/novelty-eval), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/novelty-eval
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9b2e69f3dfb46f30ffaa38414e581ad38322bf2b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9b2e69f3dfb46f30ffaa38414e581ad38322bf2b
│           └── chunk-001.nq.gz
└── blob
    ├── 00e7f924c77554c76d204db324c5496e0d871770.nq.gz
    ├── 00fff7e7f76b9454a8f492f98605dff89ff4c342.nq.gz
    ├── 01edcd527b0dd8a23e045ab8aeb854fa7fd1a79b.nq.gz
    ├── 038e7ccae0e3a7203b5c6267ea9df6ea214279ce.nq.gz
    ├── 041bfdef83ee8828198d9710995986af1dd6db7b.nq.gz
    ├── 0459c1aa3e7b48dfa7f5b6cafac1d828c4bba9e8.nq.gz
    ├── 048f4bc22c206159adfedc657113a71d28d59ce8.nq.gz
    ├── 058d3b2acc625c3223a3eb23d7561b1d4b74ddcf.nq.gz
    ├── 065d12d6e693261820c702c1252dcb3f9baae644.nq.gz
    ├── 072a6c96ffaaf3bba9912e7602fb75d3c5356bef.nq.gz
    ├── 07a23ad894f80134a1f386deb387c8a0c25bd620.nq.gz
    ├── 07b2c0efd51d736bce00d5b18014854067f1264a.nq.gz
    ├── 0a2239e425d6078ee48312c339f722c741f34973.nq.gz
    ├── 0a3d7941ba4fb411a5be6f094d543c0f6fe917be.nq.gz
    ├── 0d74559a02aca990e59f01b3fbb9ef65ba737229.nq.gz
    ├── 0f0c1f6b06d70273013fdf6e03fa922ec1d1dd8a.nq.gz
    ├── 0f1aa9f94e4589b810d2fcf177640de2dc09e945.nq.gz
    ├── 103017f3cf73652c429fd3c8a1a594febbef9084.nq.gz
    ├── 1203dbd2b0fc4b4dcb43567214a87aab0b9699e8.nq.gz
    ├── 135df0a67f4b3088d6c9c92a974bb3472d57e681.nq.gz
    ├── 151bdf4d0c0bc6db464c84170d914275e10ff364.nq.gz
    ├── 15ebdb2522ef6b276178fd3523451d7609713bd5.nq.gz
    ├── 1703b88c2abe869ebd5e270ec2a6636f10b3bb43.nq.gz
    ├── 18253731f9bf48b148d2e92f26396af421929130.nq.gz
    ├── 1b004b823b2a39541662adb258a4872887d63501.nq.gz
    ├── 1b4c74d0551e2aaebb2aaaea7f4ce9ea56c58300.nq.gz
    ├── 1f240c540b450ba55f533fb1a7a5550277a31f3c.nq.gz
    ├── 1f28b2434d91f8420250fc9b4a8858f4c8d71d61.nq.gz
    ├── 1f34b7b94b5ea713b0cd9c7d80b92c86dadb4dfb.nq.gz
    ├── 213259516e7d7f28069974a636b9ccfd715d80b4.nq.gz
    ├── 2225b08e9e53fa2275055ba4458490d9f64cad29.nq.gz
    ├── 227b946041c97e58d33bc6236317613fbb1f96a9.nq.gz
    ├── 239c977a7bc803675da0194fe623b3793f08de92.nq.gz
    ├── 25d1e799c117bc0a6576a1f73172758cd6ef4746.nq.gz
    ├── 26440d350db9b8668045563b8525f79926674392.nq.gz
    ├── 266479eed5886ec4c5d0ecdaf0e78d3ea841bcf3.nq.gz
    ├── 26b48e5c5eb878b98cbae31e6c381589519cf151.nq.gz
    ├── 27dd46c87ed2a4726a8420e16553cc636ccfcd43.nq.gz
    ├── 29fb5b574b34a1568460415e640f6f1d1c62f323.nq.gz
    ├── 2a9324f8a679fa9c2272d446a4adfe2dbfb35f44.nq.gz
    ├── 2bb7b64b7f9407b95ea69e38f52cf0794bd42f5f.nq.gz
    ├── 2d9a34446077b7b0ca09bb22781395a1853c9e2d.nq.gz
    ├── 2d9dce00e19ea1b4573ccb73f7a525652c18661e.nq.gz
    ├── 2fc599c06be3b2d454b0b9a8430956f0236c2d81.nq.gz
    ├── 309d8c7fabf650f08e1bf4a8749ddad7fe01b58f.nq.gz
    ├── 30b435aec5d907a98b5f1ba432b42d6572b2b0b8.nq.gz
    ├── 310d61dd96dcbc1192e42c34c3e1685c212d8fdc.nq.gz
    ├── 318d31a17693df54b5fb75eb1ec7cb886a8b2a66.nq.gz
    ├── 32295c7c30ff6cd3097516c50e53d8266dc11bbb.nq.gz
    ├── 3519118d98734e80402962955a616470e6360de4.nq.gz
    ├── 35f14b29e3514a83577bc4af89e03da4e83868f2.nq.gz
    ├── 365f086c32115f6e0f23c8370cbf68db2de8790f.nq.gz
    ├── 36e8ed4c5b5089bb2a73648d1f080f422ab57acb.nq.gz
    ├── 3735528977475dd7ca661818c66dc44ab92f7879.nq.gz
    ├── 3810cb25b6c1980538d0fc3affa92d655978aa10.nq.gz
    ├── 392c4e73dcdf69ff676989268fb30c03f5787042.nq.gz
    ├── 3c0f9814f5fd28df1d9e8ea30cb30a08457a2432.nq.gz
    ├── 3db683395bc697cb7d869e02291335442e67ec57.nq.gz
    ├── 40310e3b233c38172bca7c350806f3404effb54f.nq.gz
    ├── 412cd075d4de1f2875f847174c9cef731f71910b.nq.gz
    ├── 42b8b9c213dfc5ed8339fd2ee172d4076d222fcb.nq.gz
    ├── 443da4740d28136427c3a23a8e4c4a3adae77e34.nq.gz
    ├── 44fd1acdb16ffaa32cca765c42b6729910f1e36a.nq.gz
    ├── 4650ebd999038c69c0821f8970592f7897a30d0b.nq.gz
    ├── 472d2aaa7b7357e0c82dfb0f32fe5a6c9c631108.nq.gz
    ├── 4814eb839b3635f27fa394edd8eb99a9ae4a893e.nq.gz
    ├── 50048a5971e0470c1ef1d0e146e0a44107ba3073.nq.gz
    ├── 505b09f645278b61465577a5aef5db468f6a7412.nq.gz
    ├── 50916d9a2ae72d7cff8f4d352f25f70cf35ea476.nq.gz
    ├── 50ba7f7e19653cc0e8ca3f34d2db5db7ce9768d7.nq.gz
    ├── 50bf21d04e35dbe42c6472d57ccb7600493f2a4d.nq.gz
    ├── 52e76afe27568169af97c3ddcb44a6bba1c69b9a.nq.gz
    ├── 54178e4b6ba7c30912b252b6c5cce5aa63b9dce7.nq.gz
    ├── 5420ed05d3976603d4169803078352dc86ed4d39.nq.gz
    ├── 5513c8c80ed619881a5d5805fa63629dddbd23bc.nq.gz
    ├── 583f3895d28417f5914f11775ba2e99092873dff.nq.gz
    ├── 59f043b2cec04acaf8efb0e2a3b101f365644348.nq.gz
    ├── 5d9f99d6dc31b8e8da9f8a19b3cc97dde8f6331f.nq.gz
    ├── 601290095a4af5a300a3f6e7c4f34e811dd38a58.nq.gz
    ├── 6112f2c3c7b9444e479aebc8bb08804278520634.nq.gz
    ├── 61b8ea852579cc47d5930202da8f6fd344e110d4.nq.gz
    ├── 6296040a9ac6e208d947628a8d2fba4380ddf9d9.nq.gz
    ├── 63b50cfb65c8310ff06f9a4606497ca25158e3c5.nq.gz
    ├── 64e7a0cad37390a728580e19024a654c987c1875.nq.gz
    ├── 66100fc83807a613153b405026167f36fb0422e6.nq.gz
    ├── 66a7dbe74d9312d021dde6379dd9e1e12cf59da2.nq.gz
    ├── 6817ccd65d067ef472834e42621c36a43c6d6740.nq.gz
    ├── 6c733d3955564ac6eb086bee6afe84fb6c75cd77.nq.gz
    ├── 6cb155218fc896a4b570ba0e70b4c2b4e2444344.nq.gz
    ├── 6d94d0a9df095c2cd959c8e5dc0a54d8c6b957dc.nq.gz
    ├── 6fa9c3e0a34a99150d7b2479e670e9f3bdf2303d.nq.gz
    ├── 6fd3e2dcb023058bcead89303b9e1f12e74d8c6d.nq.gz
    ├── 71fca26cda845fd5cb23e775d29112886163bca7.nq.gz
    ├── 72007c221841c9f97e05bb3885f051ba5d87a7f0.nq.gz
    ├── 72f6884ad136e099c8f70becc0ce95fe6499b59c.nq.gz
    ├── 73a1641b6cb2ce678ead9c126c6838819ecd0f64.nq.gz
    ├── 7c39715b5b075a153b6133a8fc477edaa5e0c726.nq.gz
    ├── 7cd6afb9e51c2180876db281d6395f32d9046d01.nq.gz
    ├── 7d457a3223da9015f6ae99a81a5dd6ce8c2959c1.nq.gz
    ├── 7e08b4c143bd258bd4ef7f6943d323e03f50e92c.nq.gz
    ├── 7e1718ba2817797c62b8fe2ff1290a9ac1354648.nq.gz
    ├── 7e300f861827afc70ea355ce8f3c30dc595ae594.nq.gz
    ├── 7e32364f6967f9dd8ae236b53cf94bae9c8ae89c.nq.gz
    ├── 7e41242f2cd2e919e008c9973c1b30d8c1e6dc0b.nq.gz
    ├── 7e8c8917ea6a7b2e0b43ca78cdce6febfbd18a76.nq.gz
    ├── 7f49343af810378bc994607594c5757a525461a0.nq.gz
    ├── 7f57e58fcabaa184889741c9550cc1aae59e5c1f.nq.gz
    ├── 7fe41071a6ffdb7619b31352def712c2756a4b69.nq.gz
    ├── 80e49d23aa3bf936eafac56bba2d0f4d72ca185f.nq.gz
    ├── 81e067c51440c330cda4a23fcd6a2f755425bad3.nq.gz
    ├── 82892d9c1d3e41788909a81b47424770e5259ac8.nq.gz
    ├── 83ea9051f751546a22eeffc0d4978d633bd9cdbf.nq.gz
    ├── 84092d4bb1d285941a3d8553d6aa097b8183c6c1.nq.gz
    ├── 843e9a7d5e3612f2112eb9749e23863ed379c84d.nq.gz
    ├── 84e7d03868271b4307ef6294f7723cd206dbfb2b.nq.gz
    ├── 85bd725cf6fb7ef287da62e035ce97c61caab325.nq.gz
    ├── 87e6d4d064d3b69d1bc79f2dd1df4dbd3fabc9c7.nq.gz
    ├── 8a7bf9c4958fedc597ec0def8ca50c782bab3419.nq.gz
    ├── 8b05dcc09cc3dc4e5d8fb74f1699012a7591aa9c.nq.gz
    ├── 8c4b685cbddf6ade3277182fedb60adec1df8679.nq.gz
    ├── 8da0ba1385a7c37bdf5d065fd1ac3ae463ac6696.nq.gz
    ├── 8eaca38aec38f93048ce3df5740791957ae0a297.nq.gz
    ├── 8fc1d991d6e93e2bdcdd164a953f971c8f66fa9a.nq.gz
    ├── 90d558bccfa3bba0be974ab4282bc579e0870371.nq.gz
    ├── 918d61d257a15b60a0f2fdc215fb44302ef5f10f.nq.gz
    ├── 93f90a3a86f4957871b1d6181f8c967d98268abf.nq.gz
    ├── 9662a1fc4664cba40e524280369951a0be0e18b8.nq.gz
    ├── 969183f17e0ed1af878e0d907041cf93d3604d08.nq.gz
    ├── 9957260226285e7e2428c9602d8c044ae1cd6f0a.nq.gz
    ├── 9ba3045ed38b0ba4cf7d0e8faea97fbbdadab64d.nq.gz
    ├── 9c4574c1c88866a98bad162f3d2e7b006f043bc9.nq.gz
    ├── 9cce6b79cd3a25f8ef55ff2229e6c24e132b2430.nq.gz
    ├── 9ed62c2142b1d477ef2c9cf79faf52a47a3159c4.nq.gz
    ├── 9fe694359a9f1fe4ba73d0d64750e22caff8bdff.nq.gz
    ├── a0564bec7632f8e68b739abc0483009e0a46e686.nq.gz
    ├── a0ea6a503e23c81f4adf314bf76a278ee985aec6.nq.gz
    ├── a1a4ded42e24fb086020b3d460ce9959325e60f5.nq.gz
    ├── a508161dcd18c6a255d355ffb6ff53c1ac266535.nq.gz
    ├── a5a2eedaf228978ecccc2698a1af3c9f94398aef.nq.gz
    ├── a64894392bf62ae6fc19c6980c26e113a569cdca.nq.gz
    ├── a6e94c9abbac37f1da6ce41a421e115b4ac84930.nq.gz
    ├── a8c9e4f6b839e4e82013e98a7b3b4339937d5c8a.nq.gz
    ├── a8f9daeb9cf958a71f04008746e0418e9ce15af0.nq.gz
    ├── a9025eae97d025cd8e1db757b3c7b72c02de6d5b.nq.gz
    ├── a9c4eca024bb653bdc60fa40aae10bac3128ebf8.nq.gz
    ├── aaa605a791db1822800b1a33b69e21af2c12753f.nq.gz
    ├── ab5d7ed4db40bfec3a7d02cad59bf78cebde41fc.nq.gz
    ├── ac07f210b265c259d38ce2c648b09f50706307bf.nq.gz
    ├── adf24e020861515bb2ed5bf9ce72012ef7b720b3.nq.gz
    ├── ae0317a26021d3ae5dfc1ccaa5547c6f8d0a192c.nq.gz
    ├── af1bc8cd6231155208d9e2cbba50c91c92ed8af8.nq.gz
    ├── b2b8d6e418a821ffc2e5be8f416afa6c60370013.nq.gz
    ├── b45318905eec73c99014bf871bd0953d209fca77.nq.gz
    ├── b4a19a6945b4dd92e23996306b0912cddc39b20e.nq.gz
    ├── b52feb1e5a4a851732f93d38a70b8656b1d8a7b4.nq.gz
    ├── b6bf49f4cecfc2dc9aa21685f5f86fcc11ea8e1c.nq.gz
    ├── b7a89e0154128de5b815391b666a9c71da0d3cce.nq.gz
    ├── b863080ad2f0ad5842f4ca513114ab0739040ee4.nq.gz
    ├── b87d3feb21dadb948fc6e646319347f03bbb3d32.nq.gz
    ├── bb96b22ecf16ed8ce9f3805f8de2dfc186a6cdb2.nq.gz
    ├── bdf79242b66f856b2f7303053b159c2a458bc5d2.nq.gz
    ├── bf3c78dcb92757257e68cf8ad9719d61cd57ec89.nq.gz
    ├── bfe1bc56a91761c2055cfbea61b854d491ffd6dc.nq.gz
    ├── c32ec2174c866fd4f039e5fa24bedea495e813a5.nq.gz
    ├── c4075a1d316d33c615faa981f77cccea4af54e69.nq.gz
    ├── c45a64ce0c109540fb2a142261ff1389e373263b.nq.gz
    ├── c577dd89e17312da1ed45a197cd5db05659fb186.nq.gz
    ├── c617fd5cfad168480bb00a3627482a341a48eacb.nq.gz
    ├── c6dfa117e298a0b1ba819d7566580538b03e9a95.nq.gz
    ├── c6f1461831d010da98cbd0c2b8dc66b065a31e15.nq.gz
    ├── cfaf299e5bb6dc817d7f01efb2397bc7fc4cd404.nq.gz
    ├── d1097665d826f6aa69dd8b5f81ee895ff1fbeb5a.nq.gz
    ├── d1d9a7695b7490a4c6ef9bb7a6f66a148070a911.nq.gz
    ├── d235969d9962a009f0780bb0a72b2d6957efee6e.nq.gz
    ├── d2a8df6cb08ef1e97677c35f6fce8fe9acde2490.nq.gz
    ├── d3c752863604fae88ed787a7846201ed613e2fcb.nq.gz
    ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
    ├── d827465bb556c3b88d0048ed51f62aa9c1077dd6.nq.gz
    ├── d9bdb3d62bd0cf993abfc220bdc0774b0563b5e7.nq.gz
    ├── da2fc700a5fcdf985ac122cc0666f2bc3925d879.nq.gz
    ├── dac05eee679e007b4e810cc7bcb80004ca6fbce9.nq.gz
    ├── dadafb653bbaf21c9cea71c2f873296abaea72c6.nq.gz
    ├── db1a0f051dd41543fe0508b50679ec43eeb366ea.nq.gz
    ├── db24779c6b86b0680c91d701c94c4d33913a1e0c.nq.gz
    ├── dbeb117f1dd8d938c0ee6fa6b48f2a6ea9a09521.nq.gz
    ├── dd104753426edb064cf7fba82ce2c8a9a422ded1.nq.gz
    ├── e0c820e02e7182e1e38d750faa3d8c7d1b1b40de.nq.gz
    ├── e29187d82d63f49b592f010b060766079fc54703.nq.gz
    ├── e39664fb578460090f0675cb3cca4e6d32d9b4c5.nq.gz
    ├── e4fa6b3ee28896f9aa97068eb13e8ad644266a66.nq.gz
    ├── e564069258362d51a6329714d8d714a686d7c7ec.nq.gz
    ├── e5d8c2c6537ce31b8b8e2e4616ae7b28c0dcccaa.nq.gz
    ├── e67b0ac9c37a33873b860fd8dafe266d1909b6d9.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e72ad955533d68767abd41bce3c38912ed96871e.nq.gz
    ├── e73277a2c1555cbb22bebe4c655b41e98065c3a2.nq.gz
    ├── e83f2331a1824f01428b1e92adef0beac613e344.nq.gz
    └── e8be5a164bb103e5c85929507a814c0088843096.nq.gz

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

[allenai/novelty-eval](https://github.com/allenai/novelty-eval)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
