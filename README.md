# Repolex Knowledge Graph of twisted/pydoctor

RDF knowledge graph data for [twisted/pydoctor](https://github.com/twisted/pydoctor), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/pydoctor
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 279e589afc7d0a42aa1622245b30102a1bc34cff
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 279e589afc7d0a42aa1622245b30102a1bc34cff
│           └── chunk-001.nq.gz
└── blob
    ├── 02c4fd8e87fca2cf6177b6d83d54494a2931c958.nq.gz
    ├── 03738e8520fa34d3c6c54fb29db5866b51eb3bed.nq.gz
    ├── 055e71c756b9b610af2c9bd204da52991356ac35.nq.gz
    ├── 05b486c19c04a47219281e6a6e8f52f24bd53dd9.nq.gz
    ├── 0725182c5626b0d774a0e24f84afe5c431a92a6f.nq.gz
    ├── 096577e25cb694b1b50bd0a1a1da6c5f83fd8996.nq.gz
    ├── 0dd9da14c3597e2e182a7dcea0169759b7b5c57b.nq.gz
    ├── 0e8970f112681bff994ed174df0e7bf03ac00f50.nq.gz
    ├── 0ea9e8a35fd373df2c8ecd6739756ef311046375.nq.gz
    ├── 10b5dd360cdabd7d9b70a358aa8b8a98d4244a22.nq.gz
    ├── 1138c9ed2a248a13e5bb4426e062b11f33845df8.nq.gz
    ├── 113b478bd57f3f689251d5c822d67f811e6181de.nq.gz
    ├── 119fd4ee8e028f3344b68f662921c08db1fcc546.nq.gz
    ├── 11f2e22a1fb756674b72a8056ff4444f3ecbcdd9.nq.gz
    ├── 1287c496e03340db44e7c11047cb72cf159c08c1.nq.gz
    ├── 142f89f5bfe2a38cc492f97b4cd919c7d73cf113.nq.gz
    ├── 148f839d1d010e2b080cd3f7b2637bc41d290dc0.nq.gz
    ├── 15ecbd89b37148d4cc5f03e4cc69055e6ea099ea.nq.gz
    ├── 16631d33ffd7b7862a8a7a90b30d6006f3b7eb0d.nq.gz
    ├── 19fad8abafbb56f0d9832d0e12c3a3fe5691adea.nq.gz
    ├── 1b47f7a0d641c1bbd394b74a9fadcbb520fadbb8.nq.gz
    ├── 1bb8bf6d7fd4c8d09aea89b47de20fb8bbb61626.nq.gz
    ├── 1f2e5a41a8b2324a9df0df35ceb97eff8b8186ef.nq.gz
    ├── 20518ce519a7360658375fcb87d57ad3c1886351.nq.gz
    ├── 2079da7b3ac5d39be7b770e4f175dac0fe39bdef.nq.gz
    ├── 21080cc3a634485653971fa9386b2f877062992a.nq.gz
    ├── 21e6c5182e64548ca520e7736c3b380e2ccfd001.nq.gz
    ├── 24420d5d5b8cd37d251d3de270bc31b9a9543d10.nq.gz
    ├── 257df84225ad2cbe591d8c033d0a78d0418c4d37.nq.gz
    ├── 2763ccd2fe2d6fdfe9e4ef1eb267e8fdf2e1fa18.nq.gz
    ├── 278bab32454893b3ff2709ab382511966c5cab35.nq.gz
    ├── 282a2676e16da5932a85c9021d60fd0a2e2f344d.nq.gz
    ├── 285996b0a1dbefad70371bab7ddc1fb600c515d0.nq.gz
    ├── 2bb862fafa95c65692bb9ffff20d8519a087737a.nq.gz
    ├── 2bd699b5407b2d6899c8b1b7879e5fb7302e8e81.nq.gz
    ├── 2d6316a1f6620ce00f9129a1bc1bba8bc07281a5.nq.gz
    ├── 2e33574e7a2d0a7d650bdccdfcc815627f425431.nq.gz
    ├── 2efa6cb33b79bfecd334b2b97baa149030bb7d57.nq.gz
    ├── 2f4bb415460f6cae9be44135cc0ec59c459688d5.nq.gz
    ├── 30f8b84ebe57aa20afb572091380a2042f185a8f.nq.gz
    ├── 31eb5627da0156f8e18825cad6dc811e6307b1ba.nq.gz
    ├── 3396925cda78d9911966abcc8061d0cc4da3c153.nq.gz
    ├── 3398022199da37cfb8465b48baa4ae0038664dc8.nq.gz
    ├── 364f214801d3e618fe97b754a853dda5d49c1a3c.nq.gz
    ├── 375164f67b30a6763ab35ac9d6ee29e0927e6bf6.nq.gz
    ├── 375c40a74828d356661826e40309d3e99df217c3.nq.gz
    ├── 3773cc5f4c9e4c53c9d3c22c56d95bcdbc537d9b.nq.gz
    ├── 37a89bb98008d418be4cdc90f47d8fe23522f9cd.nq.gz
    ├── 385b9ea912d2e22ef201bcc801d82e019d7994c6.nq.gz
    ├── 3aefc40841db1dda06a0529f90c58f4173b46561.nq.gz
    ├── 3b97c263d889a3368219ab8a9d1a9a9c9c81f6c7.nq.gz
    ├── 3bf9843328a6359b6bd06e50010319c63da0d717.nq.gz
    ├── 4059b09963b0b9830e403ad3f72a98b84cb67e47.nq.gz
    ├── 414de12e8f331fc0a21f023ec73d8f1e907ff558.nq.gz
    ├── 41a55a438a3983c22488fae02de4233c54caf966.nq.gz
    ├── 41f0c828b85c3cd3147e6fcb797c2872591625e0.nq.gz
    ├── 442bd97a63c032cd56efad54ba9fd4f76c831f6d.nq.gz
    ├── 442ef131ecd78c183bc993e0ee831c32a3b4081d.nq.gz
    ├── 44901134692d2bcea5e5b40507b79952267e6335.nq.gz
    ├── 44d23e080cb20e2b1119247cc8de5b7c5c0ab57a.nq.gz
    ├── 44f9d02cd1abacef8484390e8bcb8133bb932347.nq.gz
    ├── 454fc672b8161269b3b3108b80b1cdb9326efc85.nq.gz
    ├── 457b2e5edaf77bb7bc8fd95caf6aa9bf95646a57.nq.gz
    ├── 489e803df1f9b6ad6baa00a5736d9394eed39a1b.nq.gz
    ├── 48fe780952abcd7ca4cdb759d3bc3804bbdc39b6.nq.gz
    ├── 49866fc9112566030f9b26b35a1a97ea06f06f4f.nq.gz
    ├── 499fa36c1be326c96d117bc0f16e8b7ff1104b09.nq.gz
    ├── 4c46446310a8db368e37d6eba623a47498354bd1.nq.gz
    ├── 4cdddb35747583381d69418d99e3757d72c3b3a8.nq.gz
    ├── 4f28bc7a4992fa35bc68694e612a5b49e2d770b9.nq.gz
    ├── 4fb9cec901033f440b7b73960debe9f7bb22c540.nq.gz
    ├── 4fcb2ff4ff615b3da70f8a0ad9ca424b31edf010.nq.gz
    ├── 4fccd52e5bd8b89dd7455e9398146acbb7402b43.nq.gz
    ├── 50e3d9ecb61306067f090c7e650c2bf3aafd8f00.nq.gz
    ├── 51a2e57f9490e6187d6d8bce673df0bc66b48d7d.nq.gz
    ├── 5348e018947ba81a31b7ba6a69efb901a57fc690.nq.gz
    ├── 53b8ad256a1be9cc238b10cde6b4e207cf7ea45e.nq.gz
    ├── 543ef7d9c2d316cba6a90b7ce3eee2a783b1bbd8.nq.gz
    ├── 561bce1c8842ee4219ec22f290ef8d740a6c1d48.nq.gz
    ├── 56878090c0589907435ca87e4ddc61f8d22651e4.nq.gz
    ├── 57be564f0a4c7a9e0826fe22675dfa58d7d99320.nq.gz
    ├── 5a5d838a899468fcac3538d50ef158eee003718f.nq.gz
    ├── 5c37280e9292ed480dd22db4866c45fd20d88f66.nq.gz
    ├── 5d132403b8bfd273c8ebe963700d672895ae828c.nq.gz
    ├── 5d40afaa60f7e587ef9f6066be76da8c166b46fc.nq.gz
    ├── 5d57a519abd194bd3585d4f2e6cfad7169fbb22f.nq.gz
    ├── 5e18bf382b5381a71376783d3a8d72f75815186e.nq.gz
    ├── 616a9f624a898aec25e15b282b97d99ee9b29409.nq.gz
    ├── 616b553fc976ca1e2ffd4076d495852e309e3ba7.nq.gz
    ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
    ├── 62e242b0e7ec90f419501bef18e1d10c8860ec86.nq.gz
    ├── 639f8d8b0df4b3d767833ab9ddd1df1adeb66a77.nq.gz
    ├── 64c35525ecb906df3fb17feeb71022e8a543531a.nq.gz
    ├── 65821691b59fa05f64eb2a28bc2c70c152a13343.nq.gz
    ├── 65e4de19db37aeff49cb191aa8995b3d82e0c122.nq.gz
    ├── 671689e80f0633e7d36bbdb2a6a5172dc33c6a60.nq.gz
    ├── 6768f2a3846b5bc0cf2e438e27ba186bc0f090ed.nq.gz
    ├── 686388d9693ed8e5615d0ed5570c94d751072f0d.nq.gz
    ├── 6a9fa40013e765ed69f2fff35442539890493f80.nq.gz
    ├── 6b09be9afb27bfcb060f39653437e1de65b25e50.nq.gz
    ├── 6b6fbf902d155ec054992cc5e685f5b26322ffb4.nq.gz
    ├── 6bb875b0b15986ee6e9d70282b9d01c625a94f97.nq.gz
    ├── 6be6e4ab7b954c7539e61fb510c9afa8e83483de.nq.gz
    ├── 6c2b4f1dd31da256b23b1c46042ca91fb85a9d65.nq.gz
    ├── 6cc61302c9a76b857bc33b9b1831d6cd4594060b.nq.gz
    ├── 6d7442a82146331e1272d94adddddef41a078711.nq.gz
    ├── 6d80387c6597b6225d80be32f418bcd5719eaab5.nq.gz
    ├── 6e5da46c949e6877978ced40d30c8a22fabdedac.nq.gz
    ├── 6eb1e3f3e770f73e14b85d49f89eecf5fc97d92f.nq.gz
    ├── 6f7da3cab284c641bf7f6e7e9830f35007411eeb.nq.gz
    ├── 7059e23142aae3d8bad6067fc734a6cffec779c9.nq.gz
    ├── 714aab684304afe7720fd0fbf7e4a86cded09b3d.nq.gz
    ├── 71b18fa4b66fc10821d94ce0b6a70a628cbadf6d.nq.gz
    ├── 7378e24c9f2ab82a77613fe5e96cfd9ff1a4e3ad.nq.gz
    ├── 73c494aa83a024212993d522a9ac7678b0c6a22c.nq.gz
    ├── 7463bbc85d783fe2477d36dafe0e150ca46fe414.nq.gz
    ├── 7501a4648c438900a47b9ece7bcd908048ae1d25.nq.gz
    ├── 75d8c2300983360ab69b1c14b2860ffe2e893aec.nq.gz
    ├── 7768fa0983424f843821d7131d7f286e13cd3376.nq.gz
    ├── 792d6005489ebee62cde02066f19c5521e620451.nq.gz
    ├── 7976685aac4c3db1a603840d9e0112bec6bab32e.nq.gz
    ├── 7a1a0298b0ad53806158ec56db9e8f90e1e5bb49.nq.gz
    ├── 7a547b331d6a0df5a9301325ab0891a4ce36de9d.nq.gz
    ├── 7be3cc8ba17aceb6e76ebac05916de7bbab7101d.nq.gz
    ├── 7db574c4d193ccc899f8eee010d9e514d5a9816d.nq.gz
    ├── 7de83ddabceaa64e73def5a418bd14b788d82955.nq.gz
    ├── 7e5a9520f49126677277a74e4cb5d03cf722fb47.nq.gz
    ├── 80802b3cbaaf4e1c1bb1a65199e5cdf370eeb033.nq.gz
    ├── 8331a2fbc3af87a5484e052d00fa862eb6a51d87.nq.gz
    ├── 83ae4718a4e11e3dde4bbba1cf9f3f6a00d3e1a1.nq.gz
    ├── 885be51125c112061df22ad554379bac5ffea58a.nq.gz
    ├── 8d7ea14f67fc6ed2fc5a6762a491abe1feb88626.nq.gz
    ├── 8e9393b97ab39dd6356d4947e7264398a015dfd4.nq.gz
    ├── 8f48f86cbbb6cfaca91a4b600bf6a4b6c761108e.nq.gz
    ├── 9397062c32a36b356927aa6cfd3ba17f53b1362a.nq.gz
    ├── 947caf48e146d0697241f7011f44bfe480fc4d27.nq.gz
    ├── 9506750e7d404a3ff3eda21cc9837a85f208e16e.nq.gz
    ├── 95323f9814f01a8f39ab5102fe88776d479bdb5f.nq.gz
    ├── 95699854c9d2d41e7ef51b60f289018fa75c96d5.nq.gz
    ├── 95d54530f54924f2f91d8964bfa99ebb889eb49a.nq.gz
    ├── 9633c91ebc65cdfab5c56224c48a9c39947d50de.nq.gz
    ├── 965716ae79ad42bece733de0fd12ceb81cbd2160.nq.gz
    ├── 98519f2cc056d610f814bf9ef8a1beb4ed3d6ea1.nq.gz
    ├── 9a951eb136e972a85a2407813efa66f37a1e4b35.nq.gz
    ├── a25f26b4b25b5a076d59cf216e242713199fc637.nq.gz
    ├── a34743ebdff9ef77745c178f34a72e7e0139b2d3.nq.gz
    ├── a5dc4463751ce2e8bc4ebfa1f02769e4c9e96e15.nq.gz
    ├── a687184c71b4521651fe52414e25e40b604a0aee.nq.gz
    ├── a7c376d0fa8e999824d409ad471b6ab0ced8522f.nq.gz
    ├── a8674f6d20a619df997f22fc7f2fc26a37f76c39.nq.gz
    ├── a8db6d1eae749094a537eba53d1b7db53bda0221.nq.gz
    ├── a9a10c797915afc532395678cedfa6d69722b128.nq.gz
    ├── a9aee4e372642512db61614798c4828e7a9ccad3.nq.gz
    ├── aad2c41645383f315b753ecb8a2e0607a8fbdd6e.nq.gz
    ├── ad7d733d6fb716ff7d6b857ae7f4b603fededcd7.nq.gz
    ├── afa31745705e297cf6cdba2e46cc1ed0f13685d0.nq.gz
    ├── b02981cc06ff103d95184022ce7503d0eabcda59.nq.gz
    ├── b0ac7fe066066f524899a66369db94bc5fb97658.nq.gz
    ├── b138ad47ff95b4ccbe237a66b09c11a7e239921e.nq.gz
    ├── b3397096525182ba63725abf6ffd49fd5ab35f2e.nq.gz
    ├── b42697ed19cddff5b8eadd6bdcf098817e232e47.nq.gz
    ├── b8250c5a17bbf74410a76b12c6433b8fd2ea53a6.nq.gz
    ├── b9f873d94149aaf821c06e1f3b0f0bb5afeac8a0.nq.gz
    ├── ba5617684470322ec0e2b9863418e19647d0db0c.nq.gz
    ├── bae930f0ee991c9b9bad3a184ebdf78f3ee9070a.nq.gz
    ├── bb195043cfc07fa52741c6144d7378b5ba8be4c5.nq.gz
    ├── bb6c499fd2954172c97edaee6852fa68d0959dc9.nq.gz
    ├── bb7513c1f8bf8dfd20d1ca2297c2ea6fcdefa7c8.nq.gz
    ├── bca1d2c6a669c770c2136c3b72c4ebb926f9e4de.nq.gz
    ├── bd8d5032bfef3f080f36edc76692322c344c4d01.nq.gz
    ├── bf3d7c9a97b8c3b2fd79755b4fb5d910aadd6264.nq.gz
    ├── bf9667a38eded0d691306755e435e6fd368af1f0.nq.gz
    ├── bfdc9877d9acc165c0342befa33f2e8f769538cf.nq.gz
    ├── c42455171433a6dd98dd8c0fcb5598eb0e24bbae.nq.gz
    ├── c4ad09a0fd32b30051bd30158f9a588e05382819.nq.gz
    ├── c4d184d6a7096c641de5b741d43646cb346ca96a.nq.gz
    ├── c51d56a43ffa5b29eb252ad116705daef46c8740.nq.gz
    ├── c53502294a931238814ed13823f9a05f3822fe8e.nq.gz
    ├── c8f38d6057c9579f49e1ed4d970c9f0b88bf6961.nq.gz
    ├── c983e059531b953ceaae513b7fc9dbebb1826b45.nq.gz
    ├── cacc3a3caa04c63afaedbb4c4b3c37ff2f3df311.nq.gz
    ├── cc4fb1b82d3b266ec8d169a3ce75cd02ef50f495.nq.gz
    ├── cc8121a6de0e48e450f0a0ed1adea1ce5c2ea2a7.nq.gz
    ├── cdb19cb637e06d669916ee08416630ea96d0f767.nq.gz
    ├── ce09b2f650b81f12e675dda90ff0e819f2d11320.nq.gz
    ├── ce37cdc3658e407fea6b7ddc9cc1f1545411ecba.nq.gz
    ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
    ├── d2a5d3b82c5a22253f32502d6067a61fc5e0142e.nq.gz
    ├── d331a7eb2dc6c37c22153dfa5e762a2f93a7e806.nq.gz
    ├── d56bfd846119689e8d70d790e93220b42f15606a.nq.gz
    ├── d5afea7ecfc58f643d9fc8adcf65b83cd7dca3d8.nq.gz
    ├── d73aa1276b5f4e9796e175fc3e368471b2ea7636.nq.gz
    ├── d7b9a5bb0d319e7afcb95e46219a4693c2f04c85.nq.gz
    ├── d91331c44fca9f88b42c94a9ce0cdb16bbf6ec2d.nq.gz
    ├── d998fb9b3468a5bdf7de4e9e18a9c190b12d0f0b.nq.gz
    ├── dae6aa353a2d81d2ff3ba981c98b5891fc789701.nq.gz
    ├── db07eec8a13f29d987cb0b51c739e05b50294896.nq.gz
    └── de40ea7ca058e07a399acf61529d418c07eeee61.nq.gz

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

[twisted/pydoctor](https://github.com/twisted/pydoctor)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
