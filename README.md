# Repolex Knowledge Graph of google-deepmind/gbench

RDF knowledge graph data for [google-deepmind/gbench](https://github.com/google-deepmind/gbench), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/gbench
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d3e4283162d6c34353fa933284135d2a7ef3b9fe
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── d3e4283162d6c34353fa933284135d2a7ef3b9fe
│           └── chunk-001.nq.gz
└── blob
    ├── 0059319d37539443f1a1366da6ad16d458a9a8bb.nq.gz
    ├── 00c0bf61def92957d6e277375894a6704098339d.nq.gz
    ├── 00cc2acfb82a8543bc7f5087c126f6c3d759e4f2.nq.gz
    ├── 00f70a64bb11b478b79d25cab1ed28fb7b79b505.nq.gz
    ├── 0122db8b181dc3eef16be4854c178b51eb996058.nq.gz
    ├── 030db6d62a33d0cc5f759d41275b53dc68793891.nq.gz
    ├── 041d488280ecdf157d9b96a6bb49fe69be193d8a.nq.gz
    ├── 043d810059ce524711c8a0c24e91a40b80e3f069.nq.gz
    ├── 0440e40fa5f8381bee715ce77a6ca96e1875c71a.nq.gz
    ├── 044fb2fd55ee30e4eba3bfb15ac1d90053440ba6.nq.gz
    ├── 04b8a1edd4f76bc63a5dc83d19409eb296bf5bbd.nq.gz
    ├── 04e1e66166e0dda4228360c3f94ba2d141eb92c0.nq.gz
    ├── 04e56ea364b9273cccf19874b4e73b42aeb3b9ac.nq.gz
    ├── 04fd98b404423dd03b1c234fa3c45ee2595277c7.nq.gz
    ├── 05222ab71c7a16f6ca0a8b3e74c173c6c8ddb5ea.nq.gz
    ├── 059e1d94870309baff8f09ae652c753ed5249190.nq.gz
    ├── 060dfeedf15b85c5082bf2b7a019251e0f288a36.nq.gz
    ├── 07496afd24e74a67250fd9707e6269ce91d01683.nq.gz
    ├── 07c5d5b32b8a207823cda983141f4426f43f16c5.nq.gz
    ├── 081ad8ba7ed00f70edf191ada7da7829b0c7ca17.nq.gz
    ├── 084546209d46bc0c26b66cc02e92b467c50b5741.nq.gz
    ├── 08a12d65d8ef15343b0effc8fac5e882a87b93f1.nq.gz
    ├── 08e17f5068db61c746be606211962eb1c2519215.nq.gz
    ├── 097978cfddced7353ba8d3f4efa9e0688aab7c4f.nq.gz
    ├── 0996ffdcd7eee1bf26accd18e89b13f0dcbf317e.nq.gz
    ├── 0ae7d3a549c605fb1e0d1c4d305d52b0ddf1e838.nq.gz
    ├── 0b07dbe5ec1cd6f4302540b2708d372cc97bab6f.nq.gz
    ├── 0ba026c75f23116a0269a7621748bd6565b3fe8f.nq.gz
    ├── 0c08a9dea31a0606983b768844fa39f6d180b7d7.nq.gz
    ├── 0cdc416ae946f413b5613042890531359de3d5e9.nq.gz
    ├── 0d21f33ed868c103d5f8ad6618c01df7ec9003c3.nq.gz
    ├── 0d28872bb3b66ea041719c89aab4792cb51e2dda.nq.gz
    ├── 0d71fa11ee39dfea7f0707cfff2a2bac976b2011.nq.gz
    ├── 0deae0979c8ffdd81d81d4b8a1dd5f6cef7d1130.nq.gz
    ├── 0e1a7e3c1a7684ad6ab27c44dabf3cac90cdd771.nq.gz
    ├── 0e7d9ee7b516e11dd5f6d04a4d1e1f6bdeb955d5.nq.gz
    ├── 0fc4ce28da2eebe50f6ff8fd9d9127ecd6b03c7f.nq.gz
    ├── 104eeef2bc24fb0c84f8fa83a6249564a9d83540.nq.gz
    ├── 108e88548e68d0817d55901c04cc033374c1da41.nq.gz
    ├── 10cc86895df9ffca77c6c082325efdd7895600dc.nq.gz
    ├── 10fe4cd83d76214bcfdc4fdf191954cb2b96508f.nq.gz
    ├── 11053c376b179367ffedfae816f9162ee8f76d0a.nq.gz
    ├── 115db35479cfcd3df420ac4015763427d0e028fd.nq.gz
    ├── 1182f23e92251111f765131e760855d333c47010.nq.gz
    ├── 11ff67122e85e94cb49f4552d60d25a53bf405fa.nq.gz
    ├── 12197e4f7674397049de92441df9e6c6e73ed978.nq.gz
    ├── 127b6bf4340a653efa9ce8fa213b05119b04bd5a.nq.gz
    ├── 1391e3cdb31d3cb1daf43b56a1843173c3038aae.nq.gz
    ├── 13e2c2f617cd0aa0fc33742f092ac125a3b49d01.nq.gz
    ├── 13e86610c8b88e21174897339df302f98c155b05.nq.gz
    ├── 14ed0caa84581423c419c55c94fc3a1a54667531.nq.gz
    ├── 14f4d41bd96874c829561e4ffb2b6296d6f1e556.nq.gz
    ├── 15b6df8b1f1bbda9174b52a7cd12343b79bebbfc.nq.gz
    ├── 167508eb066a05bbb1468fea7aad07fcaaa7f56c.nq.gz
    ├── 1735f4185199c53fc26510567cdd13faeede21f2.nq.gz
    ├── 173d70fcc7a3e83f68763951fd5af4cecaf22a95.nq.gz
    ├── 1741d728eb2b420ffc91023e0335dc4572c29760.nq.gz
    ├── 17a9735b15bf2aa53bda9a2eb0b08b764a84adab.nq.gz
    ├── 17d0effd0917e9e692bd9c66898fe96598590b05.nq.gz
    ├── 1804536c58ada3ab296f58f5e30a4e436eedaf1a.nq.gz
    ├── 18b8342b6d02b62c05e60b1c4712d75c472218e5.nq.gz
    ├── 1962a53fe9a7fa17f74c3bcf53e4bbb712418f85.nq.gz
    ├── 19ea5ff473e75f2bfde7d8c60178119d594d6ea2.nq.gz
    ├── 1a8fcf160587a18351fe530794417b216501c8a8.nq.gz
    ├── 1ab952984a565dc999b64b137695ec4b45db9572.nq.gz
    ├── 1abe7cd2cb77361822efdf4add413def6e12f623.nq.gz
    ├── 1af1115efb198c17a77bca948a9a8985aa2c33b4.nq.gz
    ├── 1afa84e1a79dbc70547d66336009362c7f6d553f.nq.gz
    ├── 1b9523953f4fe02323a7e57489bf0cadcbe9e116.nq.gz
    ├── 1bb7eb2fecf6a7d27225fb1c7e4965272dac4640.nq.gz
    ├── 1bcc7f682f0278d0550b1625992196206d7f0dba.nq.gz
    ├── 1c1133f0c4044e50fa1b1d6a7f0bd7cd195cf535.nq.gz
    ├── 1c869b3c2e5383f21c3e878c826d8ae84ca40d83.nq.gz
    ├── 1daa4d976e9c041da50e1bc4362358fbbf87e0c7.nq.gz
    ├── 1dfaa037e8269f3c9a50346ce64a9b835bbd0dec.nq.gz
    ├── 1e6326fb8e10c0c0f049348d6b00046c246e9bac.nq.gz
    ├── 1ea8347760837ce79d0f0235fa7109650da9bf2c.nq.gz
    ├── 1f0c53696a08879f87b2d89d616caf9dddff3291.nq.gz
    ├── 1f151ccf5aa9e6ad9418fae27422a327190442a2.nq.gz
    ├── 1fbd7dcf3a340a8750fab3eca94468d063ed4c08.nq.gz
    ├── 2008ca7785a7933443c6acfab79a7f6328dd25c6.nq.gz
    ├── 21556943ab136f54713634619f2cf3db2103af95.nq.gz
    ├── 21655d5fecd96690249dc0767c0b43b4b65ec702.nq.gz
    ├── 21eb778b0ae15f1c2386a96df6eee325a3706792.nq.gz
    ├── 226b299416274d37e3290b3bc22062ab69f0d51a.nq.gz
    ├── 24876f123299be418602a404d581bb100a8ea869.nq.gz
    ├── 24ce6edd4024ffcd9a64ef4d1740ba5317fb380e.nq.gz
    ├── 25801a7799d912c98afcc1ae39b37c3c3d1e408a.nq.gz
    ├── 25856eb03e5abf1afe429d4dcee63339178facad.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 263012122eb84bffbeacb46ea22b4f401b5b9ae2.nq.gz
    ├── 26b5320c5a302ae1488efd34cb3905ea713c3a57.nq.gz
    ├── 26d65160404cb89542661c4bed2e73b8565ba6ae.nq.gz
    ├── 2701add43687ae483ff200dac264df41c67dd4c4.nq.gz
    ├── 2724301281b8cbb7019ccdcfe22805921c1173b5.nq.gz
    ├── 2774910d4bf49cb200b569aeb3f9b5b597b31e58.nq.gz
    ├── 28972eba81aac25c5b7fd8432f77639216532585.nq.gz
    ├── 28e8d2098141a43585f054d136f88a05be92e86e.nq.gz
    ├── 29570d0f890114bba6c13ffbc74fae8ee5225db5.nq.gz
    ├── 29587ff741955bb70892b34d2c512885118df86d.nq.gz
    ├── 2b51a615b03ae45252e67aec4f2f2bc6eb319396.nq.gz
    ├── 2e2fcc011349b8d5baa11bc865548a7d8c7beb5d.nq.gz
    ├── 2e32a59cdeaac6ae735c61e1270b7b3934faf7cd.nq.gz
    ├── 2e9dbd06ab995badd3b7a5f6e14789e43e652e63.nq.gz
    ├── 2f29c137b17d8d9ee50ca965f2ae91b684d521d4.nq.gz
    ├── 2f69801ddf04506519d4c8a5f525e3edd8060dc8.nq.gz
    ├── 2fafbbdd8022582a7e9fc90871c0e43496b1f721.nq.gz
    ├── 30272c1f37e277791aae190796cb1b23a61f5ab2.nq.gz
    ├── 318d9f722ebcaf79193810f4da5ec30ebd671b7b.nq.gz
    ├── 31ace7965290e548bd83f953201fc6259e21e25d.nq.gz
    ├── 32244a8f49d9baf9ac01652222b9d3437f35afe5.nq.gz
    ├── 32261427ca2d93f704ec9c7f7fe32d41188e4333.nq.gz
    ├── 3240dbfd05adbed3186ea98846e00348af5abf69.nq.gz
    ├── 3278ad3ac60d71b8929eafab851c1cc956083f9e.nq.gz
    ├── 336d81e54bec61ec87a28e668e5037bad5a1a7a4.nq.gz
    ├── 347309d9790105f60970df6ab83834840da2c177.nq.gz
    ├── 356d580f960a4ab0b419cf2ce1caafc518ce7d9b.nq.gz
    ├── 35bee407924ece950383ab603d75a27324da6461.nq.gz
    ├── 35f0a4b0aa9ab4dd5d10f1e66198fde5291edbde.nq.gz
    ├── 366b690450ec878c5657ae66ad44abd6152886ee.nq.gz
    ├── 3762d3ef19d6b7756f351976e77eabebb9e95ac0.nq.gz
    ├── 37b36eaef4838874a810a10c2cc7d4b04da45a8b.nq.gz
    ├── 37d8d3aeaf1031f9812ddc9368c62e477f75a561.nq.gz
    ├── 382ecb71fe98f5b660efce58d9daefa045bf1f08.nq.gz
    ├── 38e0f0ab82567e44440bda85d99f26e752f3ed83.nq.gz
    ├── 39d78463138200ab756c6639a4a9b54b88280231.nq.gz
    ├── 3aa55ed1c999cb4cec2986a496b1d04d9932d988.nq.gz
    ├── 3ac051a18b0ef43cf5ce20c367dd234ace8280e8.nq.gz
    ├── 3b4b24738b8d25be131f2fadee102bc5b1021a2f.nq.gz
    ├── 3bca68ac4cb90f903a714c8b663e00cbb9cfb0e7.nq.gz
    ├── 3be4835ec3e841b50cbd25240dcd132c84939c1e.nq.gz
    ├── 3c28f42433510cff0950e16add00a52dd513b8bd.nq.gz
    ├── 3c3d4f05b223308ec96f626431c924abed39d3d8.nq.gz
    ├── 3c5b40e4b04cd549cb55be1e1760720b8ea7ccf7.nq.gz
    ├── 3d830b88b640af05bc3cab3a2199227625ebe28f.nq.gz
    ├── 3e84c2f600242fa4d0ed2cc23cce24a088d79451.nq.gz
    ├── 3eb55a4580468085e60a8a4a48c372dfe8b14d0c.nq.gz
    ├── 3ee1c6e3030c8a607ee5e5679cc144d4a677eb5b.nq.gz
    ├── 3f73d3790b219659dee7638233470e715bd2357c.nq.gz
    ├── 3fd68713f46c96fe3bed6b819af98c17820debc3.nq.gz
    ├── 409ac83beaddd69e0c47218617ff92993adfdb69.nq.gz
    ├── 411633642aa03e470010e6528efbe129c4bf89bd.nq.gz
    ├── 415bc821cfbe2c4b86a448c806fdfdde3bee200e.nq.gz
    ├── 417984bc60cc5b562f7819cff0ba8004e25a692c.nq.gz
    ├── 41f5fd16949ac4042e205a3aa29ff597fc723d8f.nq.gz
    ├── 4207bdd66e7352ef9fa8d9aa427ce4f7765eb747.nq.gz
    ├── 429eae8fa69c6716e29940851fe598d36243a35d.nq.gz
    ├── 432acd246af16372f85caa7b2ab0e686306419a2.nq.gz
    ├── 4387987e9f93b074f493fb4905d4da9ac9ff2fea.nq.gz
    ├── 43967f069386f2acbe50c03658dce04be03ef8ad.nq.gz
    ├── 440cf8f014c130def545e52d5ca62eacb531d893.nq.gz
    ├── 446bf29f4bde3fa7bc8db95147a3cd6f56db1f8d.nq.gz
    ├── 45546189b7cbd2c4e93e4351a7864a2ae2e9342d.nq.gz
    ├── 46a7ce61af78cb3ee509f1197c55fdab49192394.nq.gz
    ├── 475a19ede12bfe4faad101af00d199ece245d7f6.nq.gz
    ├── 47d4259a9f375aeb3781b89b754456f14dcdca63.nq.gz
    ├── 47f002ac6bc4b7bd36790b25e8651b64ac0fc421.nq.gz
    ├── 4888960e0e4f8260e7fc202ab9689578188864c0.nq.gz
    ├── 489f174c97593f3dec5eb21f86f52d9e1719614f.nq.gz
    ├── 49f40a0b5b33026d70483bf11f54c4884b871d9e.nq.gz
    ├── 4a69f65b71042fc33a5e2100e225839a5c86c01d.nq.gz
    ├── 4cf26998378b8a029fd958675eb27547a45ba886.nq.gz
    ├── 4e3bd8ba6345c9050e67fcae8917d96f6b4ec455.nq.gz
    ├── 4f3a962c030b5020f1b78f58c09de36c23d1f00b.nq.gz
    ├── 4f4b237a2320bd4a51c1c7724bf81367a3f75688.nq.gz
    ├── 4f5374779abc551d3c65cfb32293bf4a8833ffd2.nq.gz
    ├── 4faa90d322735211134973e616818e4658cf7842.nq.gz
    ├── 4fd6f71ae7743f3eb9a888280c77a7c87c05106b.nq.gz
    ├── 5000e93fa1906b9c5be56d7f9b5291a6104c59c7.nq.gz
    ├── 5084459105510b3ee9cdd4652f5c9c03056ff395.nq.gz
    ├── 50c7d9f21477cbe1d7f7ef8e993354073a94279a.nq.gz
    ├── 51ad040c9bc5282f9e29d40ef8b867e07aa51018.nq.gz
    ├── 51cbcf88d9545f76c8af9bb3b0b68d67aa39e68c.nq.gz
    ├── 522fb97e95f61ce0de58100109c51585cc0aea6d.nq.gz
    ├── 529436e5c739741a0c56e25239cf49ec56db2835.nq.gz
    ├── 52a6fea106def1b35c596c125812182193ab0ef2.nq.gz
    ├── 53e2d33e3357571c8555b49d27985a66cecaf198.nq.gz
    ├── 5407fac3d2a0feed823626723d8a1497c78e8747.nq.gz
    ├── 543f1635adfa3b2f45d8c75b04c533ec7936101c.nq.gz
    ├── 544b5f133c0c21a5ed0ed973c8d3ffb89b0b0897.nq.gz
    ├── 54583ac9f6ea48e1aeef904e9052efd7c9048357.nq.gz
    ├── 55b711babae72759e135d405dff821d18594789c.nq.gz
    ├── 5624f802890a67f8ba4c29325f64864d3514f03a.nq.gz
    ├── 569d02cccce2025bce23568c6c106f08230e49c0.nq.gz
    ├── 57a08e18583897957cc13aa82747e3bbb3d83a03.nq.gz
    ├── 58db38b093d6a150412376f3ab8bebc442c7bded.nq.gz
    ├── 59ebe1c88860102a0b80124be7933d1449ede75e.nq.gz
    ├── 5a417142a54ded51c9ef429558d90d1b655789fc.nq.gz
    ├── 5acdec9f9ce550c655db8316f4c98bbd36f41305.nq.gz
    ├── 5bcc5dfd44ba5dc3d1d0b7d2488832786a570434.nq.gz
    ├── 5be86e456639e21cf9b8d1290619c53867cd6950.nq.gz
    ├── 5cace4a0579880e5925d7a0717b2854819965b47.nq.gz
    ├── 5cdb3163d76c4ac5cde37483656dc034b70bfb93.nq.gz
    ├── 5f400cfd5fb0b3a7d20f669fb9f36faa3ac40c20.nq.gz
    ├── 5f69e145974e040a07bc20ad1e10493acd78e403.nq.gz
    ├── 60859835b89ac5941ea618b1009175b67f7c18f1.nq.gz
    └── 60a3a3296720454e1faf93c3bef9f01abe18c316.nq.gz

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

[google-deepmind/gbench](https://github.com/google-deepmind/gbench)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
