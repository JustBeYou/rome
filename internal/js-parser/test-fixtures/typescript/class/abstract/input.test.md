# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > class > abstract`

### `ast`

```javascript
JSRoot {
	body: [
		JSClassDeclaration {
			abstract: true
			id: JSBindingIdentifier {
				name: "C1"
				loc: SourceLocation typescript/class/abstract/input.ts 1:15-1:17 (C1)
			}
			meta: JSClassHead {
				body: []
				loc: SourceLocation typescript/class/abstract/input.ts 1:0-1:20
			}
			loc: SourceLocation typescript/class/abstract/input.ts 1:0-1:20
		}
		JSClassDeclaration {
			abstract: true
			declare: true
			id: JSBindingIdentifier {
				name: "C2"
				loc: SourceLocation typescript/class/abstract/input.ts 2:23-2:25 (C2)
			}
			meta: JSClassHead {
				body: []
				loc: SourceLocation typescript/class/abstract/input.ts 2:0-2:28
			}
			loc: SourceLocation typescript/class/abstract/input.ts 2:0-2:28
		}
		JSExportLocalDeclaration {
			exportKind: "value"
			trailingComments: ["0"]
			declaration: JSClassDeclaration {
				abstract: true
				trailingComments: ["0"]
				id: JSBindingIdentifier {
					name: "C3"
					loc: SourceLocation typescript/class/abstract/input.ts 3:22-3:24 (C3)
				}
				meta: JSClassHead {
					body: []
					loc: SourceLocation typescript/class/abstract/input.ts 3:7-3:27
				}
				loc: SourceLocation typescript/class/abstract/input.ts 3:7-3:27
			}
			loc: SourceLocation typescript/class/abstract/input.ts 3:0-3:27
		}
		JSExportDefaultDeclaration {
			leadingComments: ["0"]
			declaration: JSClassDeclaration {
				abstract: true
				leadingComments: ["0"]
				id: JSBindingIdentifier {
					name: "*default*"
					loc: SourceLocation typescript/class/abstract/input.ts 5:15-5:33
				}
				meta: JSClassHead {
					body: []
					loc: SourceLocation typescript/class/abstract/input.ts 5:15-5:33
				}
				loc: SourceLocation typescript/class/abstract/input.ts 5:15-5:33
			}
			loc: SourceLocation typescript/class/abstract/input.ts 5:0-5:33
		}
		JSExportDefaultDeclaration {
			trailingComments: ["1"]
			declaration: JSClassDeclaration {
				abstract: true
				trailingComments: ["1"]
				id: JSBindingIdentifier {
					name: "C4"
					loc: SourceLocation typescript/class/abstract/input.ts 6:30-6:32 (C4)
				}
				meta: JSClassHead {
					body: []
					loc: SourceLocation typescript/class/abstract/input.ts 6:15-6:36
				}
				loc: SourceLocation typescript/class/abstract/input.ts 6:15-6:36
			}
			loc: SourceLocation typescript/class/abstract/input.ts 6:0-6:36
		}
	]
	comments: [
		CommentLine {
			id: "0"
			value: " `export abstract class {}` is not valid TypeScript."
			loc: SourceLocation typescript/class/abstract/input.ts 4:0-4:54
		}
		CommentLine {
			id: "1"
			value: " `abstract class` is not valid as an expression."
			loc: SourceLocation typescript/class/abstract/input.ts 7:0-7:50
		}
	]
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "module"
	syntax: ["ts"]
	path: UIDPath<typescript/class/abstract/input.ts>
	loc: SourceLocation typescript/class/abstract/input.ts 1:0-8:0
}
```

### `diagnostics`

```

```
