# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0175`

### `ast`

```javascript
JSRoot {
	body: [
		JSDoWhileStatement {
			body: JSBlockStatement {
				body: [
					JSExpressionStatement {
						expression: JSReferenceIdentifier {
							name: "x"
							loc: SourceLocation esprima/invalid-syntax/migrated_0175/input.js 1:5-1:6 (x)
						}
						loc: SourceLocation esprima/invalid-syntax/migrated_0175/input.js 1:5-1:6
					}
				]
				directives: []
				loc: SourceLocation esprima/invalid-syntax/migrated_0175/input.js 1:3-1:8
			}
			test: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: SourceLocation esprima/invalid-syntax/migrated_0175/input.js 1:9-1:10
			}
			loc: SourceLocation esprima/invalid-syntax/migrated_0175/input.js 1:0-1:10
		}
	]
	comments: []
	corrupt: true
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {
				advice: [log {category: "info", text: [RAW_MARKUP {value: "Expected character <emphasis>"}, "while", RAW_MARKUP {value: "</emphasis>"}]}]
				category: ["parse"]
				categoryValue: "js"
				message: [RAW_MARKUP {value: "Unexpected character <emphasis>"}, "*", RAW_MARKUP {value: "</emphasis>"}]
			}
			location: {
				language: "js"
				path: UIDPath<esprima/invalid-syntax/migrated_0175/input.js>
				end: Position 1:10
				start: Position 1:9
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<esprima/invalid-syntax/migrated_0175/input.js>
	loc: SourceLocation esprima/invalid-syntax/migrated_0175/input.js 1:0-2:0
}
```

### `diagnostics`

```

 esprima/invalid-syntax/migrated_0175/input.js:1:9 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unexpected character *

    do { x } *
             ^

  ℹ Expected character while


```
