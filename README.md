# Repolex Knowledge Graph of wandb/wandb

RDF knowledge graph data for [wandb/wandb](https://github.com/wandb/wandb), parsed by [repolex](https://repolex.ai).

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
rlex download wandb/wandb
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2e10e7dd5118f56db75e43d17b959c26d357dd2a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2e10e7dd5118f56db75e43d17b959c26d357dd2a
│           └── chunk-001.nq.gz
└── blob
    ├── 00186e7348f0d8915d5ed0ae303adbacbebfde18.nq.gz
    ├── 002cb1a41c645a97d278a96f492505abfbdf52d1.nq.gz
    ├── 00509cabac6e9c1cf63fe32766a53b37ebe5f856.nq.gz
    ├── 00c02027d776fcb88f86b2adb2722c0332b30107.nq.gz
    ├── 0110db40cab01d34e3feb3570c29a9b5067a69bb.nq.gz
    ├── 0129d8351ae13a7b14a92af0c196a659468d5091.nq.gz
    ├── 01cfb8ce2874a86f646c055127b8f568b3a55681.nq.gz
    ├── 0270298dd4d62e109158b99945168033488bab86.nq.gz
    ├── 027807a2f16fa02015bbda9666c085583ff67681.nq.gz
    ├── 02e8a24d9fbce482e31cde126d8407586a61b3fd.nq.gz
    ├── 04c3706c05f999490f90e50e86c2323ffe894397.nq.gz
    ├── 050443d91efa3a90e6067a66bbffdd559a26f24c.nq.gz
    ├── 05e53473af04ca830a5ad33a5c6c6a8bb84e5e06.nq.gz
    ├── 06a3782da2aec16c743389878202a1186ff89c65.nq.gz
    ├── 06b9311a207b5d53140569d6c9839eb1e012a48b.nq.gz
    ├── 06bcf04287e343f808b67ab5b6d51d5dc435fa1e.nq.gz
    ├── 06d327f1cfc6879a27e61eb14a3c5c6d19f12e1c.nq.gz
    ├── 072547ab219e907efede3399d660817926074490.nq.gz
    ├── 073e4399860bae2001d6159a05ce9bb0dd5cb267.nq.gz
    ├── 078f649b44d2e25eef84b90db70c1e15f0ef8a8a.nq.gz
    ├── 081633ebfa7bab9488393f7b747100381b824618.nq.gz
    ├── 0906b797eea82a9decd01756b369ec298b6b0aa0.nq.gz
    ├── 0a110ec14cdddbe944dc16ccfb012df2cc5ab8b5.nq.gz
    ├── 0a7801b68334552ff59858be1513a4f1e65136cf.nq.gz
    ├── 0a7ead2d5ab8e49ce4d032ec6afabb9e9333a1b8.nq.gz
    ├── 0ac5014e61452c88f0aac737c67a2b35a5f18b50.nq.gz
    ├── 0ade9499472a8bd6b062656186d3d27a5a97c232.nq.gz
    ├── 0c8635345f13c106742bd42766f0938906cc12a6.nq.gz
    ├── 0c8d464383f61a95bcfa20dcd612ec0336d28114.nq.gz
    ├── 0c99af149ee8afa9f3de871d60a316cc2450f401.nq.gz
    ├── 0caee20ab33ea0dd6f79bcd105d0b3570ae2f52c.nq.gz
    ├── 0df827e643860f77fdcf52eef0d00c7849e7c2db.nq.gz
    ├── 0e162f02362caf9d202442feaba791fc8171e460.nq.gz
    ├── 0e2553f0fe7a6c4024e418e0a4ea4e7a40fcc909.nq.gz
    ├── 0e4fac0e67f4dbc58821f68fcd53f8564b47e17c.nq.gz
    ├── 0f7e5dfde5f018c3d1f8f823e1d8f431a2654e23.nq.gz
    ├── 0f952c0bd9eacae89b8e1218d749ed6c06d12190.nq.gz
    ├── 100eef9573856be771897958c425f9b43b94cc25.nq.gz
    ├── 10d692213bf6350c07308f569f57771af7a9135f.nq.gz
    ├── 119454eb31b9c5d4e5e50e5c35fbcab62be629c5.nq.gz
    ├── 11fce5e0fa698fa621de3db4d9da15771b17d475.nq.gz
    ├── 121e22bfcf8b99718b99ae9ef7b82874a3d311c8.nq.gz
    ├── 129649aa8aa0e205563711c7022d9825216dd2b4.nq.gz
    ├── 129fec111bb76d4e7dc0d9b6ebbc4d809a0c3e60.nq.gz
    ├── 12d3055e8fe48847013c782bd8686ab3b686201d.nq.gz
    ├── 133fa41013658001c1c66fde570d638875dc180e.nq.gz
    ├── 134894ebc5067e5328866d94decfca4b61ad9dc9.nq.gz
    ├── 147fb616515864163af85d5eb6d909e29aeb60a2.nq.gz
    ├── 15e61aa51cdaa88d063d7794d6a0d223a797ff24.nq.gz
    ├── 15eec7ff65ceeb19c3dc2f392648d7ec54631202.nq.gz
    ├── 15f71d8303908dbb2619fb40d9af8874ac7bafd8.nq.gz
    ├── 168ed7a9b36b2b69b17ef66d13e92bf5d5c3f8ad.nq.gz
    ├── 16d1d7c1d32cb3cd084e43eb011f1ea99123c5d8.nq.gz
    ├── 16e9d2034f92a7ab7416d57c2de83463a8666c9c.nq.gz
    ├── 16f35e358edf8de08ea081db8a8692879c7872fe.nq.gz
    ├── 172d32bb61d4817630ab4f3987de480332f5ef25.nq.gz
    ├── 174232c76e0439b91eea77a610587021179e27af.nq.gz
    ├── 1863c76724d8bc7ace20bffed9dd098742f66c7c.nq.gz
    ├── 187d21a53442054eef51ee163368344db762d9f2.nq.gz
    ├── 190200b8684807c07c4a15b3e954b911a83ab494.nq.gz
    ├── 197051fcf23e383c4b9440186aab00d6bb0b53b5.nq.gz
    ├── 19a2ddc7ca60728e7accf5cec5b646f2a0c7f694.nq.gz
    ├── 1a0d2d076032d30dbdf19eff2ed77855c7cbfb8a.nq.gz
    ├── 1aa45ad8aced101f4bec07df6f1d8972dabffd34.nq.gz
    ├── 1b330a9b2767ddf540cafc2670e7e1b605f54557.nq.gz
    ├── 1b5d8289f6b2f64ae8411ea67a45b43bc190e03f.nq.gz
    ├── 1bbcac79f89ddcb69fdaac859a495aff95c893fe.nq.gz
    ├── 1d15c0aa57b20fb3ec2b32bc699b1a9b7ce7bf92.nq.gz
    ├── 1d1db8ab1d2eb9739e00586bca6f06c7e6f6590b.nq.gz
    ├── 1e37162ed582350fe115538c2ed5deebd65efe92.nq.gz
    ├── 1eb8cae9b5792958b3d9dc62ae94ffe5300bdf6a.nq.gz
    ├── 1efc02734e063818485d6b0bcb715e3777b77b9d.nq.gz
    ├── 20ad121e3de1b056b0d221980fadebfed784eec2.nq.gz
    ├── 2195a46485f0dd7f195c310ad8597d00b19a0a99.nq.gz
    ├── 21ceb04db959c484dc002f93cfa0169832591372.nq.gz
    ├── 23e0ab049178bba293a3b58598a43aa1643a2263.nq.gz
    ├── 23e6619df114b5a1fcc3f3f78c7778a5ed211d9f.nq.gz
    ├── 25777cbb99b7956dfefaf355b1d49c972944cd2d.nq.gz
    ├── 25b554f2c4df9207646d8d32287cffb36e709d61.nq.gz
    ├── 25dd4d0197c18603c715b3d37776543fb28b5724.nq.gz
    ├── 26370b3fdeb8213ed2fc712f2d47ad6b76941a69.nq.gz
    ├── 26772f89afdf7cfb6940913b0d3a47f6e3af764d.nq.gz
    ├── 26bd4e1b3838e2645c28547d2365eb4fd2f0300d.nq.gz
    ├── 2701cb5d2e621fceda839d11edaba207234c65c4.nq.gz
    ├── 288014ad583d103e96e6054fe42f38372e6286fc.nq.gz
    ├── 2904b1d13a8ce8a1a501786df5906d7232534a17.nq.gz
    ├── 2950db236fd440f733884166aab1a65bb2441455.nq.gz
    ├── 299692da6bb7c1b24a87bf6ff02194f8578a48b1.nq.gz
    ├── 29b28f3d3cf9641d8259a1b232863e33873f50bf.nq.gz
    ├── 29e7e97c8000a24040fe639bbc9caefbfdbbd584.nq.gz
    ├── 29ed7d8fff67f3e705c0338415d1bf9b12042c86.nq.gz
    ├── 2a209c389864045808c1629fdd1c56c6a254f994.nq.gz
    ├── 2a3f8716076efe473c4371f909b754094cb19835.nq.gz
    ├── 2b3f6566507f330cf0acda42ce871d1a4aec3d51.nq.gz
    ├── 2bccd31314bd393423701a4a328b21abf461790e.nq.gz
    ├── 2e671feaab19c6719731f9a4047f29e124288054.nq.gz
    ├── 2fad763dee32433bf587250e46f626ae6bbe178f.nq.gz
    ├── 2fb1830a7a86dc85971d046676fd65ddb04ab0e2.nq.gz
    ├── 2fca694e2bad4d004cfb87fe2b3fc76244b45d9d.nq.gz
    ├── 2fdeb2824bd5e381164f219d60d9920b0ef76691.nq.gz
    ├── 300712dfa7509821574bbd95187dd56735226f1c.nq.gz
    ├── 303a08e43917f4b9435471737cf0a451610f405e.nq.gz
    ├── 3089f01d947f0007a54873ae5b4c63fc193e40f1.nq.gz
    ├── 30985cbd642026b63e206bde6cedaa67fdc94fd7.nq.gz
    ├── 30e6546cc2873d017ddccdbfff3a615d29459f7d.nq.gz
    ├── 3120cf5322dc8153f2e2783991411ddfe8b7ab57.nq.gz
    ├── 31b677f99fe6b5ed943d80147779fd5d58db70f8.nq.gz
    ├── 328668ac88f7cb5fdce6373a8ba969eb15377b1d.nq.gz
    ├── 332da4a45496b501778405dd9948e34aafa03b73.nq.gz
    ├── 34123e1b1a2a3541c4bbfd9b6773b0f0e3808e11.nq.gz
    ├── 346041fdc9c1e3e1151f64e61ffd68c3dba3f14b.nq.gz
    ├── 34857a4053ac3d699f447f927b7d6d0ea8d6ca14.nq.gz
    ├── 3621d910423282b79f6f3f8b0bba07c70366c588.nq.gz
    ├── 368b0cc1126e55e3fe48688d3dcdc1b826a8df20.nq.gz
    ├── 36ac1c115e4e69176a51d4e8b3cd7097860313fe.nq.gz
    ├── 37326dd2990aadda5591d1410a2585ea6c441f57.nq.gz
    ├── 373aeea364d25ba214060a1f1bd8ce1ee3a47c40.nq.gz
    ├── 3757133825aab1c4d0922a935fbc7b4f564b4469.nq.gz
    ├── 3765e07cdb0842438aff082dce7df9186e36e66f.nq.gz
    ├── 3770e76307d734f09861d348f2221b245eddaae0.nq.gz
    ├── 3781835226572c36a862a14bc319730770be9d4c.nq.gz
    ├── 38907d82d47158edbc2a9e59c192148dd710c98f.nq.gz
    ├── 391aff6d42f60d4594dfd04eee64d0fab3e71a04.nq.gz
    ├── 391eefd8ff130251f5f03a02bfa2bae7c9a72962.nq.gz
    ├── 395368c1ed7face3b9a2128d408dec5b107da9eb.nq.gz
    ├── 39c41ed57e06badc776a7235b519928fb4cc48f8.nq.gz
    ├── 39f60de8dc3669264db38644d3b09cd727d3c7d0.nq.gz
    ├── 3b0a3ae962cdadde195fa31c6efb4f3d0cc07d5b.nq.gz
    ├── 3b8431b06243697b48682733d342b0c5c01cf2d4.nq.gz
    ├── 3bdb5679e6804d26abfde9997182ffd662f60b0b.nq.gz
    ├── 3c68d8f8eb80744b8de83ded805fe63f72481c43.nq.gz
    ├── 3cd55beb4b97319eba49344e5185d567ad76323c.nq.gz
    ├── 3d18b209bf6a2675d3ac5798d656818471519e32.nq.gz
    ├── 3d32e3ad6f6f5dc67faa40ae917887d7dd161057.nq.gz
    ├── 3d8e075fc6485889844242ebdb1a87d356678f34.nq.gz
    ├── 3e3f350bfbb9bdc092e87ac2b2d22c8db7073799.nq.gz
    ├── 3f6e29cc35ec3d248cc1816687ba6831afb3825e.nq.gz
    ├── 3f90100fae2cd95938c24ad5cadd604d9068d69d.nq.gz
    ├── 3f95f99c4d93b83bb37010d969bcbd0b932a87c1.nq.gz
    ├── 4003fb87ded1706092fa2357841f732f5cb3b124.nq.gz
    ├── 40163757740a069798d8af57efc197e2e46dba61.nq.gz
    ├── 414cdc36373d9e74bdf861bfc265b582baee17a7.nq.gz
    ├── 415a0e552749c357d961330cf9e6969f4a2b5d58.nq.gz
    ├── 41de387f5031fb68c1994d37caa5b01b81106520.nq.gz
    ├── 41e8c57f3311af8d0d59789ad76aff6f6d52f7ab.nq.gz
    ├── 421d07448e2dbe010d919ec29b7ff79156909ddd.nq.gz
    ├── 429e2fa4623d060c5a9d38f365d2544f04c50c5f.nq.gz
    ├── 4410c755772eead22a846cf25a5beed6fca6cc45.nq.gz
    ├── 4445e94dbb0120d2de7dd5ed30646f8a5c1d2ec9.nq.gz
    ├── 44c16d0403a7f6832964933b536e060948eca0f8.nq.gz
    ├── 4513a06b46b9a27f514d999fdf974486d904dba0.nq.gz
    ├── 45cf7aa18f48e77f4b78436f3a3b4a1c670814fb.nq.gz
    ├── 46d65746f9585365533861c9cbfe78459b6dacdd.nq.gz
    ├── 477f2b9792846906335774724d06a0f682879387.nq.gz
    ├── 483896a4801328b7508df0a956e430150424a5e1.nq.gz
    ├── 48fa6a9d52d9e66886feb015dd9de2aedd4f1051.nq.gz
    ├── 490e6f27ebd250b8b8e74cfebf449192a5854426.nq.gz
    ├── 49d3eb934d21aebdcdd899c2682e6991a6116dfa.nq.gz
    ├── 49d99c410beefe8964ee268b81949d1892060aad.nq.gz
    ├── 4ab72bf8ecb663d4bf322cb7cfce0133d5ef6470.nq.gz
    ├── 4b64a63b5f26c70fc9ae381dd25ca8cd2bed82db.nq.gz
    ├── 4c374708a7e2a8b6453b06b58fe7d430f3f0ccc0.nq.gz
    ├── 4d409bcf913dfde9b84f6cc53d3c980a2cbe02e2.nq.gz
    ├── 4defe2d8f47790f4fbdfeecb64894894f56652ca.nq.gz
    ├── 4e4e0bc3a3713d2c47a9b41004847af8b7a6614a.nq.gz
    ├── 4e68ed5c4ca4fabd0fa883686a5beb0c69dd67a5.nq.gz
    ├── 4ed02bb9d3249f2378846b8c658f3d240d747bde.nq.gz
    ├── 500e3e761be849f158d06cbf76667113cb899038.nq.gz
    ├── 5065f1cdee4408d7d63ff2f3ebb5f9036aaf1e6f.nq.gz
    ├── 516bf27b9040e7adeba3ff86f4aadb052810c521.nq.gz
    ├── 525bdc287b8517e0f0539dc0cf733aa5d71604e3.nq.gz
    ├── 5393b5bcd7143111f6f3e578ff157cfb1dcd3263.nq.gz
    ├── 53aa4eafd3cff7c7035502624e7d6a6ab1480b23.nq.gz
    ├── 56dde52df67856709351da2976a286e50398c006.nq.gz
    ├── 570c654ebccc4cef2a406ad7c0762cb932e867fd.nq.gz
    ├── 5714027aa6596de45a64f61602b0eec743adaeca.nq.gz
    ├── 579183a85ec14bbf89f8890cb01f3f2e5243574d.nq.gz
    ├── 57e0a376322cd73ae96b7bea41dad60f1d20e368.nq.gz
    ├── 58557a82141890ba0fe89e35f503e3f4b425b11a.nq.gz
    ├── 585ef82a2ef8335947f123dadde4d5d1aaa7c9f7.nq.gz
    ├── 58bda57e04fc1439f36c96bb1c3b86d4dd6d2206.nq.gz
    ├── 59327232085717e69daf4bd3866d8ecb9f209024.nq.gz
    ├── 599bd16cc63b5be1ee8ef98c882d24b6afafa979.nq.gz
    ├── 5a964364bdc3e52445f0b78d0d6932b28491c8bb.nq.gz
    ├── 5aadf3cac516618268f29eab261cba171aef246e.nq.gz
    ├── 5bcf7980133c41393fdc22db3bbff89be29be94e.nq.gz
    ├── 5eb06cf1a705985638887d668109494cd5ca09f5.nq.gz
    ├── 5f7a6e3668c3827f8f54240d365ed1481b2bd96a.nq.gz
    ├── 601f9a82acbec33765d0eb94588c5420186a3306.nq.gz
    ├── 6034a559c2854bcca9dcdf133dfe059ed0caac3c.nq.gz
    ├── 6035bd4c9c5067e553404a5a4bb818ef582a36a8.nq.gz
    ├── 603d1b27fca83ef4822d78cd548590da2a176461.nq.gz
    ├── 60d551185cce47cccfeab32efc0e98d5ff6e97dd.nq.gz
    ├── 61e9c403a0666fb4241deed20ca6dbb717377ead.nq.gz
    ├── 6203d828d74d7564202a97912cbda9f6afd5316b.nq.gz
    ├── 6223b0e7fde0363c69885f71eda677e5526bfcf7.nq.gz
    ├── 6341a29a125c54ae6d49977dbe2480b1544708f4.nq.gz
    └── 639bcd55e34111166cafc7e24357aebd987b3d72.nq.gz

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

[wandb/wandb](https://github.com/wandb/wandb)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
