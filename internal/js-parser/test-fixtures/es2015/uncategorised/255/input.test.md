# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 255`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSUnaryExpression {
				operator: "void"
				prefix: true
				argument: JSObjectExpression {
					properties: []
					loc: SourceLocation es2015/uncategorised/255/input.js 1:5-1:12
				}
				loc: SourceLocation es2015/uncategorised/255/input.js 1:0-1:12
			}
			loc: SourceLocation es2015/uncategorised/255/input.js 1:0-1:12
		}
		JSExpressionStatement {
			expression: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: SourceLocation es2015/uncategorised/255/input.js 1:12-1:13
			}
			loc: SourceLocation es2015/uncategorised/255/input.js 1:12-1:13
		}
		JSExpressionStatement {
			expression: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: SourceLocation es2015/uncategorised/255/input.js 1:13-1:14
			}
			loc: SourceLocation es2015/uncategorised/255/input.js 1:13-1:14
		}
		JSExpressionStatement {
			expression: JSNumericLiteral {
				value: 3
				loc: SourceLocation es2015/uncategorised/255/input.js 1:15-1:16
			}
			loc: SourceLocation es2015/uncategorised/255/input.js 1:15-1:16
		}
		JSExpressionStatement {
			expression: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: SourceLocation es2015/uncategorised/255/input.js 1:17-1:18
			}
			loc: SourceLocation es2015/uncategorised/255/input.js 1:17-1:19
		}
	]
	comments: []
	corrupt: true
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {
				advice: [
					log {
						category: "info"
						text: [RAW_MARKUP {value: "We expected to find the closing character <emphasis>"}, "]", RAW_MARKUP {value: "</emphasis> here"}]
					}
					frame {
						location: SourceLocation es2015/uncategorised/255/input.js 1:9-1:9
					}
				]
				category: ["parse"]
				categoryValue: "js"
				message: [RAW_MARKUP {value: "Unclosed <emphasis>"}, "property name", RAW_MARKUP {value: "</emphasis>"}]
			}
			location: {
				language: "js"
				path: UIDPath<es2015/uncategorised/255/input.js>
				end: Position 1:7
				start: Position 1:7
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<es2015/uncategorised/255/input.js>
	loc: SourceLocation es2015/uncategorised/255/input.js 1:0-1:19
}
```

### `diagnostics`

```

 es2015/uncategorised/255/input.js:1:7 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unclosed property name

    void { [1, 2]: 3 };
           ^

  ℹ We expected to find the closing character ] here

    void { [1, 2]: 3 };
             ^


```
