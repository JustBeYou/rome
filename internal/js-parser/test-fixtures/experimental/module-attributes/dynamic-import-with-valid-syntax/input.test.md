# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > module-attributes > dynamic-import-with-valid-syntax`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSImportCall {
				argument: JSStringLiteral {
					value: "foo.json"
					loc: SourceLocation experimental/module-attributes/dynamic-import-with-valid-syntax/input.js 1:7-1:17
				}
				loc: SourceLocation experimental/module-attributes/dynamic-import-with-valid-syntax/input.js 1:6-1:18
			}
			loc: SourceLocation experimental/module-attributes/dynamic-import-with-valid-syntax/input.js 1:0-1:18
		}
		JSBlockStatement {
			body: [
				JSWithStatement {
					body: JSBlockStatement {
						body: [
							JSLabeledStatement {
								body: JSExpressionStatement {
									expression: JSStringLiteral {
										value: "json"
										loc: SourceLocation experimental/module-attributes/dynamic-import-with-valid-syntax/input.js 1:35-1:41
									}
									loc: SourceLocation experimental/module-attributes/dynamic-import-with-valid-syntax/input.js 1:35-1:41
								}
								label: JSIdentifier {
									name: "type"
									loc: SourceLocation experimental/module-attributes/dynamic-import-with-valid-syntax/input.js 1:29-1:33 (type)
								}
								loc: SourceLocation experimental/module-attributes/dynamic-import-with-valid-syntax/input.js 1:29-1:41
							}
						]
						directives: []
						loc: SourceLocation experimental/module-attributes/dynamic-import-with-valid-syntax/input.js 1:27-1:43
					}
					object: JSReferenceIdentifier {
						name: "INVALID_PLACEHOLDER"
						loc: SourceLocation experimental/module-attributes/dynamic-import-with-valid-syntax/input.js 1:25-1:26
					}
					loc: SourceLocation experimental/module-attributes/dynamic-import-with-valid-syntax/input.js 1:21-1:43
				}
			]
			directives: []
			loc: SourceLocation experimental/module-attributes/dynamic-import-with-valid-syntax/input.js 1:19-1:45
		}
		JSExpressionStatement {
			expression: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: SourceLocation experimental/module-attributes/dynamic-import-with-valid-syntax/input.js 1:45-1:46
			}
			loc: SourceLocation experimental/module-attributes/dynamic-import-with-valid-syntax/input.js 1:45-1:46
		}
	]
	comments: []
	corrupt: true
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {
				advice: []
				category: ["parse"]
				categoryValue: "js"
				message: RAW_MARKUP {value: "Trailing comma is disallowed inside import(...) arguments"}
			}
			location: {
				language: "js"
				path: UIDPath<experimental/module-attributes/dynamic-import-with-valid-syntax/input.js>
				end: Position 1:18
				start: Position 1:17
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<experimental/module-attributes/dynamic-import-with-valid-syntax/input.js>
	loc: SourceLocation experimental/module-attributes/dynamic-import-with-valid-syntax/input.js 1:0-2:0
}
```

### `diagnostics`

```

 experimental/module-attributes/dynamic-import-with-valid-syntax/input.js:1:17 parse(js) ━━━━━━━━━━━

  ✖ Trailing comma is disallowed inside import(...) arguments

    import("foo.json", { with: { type: "json" } })
                     ^


```
