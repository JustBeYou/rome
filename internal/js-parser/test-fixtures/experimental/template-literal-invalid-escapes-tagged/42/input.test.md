# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > template-literal-invalid-escapes-tagged > 42`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSTaggedTemplateExpression {
				quasi: JSTemplateLiteral {
					expressions: [
						JSNumericLiteral {
							value: 0
							loc: SourceLocation experimental/template-literal-invalid-escapes-tagged/42/input.js 1:17-1:18
						}
					]
					quasis: [
						JSTemplateElement {
							cooked: "\\u{g}"
							raw: "\\u{g}"
							tail: false
							loc: SourceLocation experimental/template-literal-invalid-escapes-tagged/42/input.js 1:10-1:15
						}
						JSTemplateElement {
							cooked: "right"
							raw: "right"
							tail: true
							loc: SourceLocation experimental/template-literal-invalid-escapes-tagged/42/input.js 1:19-1:24
						}
					]
					loc: SourceLocation experimental/template-literal-invalid-escapes-tagged/42/input.js 1:9-1:25
				}
				tag: JSReferenceIdentifier {
					name: "sampleTag"
					loc: SourceLocation experimental/template-literal-invalid-escapes-tagged/42/input.js 1:0-1:9 (sampleTag)
				}
				loc: SourceLocation experimental/template-literal-invalid-escapes-tagged/42/input.js 1:0-1:25
			}
			loc: SourceLocation experimental/template-literal-invalid-escapes-tagged/42/input.js 1:0-1:25
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<experimental/template-literal-invalid-escapes-tagged/42/input.js>
	loc: SourceLocation experimental/template-literal-invalid-escapes-tagged/42/input.js 1:0-1:25
}
```

### `diagnostics`

```

```
