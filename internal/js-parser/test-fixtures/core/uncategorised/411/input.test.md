# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 411`

### `ast`

```javascript
JSRoot {
	body: [
		JSContinueStatement {
			loc: SourceLocation core/uncategorised/411/input.js 1:0-1:8
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
				message: RAW_MARKUP {value: "No loop label found"}
			}
			location: {
				language: "js"
				path: UIDPath<core/uncategorised/411/input.js>
				end: Position 1:0
				start: Position 1:0
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<core/uncategorised/411/input.js>
	loc: SourceLocation core/uncategorised/411/input.js 1:0-2:0
}
```

### `diagnostics`

```

 core/uncategorised/411/input.js:1 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ No loop label found

    continue
    ^


```
