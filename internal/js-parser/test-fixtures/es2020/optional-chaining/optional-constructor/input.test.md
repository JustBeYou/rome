# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2020 > optional-chaining > optional-constructor`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSNewExpression {
				arguments: []
				callee: JSReferenceIdentifier {
					name: "a"
					loc: SourceLocation es2020/optional-chaining/optional-constructor/input.js 1:4-1:5 (a)
				}
				loc: SourceLocation es2020/optional-chaining/optional-constructor/input.js 1:0-1:9
			}
			loc: SourceLocation es2020/optional-chaining/optional-constructor/input.js 1:0-1:10
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
				message: RAW_MARKUP {value: "constructors in/after an Optional Chain are not allowed"}
			}
			location: {
				language: "js"
				path: UIDPath<es2020/optional-chaining/optional-constructor/input.js>
				end: Position 1:7
				start: Position 1:7
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<es2020/optional-chaining/optional-constructor/input.js>
	loc: SourceLocation es2020/optional-chaining/optional-constructor/input.js 1:0-1:10
}
```

### `diagnostics`

```

 es2020/optional-chaining/optional-constructor/input.js:1:7 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ constructors in/after an Optional Chain are not allowed

    new a?.();
           ^


```
