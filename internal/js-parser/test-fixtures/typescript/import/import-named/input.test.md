# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > import > import-named`

### `ast`

```javascript
JSRoot {
	body: [
		JSImportDeclaration {
			namedSpecifiers: [
				JSImportSpecifier {
					imported: JSIdentifier {
						name: "foo"
						loc: SourceLocation typescript/import/import-named/input.ts 1:9-1:12 (foo)
					}
					local: JSImportSpecifierLocal {
						name: JSBindingIdentifier {
							name: "foo"
							loc: SourceLocation typescript/import/import-named/input.ts 1:9-1:12 (foo)
						}
						loc: SourceLocation typescript/import/import-named/input.ts 1:9-1:12
					}
					loc: SourceLocation typescript/import/import-named/input.ts 1:9-1:12
				}
			]
			source: JSStringLiteral {
				value: "bar"
				loc: SourceLocation typescript/import/import-named/input.ts 1:20-1:25
			}
			loc: SourceLocation typescript/import/import-named/input.ts 1:0-1:26
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "module"
	syntax: ["ts"]
	path: UIDPath<typescript/import/import-named/input.ts>
	loc: SourceLocation typescript/import/import-named/input.ts 1:0-2:0
}
```

### `diagnostics`

```

```
