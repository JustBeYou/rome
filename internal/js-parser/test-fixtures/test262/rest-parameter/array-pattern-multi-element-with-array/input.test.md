# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `test262 > rest-parameter > array-pattern-multi-element-with-array`

### `ast`

```javascript
JSRoot {
	body: [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "multiElementWithArray"
				loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:9-1:30 (multiElementWithArray)
			}
			body: JSBlockStatement {
				body: []
				directives: []
				loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:49-1:51
			}
			head: JSFunctionHead {
				async: false
				generator: false
				hasHoistedVars: false
				params: []
				rest: JSBindingArrayPattern {
					elements: [
						JSBindingArrayPattern {
							elements: [
								JSBindingIdentifier {
									name: "a"
									meta: JSPatternMeta {
										loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:36-1:37
									}
									loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:36-1:37 (a)
								}
							]
							meta: JSPatternMeta {
								loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:35-1:38
							}
							loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:35-1:38
						}
						JSBindingIdentifier {
							name: "b"
							meta: JSPatternMeta {
								loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:40-1:41
							}
							loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:40-1:41 (b)
						}
						JSBindingArrayPattern {
							elements: [
								JSBindingIdentifier {
									name: "c"
									meta: JSPatternMeta {
										loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:44-1:45
									}
									loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:44-1:45 (c)
								}
							]
							meta: JSPatternMeta {
								loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:43-1:46
							}
							loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:43-1:46
						}
					]
					meta: JSPatternMeta {
						loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:34-1:47
					}
					loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:34-1:47
				}
				loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:30-1:48
			}
			loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:0-1:51
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<test262/rest-parameter/array-pattern-multi-element-with-array/input.js>
	loc: SourceLocation test262/rest-parameter/array-pattern-multi-element-with-array/input.js 1:0-2:0
}
```

### `diagnostics`

```

```
