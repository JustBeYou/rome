# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-destructuring-assignment-array-pattern > dup-assignment`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSAssignmentExpression {
				operator: "="
				left: JSAssignmentArrayPattern {
					elements: [
						JSAssignmentIdentifier {
							name: "a"
							loc: SourceLocation esprima/es2015-destructuring-assignment-array-pattern/dup-assignment/input.js 1:1-1:2 (a)
						}
						JSAssignmentIdentifier {
							name: "a"
							loc: SourceLocation esprima/es2015-destructuring-assignment-array-pattern/dup-assignment/input.js 1:3-1:4 (a)
						}
						JSArrayHole {
							loc: SourceLocation esprima/es2015-destructuring-assignment-array-pattern/dup-assignment/input.js 1:5-1:5
						}
					]
					rest: JSAssignmentIdentifier {
						name: "a"
						loc: SourceLocation esprima/es2015-destructuring-assignment-array-pattern/dup-assignment/input.js 1:9-1:10 (a)
					}
					loc: SourceLocation esprima/es2015-destructuring-assignment-array-pattern/dup-assignment/input.js 1:0-1:11
				}
				right: JSNumericLiteral {
					value: 0
					loc: SourceLocation esprima/es2015-destructuring-assignment-array-pattern/dup-assignment/input.js 1:12-1:13
				}
				loc: SourceLocation esprima/es2015-destructuring-assignment-array-pattern/dup-assignment/input.js 1:0-1:13
			}
			loc: SourceLocation esprima/es2015-destructuring-assignment-array-pattern/dup-assignment/input.js 1:0-1:14
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<esprima/es2015-destructuring-assignment-array-pattern/dup-assignment/input.js>
	loc: SourceLocation esprima/es2015-destructuring-assignment-array-pattern/dup-assignment/input.js 1:0-2:0
}
```

### `diagnostics`

```

```
