# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > async-functions > await-function-declaration-name-inside-async-function`

### `ast`

```javascript
JSRoot {
	body: [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "foo"
				loc: SourceLocation es2017/async-functions/await-function-declaration-name-inside-async-function/input.js 1:15-1:18 (foo)
			}
			body: JSBlockStatement {
				body: [
					JSFunctionDeclaration {
						id: JSBindingIdentifier {
							name: "await"
							loc: SourceLocation es2017/async-functions/await-function-declaration-name-inside-async-function/input.js 2:11-2:16 (await)
						}
						body: JSBlockStatement {
							body: []
							directives: []
							loc: SourceLocation es2017/async-functions/await-function-declaration-name-inside-async-function/input.js 2:19-2:21
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: []
							loc: SourceLocation es2017/async-functions/await-function-declaration-name-inside-async-function/input.js 2:16-2:18
						}
						loc: SourceLocation es2017/async-functions/await-function-declaration-name-inside-async-function/input.js 2:2-2:21
					}
				]
				directives: []
				loc: SourceLocation es2017/async-functions/await-function-declaration-name-inside-async-function/input.js 1:21-3:1
			}
			head: JSFunctionHead {
				async: true
				generator: false
				hasHoistedVars: false
				params: []
				loc: SourceLocation es2017/async-functions/await-function-declaration-name-inside-async-function/input.js 1:18-1:20
			}
			loc: SourceLocation es2017/async-functions/await-function-declaration-name-inside-async-function/input.js 1:0-3:1
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
				message: RAW_MARKUP {value: "Can not use 'await' as identifier inside an async function"}
			}
			location: {
				language: "js"
				path: UIDPath<es2017/async-functions/await-function-declaration-name-inside-async-function/input.js>
				end: Position 2:16
				start: Position 2:11
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<es2017/async-functions/await-function-declaration-name-inside-async-function/input.js>
	loc: SourceLocation es2017/async-functions/await-function-declaration-name-inside-async-function/input.js 1:0-3:1
}
```

### `diagnostics`

```

 es2017/async-functions/await-function-declaration-name-inside-async-function/input.js:2:11
parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Can not use 'await' as identifier inside an async function

    1 │ async function foo() {
  > 2 │   function await() {}
      │            ^^^^^
    3 │ }


```
