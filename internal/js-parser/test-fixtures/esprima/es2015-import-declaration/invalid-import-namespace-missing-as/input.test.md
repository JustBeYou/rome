# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-import-declaration > invalid-import-namespace-missing-as`

### `ast`

```javascript
JSRoot {
	body: [
		JSImportDeclaration {
			namedSpecifiers: []
			namespaceSpecifier: JSImportNamespaceSpecifier {
				local: JSImportSpecifierLocal {
					name: JSBindingIdentifier {
						name: "from"
						loc: SourceLocation esprima/es2015-import-declaration/invalid-import-namespace-missing-as/input.js 1:9-1:13 (from)
					}
					loc: SourceLocation esprima/es2015-import-declaration/invalid-import-namespace-missing-as/input.js 1:9-1:13
				}
				loc: SourceLocation esprima/es2015-import-declaration/invalid-import-namespace-missing-as/input.js 1:0-1:13
			}
			source: JSStringLiteral {
				value: ""
				loc: SourceLocation esprima/es2015-import-declaration/invalid-import-namespace-missing-as/input.js 1:0-1:13
			}
			loc: SourceLocation esprima/es2015-import-declaration/invalid-import-namespace-missing-as/input.js 1:0-1:13
		}
		JSExpressionStatement {
			expression: JSStringLiteral {
				value: "foo"
				loc: SourceLocation esprima/es2015-import-declaration/invalid-import-namespace-missing-as/input.js 1:14-1:19
			}
			loc: SourceLocation esprima/es2015-import-declaration/invalid-import-namespace-missing-as/input.js 1:14-1:19
		}
	]
	comments: []
	corrupt: false
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {
				advice: []
				category: ["parse"]
				categoryValue: "js"
				message: [RAW_MARKUP {value: "Expected keyword <emphasis>"}, "as", RAW_MARKUP {value: "</emphasis>"}]
			}
			location: {
				language: "js"
				path: UIDPath<esprima/es2015-import-declaration/invalid-import-namespace-missing-as/input.js>
				end: Position 1:9
				start: Position 1:9
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<esprima/es2015-import-declaration/invalid-import-namespace-missing-as/input.js>
	loc: SourceLocation esprima/es2015-import-declaration/invalid-import-namespace-missing-as/input.js 1:0-2:0
}
```

### `diagnostics`

```

 esprima/es2015-import-declaration/invalid-import-namespace-missing-as/input.js:1:9 parse(js) ━━━━━━

  ✖ Expected keyword as

    import * from "foo"
             ^


```
