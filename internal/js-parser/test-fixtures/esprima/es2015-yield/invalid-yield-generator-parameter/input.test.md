# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-yield > invalid-yield-generator-parameter`

### `ast`

```javascript
JSRoot {
	body: [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "g"
				loc: SourceLocation esprima/es2015-yield/invalid-yield-generator-parameter/input.js 1:10-1:11 (g)
			}
			body: JSBlockStatement {
				body: []
				directives: []
				loc: SourceLocation esprima/es2015-yield/invalid-yield-generator-parameter/input.js 1:18-1:20
			}
			head: JSFunctionHead {
				async: false
				generator: true
				hasHoistedVars: false
				params: [
					JSBindingIdentifier {
						name: "yield"
						meta: JSPatternMeta {
							loc: SourceLocation esprima/es2015-yield/invalid-yield-generator-parameter/input.js 1:12-1:17
						}
						loc: SourceLocation esprima/es2015-yield/invalid-yield-generator-parameter/input.js 1:12-1:17 (yield)
					}
				]
				loc: SourceLocation esprima/es2015-yield/invalid-yield-generator-parameter/input.js 1:11-1:18
			}
			loc: SourceLocation esprima/es2015-yield/invalid-yield-generator-parameter/input.js 1:0-1:20
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
				message: RAW_MARKUP {value: "Can not use 'yield' as identifier inside a generator"}
			}
			location: {
				language: "js"
				path: UIDPath<esprima/es2015-yield/invalid-yield-generator-parameter/input.js>
				end: Position 1:17
				start: Position 1:12
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<esprima/es2015-yield/invalid-yield-generator-parameter/input.js>
	loc: SourceLocation esprima/es2015-yield/invalid-yield-generator-parameter/input.js 1:0-2:0
}
```

### `diagnostics`

```

 esprima/es2015-yield/invalid-yield-generator-parameter/input.js:1:12 parse(js) ━━━━━━━━━━━━━━━━━━━━

  ✖ Can not use 'yield' as identifier inside a generator

    function *g(yield){}
                ^^^^^


```
