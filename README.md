# Repolex Knowledge Graph of executablebooks/sphinx-exercise

RDF knowledge graph data for [executablebooks/sphinx-exercise](https://github.com/executablebooks/sphinx-exercise), parsed by [repolex](https://repolex.ai).

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
rlex download executablebooks/sphinx-exercise
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9804d685b8e6036869845683bb5d22ab5f3b78c2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9804d685b8e6036869845683bb5d22ab5f3b78c2
│           └── chunk-001.nq.gz
└── blob
    ├── 018315ad9033fd98909a2973c7987da3c44742c5.nq.gz
    ├── 04ef7e64f41fb46326f6f305bbf845477d10349c.nq.gz
    ├── 059f2e2dadd6fcaad46bac0ee7ff3e809403db0a.nq.gz
    ├── 05f7eaf3e5ab084ab1f6d534a6e9b9c2ccb9ab25.nq.gz
    ├── 061a455db1e28768cf7592f747057ffb9432aa51.nq.gz
    ├── 06e6f5f5a6b8a34adf7c916649f9763943ec9782.nq.gz
    ├── 0704ae1752fa0c2735d54989bdf39bc71aa244c6.nq.gz
    ├── 07a1be82b0297b44aeab4ac9ae86b810c4a02ddc.nq.gz
    ├── 07f8265e20fadb37044fe5604e55e5d0dc56fc4c.nq.gz
    ├── 0929241fd214911f0b34169bef0dbe9a493ac0c3.nq.gz
    ├── 0a4b5cc1c89ff089053ccd3430c675f330c9659f.nq.gz
    ├── 0cacb2d889abad2e67eae95166cfe9341fdd5e27.nq.gz
    ├── 145bab2edd58f123482ae5e045795fee2fb12188.nq.gz
    ├── 1600f3fdaedf9152c7c7513d7f59c3fc0233b7a9.nq.gz
    ├── 16dfae21959b706fe1b266c985ffc57290cddd23.nq.gz
    ├── 1c3bba1788df31f6d18245e726ec2997e51daaf0.nq.gz
    ├── 1cadb0980fde7e1ba772c4ae11f24c12a5fbf1c3.nq.gz
    ├── 1d07b2692242735d5e0da59e885b057daf8aaa95.nq.gz
    ├── 1e74f78b9bb158abeb46f573b67318e234970898.nq.gz
    ├── 1fe5c64f38faa04a11084e623497448a543fb71f.nq.gz
    ├── 21dd0abfbf6e7060632328e241c2c4f576f251c9.nq.gz
    ├── 2263e21dbad4aa1da607d483031a6e7442bfefec.nq.gz
    ├── 24c3e7c79e825b7f9ceb3b43d9dc072a5e763569.nq.gz
    ├── 24ecf1f75dd5c07d85be595cd2996d6486758adf.nq.gz
    ├── 25c8a72c447b7b6ffd393ff667c2d7cab3d08a7e.nq.gz
    ├── 25dbe70a56e490af946547d44d5225566fbcb795.nq.gz
    ├── 272bd7f339c9e4f98d7ab242aa4e2aae0486b596.nq.gz
    ├── 29cd9d9c4b3a3c8ad00fe14a70c11a06a2df8409.nq.gz
    ├── 29eba4ce31e8ad8b07c4def38d9f75de80d63441.nq.gz
    ├── 2a982ab663e84389362a8f117d10bd7b06a41cf7.nq.gz
    ├── 2c0733315e415bfb5e5b353f9996ecd964d395b2.nq.gz
    ├── 2c0764f4deaefa281b0316aeff4b3c9b98693531.nq.gz
    ├── 2f08ec70499eea7526817c9d42fa0d58d58c614b.nq.gz
    ├── 2f0f6a34940b99e04f65f48928326424fa2e1705.nq.gz
    ├── 2f7877a44c708685e931a8bb00aaeae98ea02c39.nq.gz
    ├── 2ff248266e1dd5ea70118077711f61aa8a26c3fc.nq.gz
    ├── 30c8a127f3a1e241369987f9d2477d2fa8987ad9.nq.gz
    ├── 3205d7fb898379a432af6672fefa23c593efae02.nq.gz
    ├── 32ce04bba10a0c52d2c2109dadc3112f701ea92a.nq.gz
    ├── 34b9dcf7f2862a3016e10e804dc330365b67db12.nq.gz
    ├── 375c50b0359c70fdf3196532b7fbebd1a832b669.nq.gz
    ├── 3a9ee4b7203f4fbf473317db3a68a21332bd4c4d.nq.gz
    ├── 3d1458d5129031d6f73fcd6530d10615ae8492c8.nq.gz
    ├── 40285bfd4866734c890a84671fddf8c3618eb560.nq.gz
    ├── 439911ce789e5cad09e67dffbe2134dc712285d0.nq.gz
    ├── 4426842065c380e5a772810c563ccd2d247bbbb1.nq.gz
    ├── 456f08dfca62315fb9fd82e1cbb9432230d81020.nq.gz
    ├── 47144b5173ce81e2d599750cfaa16af00c896202.nq.gz
    ├── 492b6c30901744bbf4730d910bc163abe3bf784c.nq.gz
    ├── 4bcb37326cf2ba0a89c5cacc768918f84a33ba82.nq.gz
    ├── 4de64b9479d423e7cd05f150fbd02938679932fd.nq.gz
    ├── 4e2740b05147fa4d9f0258b823385a18c35fa75a.nq.gz
    ├── 4f54b84eb4a1ca9976c7e24737772c43eb273133.nq.gz
    ├── 50cb93ff8963dadb6c7c8b5b32d69e426fe6ccad.nq.gz
    ├── 5102a59aa8ac02b9d699afc7e632eb0266953b38.nq.gz
    ├── 53ff0ae63c239def7901edc844aa8d1a264dcda3.nq.gz
    ├── 5409caa57238dc0d0cd66f63438a1a70e9f7008f.nq.gz
    ├── 54ac8358175433409fa6e6d4631a20d5fc590819.nq.gz
    ├── 56b0f02ff33b5790d1fdf58a43805e25cfbd4c1d.nq.gz
    ├── 582ddf59e08277fe6e78cee924d2c84805fe36fe.nq.gz
    ├── 58d20f5ba49bd053471928b00c758ffea910dd5d.nq.gz
    ├── 5a69cd6383ebbe21c1b25deeeebc3deb1faacb79.nq.gz
    ├── 5d0ca858c2d9f3059324a9ea4e3c69b416cbbfc3.nq.gz
    ├── 5d6a3a3cfd6ad7a73b1b7812c54275939cb34362.nq.gz
    ├── 5eaebb82284eb75e2423b81284305d4f7216bcc9.nq.gz
    ├── 5eb679fae58e8506671b81bc53d6ad58ab4597b4.nq.gz
    ├── 60548e28ace8534210516afe852edb40f092a012.nq.gz
    ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
    ├── 62829c7d0602bab9a80ae04512b2707c2b281ee7.nq.gz
    ├── 629d64f471308cc72e2ab1478b190eac6e53a0a5.nq.gz
    ├── 62a9d507f389c9f584a0c29423e4cc8720b46090.nq.gz
    ├── 649e6cf9e6bc46c27910743ca64f60660d389b5d.nq.gz
    ├── 6691eb47d22a7b9eee003d8e83abb141b90f3cd6.nq.gz
    ├── 670b53c024384dc2b3316ba7eb91ed74e8da5930.nq.gz
    ├── 68c4eb345fdb8b67cf42a6df95ddde2b647068da.nq.gz
    ├── 68f29b894f31475523d920471790b7eb7a78622d.nq.gz
    ├── 697190840befa7aa3088c762ab669c7f0230e4d1.nq.gz
    ├── 697adb1d1bf276491f2c20cd406f1ab91887caa7.nq.gz
    ├── 6a059a26c6cd2793966a776934a5f9de4d4a991f.nq.gz
    ├── 6a6f2b2ef6cea29f7494ca5f6ed0ca3fbe12430b.nq.gz
    ├── 6b2527e8d82a76f7b71c21b45d6feed7a03756f5.nq.gz
    ├── 6dd8fcf14083d53fff2c3971ef5473f9091b7773.nq.gz
    ├── 6e480e0ba758b5f62db865080211e8c73579fa87.nq.gz
    ├── 6eb04fdd34f408db6dd308f56fd955b492eccb0f.nq.gz
    ├── 6ecb8d7d9c48c4a4e46d74aa23dd5f9ad31ad0a3.nq.gz
    ├── 6fd03abc479e25fd5dd207a498425c6062e56dba.nq.gz
    ├── 711500a7fc7cdd24f9f8bc307978ab635c4ea591.nq.gz
    ├── 7149ef9336fb0b2d683c4cf33c4572e205a57116.nq.gz
    ├── 720d34f79af6028588582e18a46c6dfc01a7e9e3.nq.gz
    ├── 72e85b9713b2096c172f0a9e7cd6f06dd18ebe93.nq.gz
    ├── 748c520a01b8b364aaad8c50dd75c304beb3d01a.nq.gz
    ├── 753032f65a078aa7ee23cd1511023165989acd99.nq.gz
    ├── 7551f438b177028f6fb3fa91f4710378cff9348d.nq.gz
    ├── 7984184fdc2e5a5986f22638fd77da968897394b.nq.gz
    ├── 79e31edefc76e3424a84e75e5e480be8a71adb15.nq.gz
    ├── 7a45c3f41626259285eda6f1acb92ac8ba524dd3.nq.gz
    ├── 7bd5a4f44263802a4c548e4ee89cda6a8257a838.nq.gz
    ├── 7d3880cfb616f856548a51015fef4f920501b303.nq.gz
    ├── 7d39a263da0aa7aefbcb07e9d5e025500acfe225.nq.gz
    ├── 7e3e1807c047218bcb3d8516c33b7078580d3338.nq.gz
    ├── 7e98d304ec72f7df1238f8be80b5458a1e0829ee.nq.gz
    ├── 7f921d6c99cea5d583a293948bf30d06eb502c25.nq.gz
    ├── 8140aecbddf25e4e4268018b09c333fce91cb5d6.nq.gz
    ├── 8147e1b6e7674858df4128ef69affa7b7b5e812b.nq.gz
    ├── 81b0edda940394128ea26adcf3251c4fe0912317.nq.gz
    ├── 83e33e0f1f5db997e35e5316d5bd47247a2372de.nq.gz
    ├── 85c74721983726440ee1d43541a66b30e5beed92.nq.gz
    ├── 86324c5d31f9ad28d6c3fab221e5d1c16c2aa386.nq.gz
    ├── 86838b9746574e45ff38d89c8089baf6a39858ae.nq.gz
    ├── 870f7b39cec48c65c3fec4faf57e3e85575fc801.nq.gz
    ├── 87a7dbc26decb758bbcd244770353fd3412de6f3.nq.gz
    ├── 87e88a53f03d1519bcb6c8d99357ca48aece5f01.nq.gz
    ├── 8b9463b65d9306e67c47d46bf3a54d27ee59a8eb.nq.gz
    ├── 8c486ae0bf2ded2265cf30a2cb70e97533694f23.nq.gz
    ├── 8f8ed0012bc9e3933a2b3292a011044dbe65985a.nq.gz
    ├── 900c175c465904f3fc8dd6af62e6db3a13e941db.nq.gz
    ├── 911fa5464b7fffcbecb9e4003879f78fef41cb83.nq.gz
    ├── 9303a6eaf7aa1b42d45cbcec98ace2cf6d956405.nq.gz
    ├── 93a3f634459990867797e0d90863a939f97997d6.nq.gz
    ├── 944ea38eb9197bcde3db00d04cbb19557a01bec5.nq.gz
    ├── 94a82fa236c99a28e2456b83e835922d9f879115.nq.gz
    ├── 954a9b38ec53df2aa486f9d3a8d5582c24c98e30.nq.gz
    ├── 9607f4a6491f7525bf4a36a7d945553e19d2f7d8.nq.gz
    ├── 96195e2ce72c4f8017f707adb87dbe22dd3bc6b3.nq.gz
    ├── 99e70b8d232a850e1ecedf2d8eafec98cddb2a7e.nq.gz
    ├── 9a3b6980432b1b5f20e18324031d1ce6bb40f975.nq.gz
    ├── 9a42a6e2f5a6b2eb49a0754de796aea36acc39a7.nq.gz
    ├── 9c8d44e9d6e8f21506e72c185a864f750304988d.nq.gz
    ├── 9cafd2acd8810205767684bc33d5a9a16ca9cd3d.nq.gz
    ├── 9d464e66c8cf5b1972fd2596997288c20b17da93.nq.gz
    ├── 9dc64d4d580cc0962c0e6895de8e7fc5d81fba05.nq.gz
    ├── 9e273dec42297d980ff942e0a12f037d9a091797.nq.gz
    ├── 9eb397d0baa9571b0d4762710d3f30ead00f8a63.nq.gz
    ├── 9eb3bbaf5f5ee60a3ef4329f12b98bd72be28bc4.nq.gz
    ├── 9f5b655b7d808959ec969c96f9d308a87e08a095.nq.gz
    ├── a19584b9507ba9ccc1bb4601d8710935838f92e9.nq.gz
    ├── a223099a6fdca15c7108057e51b879d0d8f6dbbf.nq.gz
    ├── a2a6024fceae738b8821342f16d4872d42fb277a.nq.gz
    ├── a3690026b703db61dcfc77a89d83c088f3ed8b5b.nq.gz
    ├── a3bf5c67f7421319ba34c7ae03f71e0280acc7d8.nq.gz
    ├── a55f7548c9d824c94c2f2304ea9478c6f07578c9.nq.gz
    ├── a583c5555862ff81081b6e581f83a33f9ef2ce5e.nq.gz
    ├── a8c9434b3faaf324912851f10bbce915d1c30da2.nq.gz
    ├── aaba841976b63eca785334ebcef56313a0abca51.nq.gz
    ├── ac6ee9d74541f35ce77d81db95210c2e94aafb32.nq.gz
    ├── aec045a113cbc1f27a29931d0d81c7e1d14ffc4b.nq.gz
    ├── af407fb55e320d834296e1a3ada40c9aebd0df10.nq.gz
    ├── b03b9ac74f0fe8ef1119e29ae246d7a444df864e.nq.gz
    ├── b10c4a434572b1e207f752afe2aaced5a6fcdd8d.nq.gz
    ├── b224d03d9dd3f277d3404bc8f711ac84d30ab2b1.nq.gz
    ├── b381cb74aa89b1ac73b6cd36ae85c90a939f2ea7.nq.gz
    ├── b3f20e1fe0ac43e673d159d6f2b36193d8fb394f.nq.gz
    ├── b43af8f867ab74fde71e176d7d365538a1fdb399.nq.gz
    ├── b6ad8354364a50d44174aceaeabc08bbe382b9c7.nq.gz
    ├── b7a2467562ea8998f5e967fa1f5b8fa44b770f41.nq.gz
    ├── b8164a074437870cf8ae35debdb9dbc0072f7d49.nq.gz
    ├── b871fc064229c2a304c2d485e95e015cc6d74499.nq.gz
    ├── b950eb72bfb3e022bb10a85e639a9f86dc62c314.nq.gz
    ├── ba11f557c717356ee8e9811f31d973f90841abbc.nq.gz
    ├── ba3ee2cac84dfb02a7fe536dcf7642e0965c7131.nq.gz
    ├── bad2ebbca3bbce2c1f51b504c0d397ad2f2ff54b.nq.gz
    ├── bb5780681784a49322fd0ada884eb14f4894a3fe.nq.gz
    ├── bb5944ac939ee1a4c14c65b4c52431030c27b6bd.nq.gz
    ├── bead76dd4220ea9e134c2314b0a3b69b75f58b5e.nq.gz
    ├── c033389c16e1857ff1cd05eb8c88c09e1ed14771.nq.gz
    ├── c0d991c91abf29752b5c2b75ae649fa6fb4d7f2d.nq.gz
    ├── c16335ba1132d18cb8702a45ad2066b7d36576ac.nq.gz
    ├── c35da7acb6c3f4462933aee373016b0d21109140.nq.gz
    ├── c429f2a422f69bac9f1a79fe9b5b2df04f4325db.nq.gz
    ├── c49c0097593e281ba92eadd3fc3c5f788b0bca42.nq.gz
    ├── c4f7d8c555d3b86056819eb350de79c1710a62a3.nq.gz
    ├── c505c648fe481b2cf4c4248f5b302bfbb275e2e8.nq.gz
    ├── c56e0b89cfb795facd0ee7a3a47fa8213bcc6c89.nq.gz
    ├── c6128577b4b8e349be5bba28e98dfc37bd4f5e48.nq.gz
    ├── c6ed9de6a9a68e52a717e97eace0190c89bfe910.nq.gz
    ├── c8e00f0fbb552aab29089205eef55b5f0cad50cc.nq.gz
    ├── cc67147beae6a25689483d0782d4c7a7069656d3.nq.gz
    ├── cdaa8f3dc5ae9d0fefd35fd44c5bccc63d8b9e39.nq.gz
    ├── cdb827155dea6992fa567c5f09a3c25e32caa67d.nq.gz
    ├── cdf47d91313f79c0e2ecf5543aced959f37e803d.nq.gz
    ├── cf0f8be2b4f8a268ff8f9e1867a6db225041a0f4.nq.gz
    ├── d131f1850cccbe4c57ba4fb9d763f91c69a4f591.nq.gz
    ├── d28b54bf92b57d09d9b46620ca00c25bcabc2a89.nq.gz
    ├── d49b0ce7a72f2426e0db6022a0b8718e6a15b975.nq.gz
    ├── d509fd70796d18eb8d8a0d98dbdd0d62ae56bcfa.nq.gz
    ├── d5c931a38774929c46b63777114d0edb3e00b051.nq.gz
    ├── d642ee70bbbee15914327c7473d474fde8fa9e68.nq.gz
    ├── d9a0fd794ca343061f20c9aee18898a7d3eb98dd.nq.gz
    ├── da1dc3fe932bfe23ecd40661c831d23ce445d9fe.nq.gz
    ├── daa32c84debe981cc55805a2c9f369fd893d1d73.nq.gz
    ├── daf34e71ff1d89de67695d3e5d0e23019aedafd8.nq.gz
    ├── dc88dd97384f4c8d5a082d34988797ed938a62f3.nq.gz
    ├── dda9865ad01e8f6ecebfc69f0889c81050a594f0.nq.gz
    ├── de3dbdadfade97fcfac04a13b3a19ec206d8c108.nq.gz
    ├── dec2fb23cd3a964cef9b4b9d3d4282d49f9e2dc7.nq.gz
    ├── dedc9797949344dc0307a8167f23d1f141b7a7a6.nq.gz
    ├── e0f06e000d25d0ddc50c7d7d35bf2fe41c9f7819.nq.gz
    └── e29b5bc3b7aabc1ddaa4c74c10efde9b7a2000a4.nq.gz

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

[executablebooks/sphinx-exercise](https://github.com/executablebooks/sphinx-exercise)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
