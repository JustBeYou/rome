# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 171`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSFunctionExpression {
				id: JSBindingIdentifier {
					name: "x"
					loc: SourceLocation es2015/uncategorised/171/input.js 1:10-1:11 (x)
				}
				body: JSBlockStatement {
					body: []
					directives: []
					loc: SourceLocation es2015/uncategorised/171/input.js 1:24-1:26
				}
				head: JSFunctionHead {
					async: false
					generator: false
					hasHoistedVars: false
					params: []
					rest: JSBindingArrayPattern {
						elements: [
							JSBindingIdentifier {
								name: "a"
								meta: JSPatternMeta {
									loc: SourceLocation es2015/uncategorised/171/input.js 1:17-1:18
								}
								loc: SourceLocation es2015/uncategorised/171/input.js 1:17-1:18 (a)
							}
							JSBindingIdentifier {
								name: "b"
								meta: JSPatternMeta {
									loc: SourceLocation es2015/uncategorised/171/input.js 1:20-1:21
								}
								loc: SourceLocation es2015/uncategorised/171/input.js 1:20-1:21 (b)
							}
						]
						meta: JSPatternMeta {
							loc: SourceLocation es2015/uncategorised/171/input.js 1:15-1:23
						}
						loc: SourceLocation es2015/uncategorised/171/input.js 1:15-1:23
					}
					loc: SourceLocation es2015/uncategorised/171/input.js 1:11-1:24
				}
				loc: SourceLocation es2015/uncategorised/171/input.js 1:1-1:26
			}
			loc: SourceLocation es2015/uncategorised/171/input.js 1:0-1:27
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<es2015/uncategorised/171/input.js>
	loc: SourceLocation es2015/uncategorised/171/input.js 1:0-1:27
}
```

### `diagnostics`

```

```
