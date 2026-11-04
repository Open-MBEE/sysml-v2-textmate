# TextMate grammars for SysML v2 and KerML

Syntax-highlighting grammars for the textual notations of the OMG
[SysML v2](https://www.omg.org/spec/SysML/2.0) and
[KerML](https://www.omg.org/spec/KerML/1.0) languages:

| File | Scope | Extension |
| --- | --- | --- |
| `syntaxes/sysml.tmLanguage.json` | `source.sysml` | `.sysml` |
| `syntaxes/kerml.tmLanguage.json` | `source.kerml` | `.kerml` |

The grammars are generated from the keyword tables of the
[OpenSysML](https://github.com/Open-MBEE/OpenSysML) lexer by
`editors/vscode/tools/gengrammar` and published here unchanged, so the
highlighting agrees with the parser. Do not edit the files in `syntaxes/` by
hand: changes land in OpenSysML and are synced here by its release process.

The same grammars ship in the
[SysML v2 (OpenSysML)](https://marketplace.visualstudio.com/items?itemName=open-mbee.opensysml-sysml)
VS Code extension. This repository exists so that tools which vendor a grammar
by repository, such as [GitHub Linguist](https://github.com/github-linguist/linguist),
can take it without the rest of OpenSysML.

## License

[Apache-2.0](LICENSE), the same as OpenSysML.
