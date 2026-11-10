# Repolex Knowledge Graph of ChadCSong/ShineButton

RDF knowledge graph data for [ChadCSong/ShineButton](https://github.com/ChadCSong/ShineButton), parsed by [repolex](https://repolex.ai).

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
rlex download ChadCSong/ShineButton
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 91983d10e451ed1a294b1556283a6ac274c30c76
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 91983d10e451ed1a294b1556283a6ac274c30c76
│           └── chunk-001.nq.gz
├── blob
│   ├── 04215c65e03d4ee2f8f483fa1a5d763dc5fa5d69.nq.gz
│   ├── 077248d4569f17f80e85aee5b4dc7ba6c454e4e1.nq.gz
│   ├── 0eb29cb919aa22ee119d53d77f5dd404ebd401d4.nq.gz
│   ├── 0ed2cc84d7c04f93b6a946580f7191e88b330f52.nq.gz
│   ├── 126d3ab43373da650d769b25a1a7123d5e7911f0.nq.gz
│   ├── 13372aef5e24af05341d49695ee84e5f9b594659.nq.gz
│   ├── 13685ca41d5297fd18726732c252f3a71b76becf.nq.gz
│   ├── 1ca6e779ff1b7b4510beafbaa2050bc891b27b0e.nq.gz
│   ├── 1d1ec2d5c11f7f2488cbb949cd02d4d7994e6eb6.nq.gz
│   ├── 27b4b7bba17b0ca46d55c275249c368e61a1ef10.nq.gz
│   ├── 2afec32b0a4f938c9e806d1aadc83d1dfb0b9919.nq.gz
│   ├── 2ce83a03e2c95159e1789550c6a94e03a72c9222.nq.gz
│   ├── 30a56f8fc8072cfa2a2069542cf78c5e5416079b.nq.gz
│   ├── 324e72cdd7480cb983fa1bcc7ce686e51ef87fe7.nq.gz
│   ├── 37eabbad8f1e379abb964d5edfdcf9a381ec6fe7.nq.gz
│   ├── 38219ce9cf8c05374e7d981f59eb3bfe221d4ece.nq.gz
│   ├── 3ab3e9cbce07f7cdc941fc8ba424c05e83ed80f0.nq.gz
│   ├── 3ec67001cfd8250d0bb08f93dc70dd1ff11efe0d.nq.gz
│   ├── 4481664b570228b71e6f197c7dd9bbc7bd8fd37c.nq.gz
│   ├── 458f97dbfde4688ddfbf63f9459384bea8b2945d.nq.gz
│   ├── 47c82246738c4d056e8030d3a259206f42e8e15d.nq.gz
│   ├── 48ba4101610152fbe7a6e89aea6b6857bbb31449.nq.gz
│   ├── 4eb32c3f1a280cebcae6acfd74a87d75056214a4.nq.gz
│   ├── 4f88c0e5202bbd433e7c206bfdc3ba4d9176a142.nq.gz
│   ├── 54ed479640c7b8259b91efe4afe92a14e5c68c54.nq.gz
│   ├── 5d9edbbef0f97fe9cc1277570712509199c1c56d.nq.gz
│   ├── 5e3d682513cfa6522533c1a5902d332c484cba3d.nq.gz
│   ├── 601ddfa8284d6d665328dc4f7931ea3c644de297.nq.gz
│   ├── 611de5c43175ae7b40938a4040ab1edb69921a9d.nq.gz
│   ├── 63fc816444614bd64f68a372d1f93211628ee51d.nq.gz
│   ├── 77ed2b95fd7352bac930c88c093bf63a6ae8c727.nq.gz
│   ├── 796b96d1c402326528b4ba3c12ee9d92d0e212e9.nq.gz
│   ├── 8046117686fb7d077606e38e2f629f002b94caa2.nq.gz
│   ├── 808175df2f690ceb2f28263606860f2e327ae6f3.nq.gz
│   ├── 87cd0e637848d5a9f0311226ea36e192da567e9f.nq.gz
│   ├── 88254c8b52786fd890dff6f551c2d4410d80db67.nq.gz
│   ├── 8a0b282aa6885fb573c106b3551f7275c5f17e8e.nq.gz
│   ├── 8e0d04693e17c9f754662321a35b6c3b38c52eb9.nq.gz
│   ├── 8e33105fd768b3f3d2d1215c6ab9f8284adb39d5.nq.gz
│   ├── 93ffff686547007ebce9291935c46b1411d6fad1.nq.gz
│   ├── 989454e978f4bd09484bd9bf7a4d25e6abe0ab43.nq.gz
│   ├── 9997a0404ea21749aace2479a34ff9b00b8f9443.nq.gz
│   ├── 9a75e65638ae97b58ed14fed2282f3c3c4c1cbcb.nq.gz
│   ├── 9aa884ac7dceda46451bb7d7dd64555c728a1437.nq.gz
│   ├── 9d82f78915133e1c35a6ea51252590fb38efac2f.nq.gz
│   ├── 9e5f6eb163da831fd247cce076d98db615f63bbc.nq.gz
│   ├── a3e24e9a8a25962996e26113cf50d18048ebb8be.nq.gz
│   ├── a9f7571445a43b07d7caa7b9b8467a86cdacfd23.nq.gz
│   ├── aee3f9a65f10d90c5209ba1fc02a33b55d8f8f10.nq.gz
│   ├── aee44e138434630332d88b1680f33c4b24c70ab3.nq.gz
│   ├── afc8925bf941fdd5f151a3c6183e15e89c6839b8.nq.gz
│   ├── bb9da4bed6b766573f59a0d361c2adabeb342a5b.nq.gz
│   ├── bfa42f0e7b91d006d22352c9ff2f134e504e3c1d.nq.gz
│   ├── c133a0cbd379f5af6dbf1a899a0293ca5eccfad0.nq.gz
│   ├── c4520502bf5a4c3f7a22db28d7cc69b8565283b1.nq.gz
│   ├── c58bff94c6baf68170acd829dc4b49c71cd64d40.nq.gz
│   ├── c72ada4a01302f875518713c66ebcf5646de9081.nq.gz
│   ├── cba1fe00afd4346ba332162fec5d4392eda9d863.nq.gz
│   ├── cc3f43393c2fddefbb84cf74a6484313b2fb20c1.nq.gz
│   ├── cde69bcccec65160d92116f20ffce4fce0b5245c.nq.gz
│   ├── da89990a54f9b30bee0249ee3ab9a2e30f7bd743.nq.gz
│   ├── de3612b6f42bcb5f35ed6ae0374966de89f98cdc.nq.gz
│   ├── e0d07aca79a69f7716c34b8be40dd022d3be5134.nq.gz
│   ├── e16047209442a4e2d8dc8a370b8587f45814cfb2.nq.gz
│   ├── e8a6008cbe2ab8e1bd90fa9f66fd3c736af0e09a.nq.gz
│   ├── ee654b13eba78567be80481334d5757c1ba12894.nq.gz
│   ├── f0bbcf896199af9a60018398c5c71a8aeedbcd83.nq.gz
│   └── f1baa7763be3e39e4654a76e3e002ca7e5156f6d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 91983d10e451ed1a294b1556283a6ac274c30c76.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 76 files
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

[ChadCSong/ShineButton](https://github.com/ChadCSong/ShineButton)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
