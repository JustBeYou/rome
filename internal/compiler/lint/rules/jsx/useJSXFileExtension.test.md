# `harness.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/lint/rules/harness.test.ts --update-snapshots` to update.

## `jsx/useJSXFileExtension`

### `0`

```

 lint/jsx/useJSXFileExtension/reject/1/test.js:2 lint/jsx/useJSXFileExtension ━━━━━━━━━━━━━━━━━━━━━━

  ✖ Files with the .js extension cannot contain JSX elements.

    1 │ // @jsx
  > 2 │ <div></div>
      │ ^^^^^^^^^^^

  ℹ Change the test.js file extension to .jsx or .tsx.


```

### `0: formatted`

```js
// @jsx
<div>
</div>;

```

### `1`

```

 lint/jsx/useJSXFileExtension/reject/2/test.js:2 lint/jsx/useJSXFileExtension ━━━━━━━━━━━━━━━━━━━━━━

  ✖ Files with the .js extension cannot contain JSX elements.

    1 │ // @jsx
  > 2 │ <></>
      │ ^^^^^

  ℹ Change the test.js file extension to .jsx or .tsx.


```

### `1: formatted`

```js
// @jsx
<></>;

```

### `2`

```

 lint/jsx/useJSXFileExtension/reject/3/test.js:2 lint/jsx/useJSXFileExtension ━━━━━━━━━━━━━━━━━━━━━━

  ✖ Files with the .js extension cannot contain JSX elements.

    1 │ // @jsx
  > 2 │ <Fragment></Fragment>
      │ ^^^^^^^^^^^^^^^^^^^^^

  ℹ Change the test.js file extension to .jsx or .tsx.


```

### `2: formatted`

```js
// @jsx
<Fragment>
</Fragment>;

```

### `3`

```

 lint/jsx/useJSXFileExtension/reject/4/test.js:2 lint/jsx/useJSXFileExtension ━━━━━━━━━━━━━━━━━━━━━━

  ✖ Files with the .js extension cannot contain JSX elements.

    1 │ // @jsx
  > 2 │ <React.Fragment></React.Fragment>
      │ ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Change the test.js file extension to .jsx or .tsx.


```

### `3: formatted`

```js
// @jsx
<React.Fragment>
</React.Fragment>;

```

### `4`

```

```

### `4: formatted`

```js
"<div></div>";


```

### `5`

```

```

### `5: formatted`

```jsx
// @jsx
<div>
</div>;

```

### `6`

```

```

### `6: formatted`

```jsx
// @jsx
<></>;

```

### `7`

```

```

### `7: formatted`

```jsx
// @jsx
<Fragment>
</Fragment>;

```

### `8`

```

```

### `8: formatted`

```jsx
// @jsx
<React.Fragment>
</React.Fragment>;

```

### `9`

```

```

### `9: formatted`

```tsx
// @jsx
<div>
</div>;

```

### `10`

```

```

### `10: formatted`

```tsx
// @jsx
<></>;

```

### `11`

```

```

### `11: formatted`

```tsx
// @jsx
<Fragment>
</Fragment>;

```

### `12`

```

```

### `12: formatted`

```tsx
// @jsx
<React.Fragment>
</React.Fragment>;

```
