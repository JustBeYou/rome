# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/transforms/compile/index.test.ts --update-snapshots` to update.

## `css-handler > prefix > pseudo-selectors > multiple-classes`

### `Diagnostics`

```css

```

### `Input`

```css
/* Multiple pseudo classes */
.parent > .child:any-link, .example:read-only {
	width: 10px;
}
```

### `Output`

```css
/* Multiple pseudo classes */
.parent > .child:any-link,
.example:read-only {
	width: 10px;
}
.parent > .child:-moz-any-link,
.example:-moz-read-only {
	width: 10px;
}
.parent > .child:-webkit-any-link,
.example:read-only {
	width: 10px;
}

```
