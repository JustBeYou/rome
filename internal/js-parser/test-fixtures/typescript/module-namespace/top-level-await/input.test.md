# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > module-namespace > top-level-await`

### `ast`

```javascript
JSRoot {
	body: [
		TSModuleDeclaration {
			id: JSBindingIdentifier {
				name: "N"
				loc: SourceLocation typescript/module-namespace/top-level-await/input.ts 1:10-1:11 (N)
			}
			body: TSModuleBlock {
				body: [
					JSVariableDeclarationStatement {
						declaration: JSVariableDeclaration {
							kind: "const"
							declarations: [
								JSVariableDeclarator {
									id: JSBindingIdentifier {
										name: "x"
										loc: SourceLocation typescript/module-namespace/top-level-await/input.ts 2:10-2:11 (x)
									}
									init: JSAwaitExpression {
										argument: JSNumericLiteral {
											value: 42
											loc: SourceLocation typescript/module-namespace/top-level-await/input.ts 2:20-2:22
										}
										loc: SourceLocation typescript/module-namespace/top-level-await/input.ts 2:14-2:22
									}
									loc: SourceLocation typescript/module-namespace/top-level-await/input.ts 2:10-2:22
								}
							]
							loc: SourceLocation typescript/module-namespace/top-level-await/input.ts 2:4-2:23
						}
						loc: SourceLocation typescript/module-namespace/top-level-await/input.ts 2:4-2:23
					}
				]
				loc: SourceLocation typescript/module-namespace/top-level-await/input.ts 1:12-3:1
			}
			loc: SourceLocation typescript/module-namespace/top-level-await/input.ts 1:0-3:1
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "module"
	syntax: ["ts"]
	path: UIDPath<typescript/module-namespace/top-level-await/input.ts>
	loc: SourceLocation typescript/module-namespace/top-level-await/input.ts 1:0-4:0
}
```

### `diagnostics`

```

```
