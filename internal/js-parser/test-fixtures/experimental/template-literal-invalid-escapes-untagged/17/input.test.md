# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > template-literal-invalid-escapes-untagged > 17`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSTemplateLiteral {
				expressions: []
				quasis: [
					JSTemplateElement {
						cooked: "\\u0"
						raw: "\\u0"
						tail: true
						loc: SourceLocation experimental/template-literal-invalid-escapes-untagged/17/input.js 1:1-1:4
					}
				]
				loc: SourceLocation experimental/template-literal-invalid-escapes-untagged/17/input.js 1:0-1:5
			}
			loc: SourceLocation experimental/template-literal-invalid-escapes-untagged/17/input.js 1:0-1:5
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
				message: RAW_MARKUP {value: "Invalid escape sequence in template"}
			}
			location: {
				language: "js"
				path: UIDPath<experimental/template-literal-invalid-escapes-untagged/17/input.js>
				end: Position 1:3
				start: Position 1:3
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<experimental/template-literal-invalid-escapes-untagged/17/input.js>
	loc: SourceLocation experimental/template-literal-invalid-escapes-untagged/17/input.js 1:0-1:5
}
```

### `diagnostics`

```

 experimental/template-literal-invalid-escapes-untagged/17/input.js:1:3 parse(js) ━━━━━━━━━━━━━━━━━━

  ✖ Invalid escape sequence in template

    `\u0`
       ^


```
