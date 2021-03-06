# `harness.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/lint/rules/harness.test.ts --update-snapshots` to update.

## `ts/useTsExpectError`

### `0`

```

 lint/ts/useTsExpectError/reject/1/filename.ts:1 lint/ts/useTsExpectError  FIXABLE  ━━━━━━━━━━━━━━━━

  ✖ Prefer @ts-expect-error to get notified when suppression is no longer necessary.

  > 1 │ // @ts-ignore
      │ ^^^^^^^^^^^^^
    2 │ let foo: boolean = 1;

  ℹ Safe fix

    1   │ - //·@ts-ignore
      1 │ + //·@ts-expect-error
    2 2 │   let·foo:·boolean·=·1;
    3 3 │


```

### `0: formatted`

```ts
// @ts-expect-error
let foo: boolean = 1;

```

### `1`

```

 lint/ts/useTsExpectError/reject/2/filename.ts:1 lint/ts/useTsExpectError  FIXABLE  ━━━━━━━━━━━━━━━━

  ✖ Prefer @ts-expect-error to get notified when suppression is no longer necessary.

  > 1 │ // @ts-ignore: Blah blah blah
      │ ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
    2 │ let foo: boolean = 1;

  ℹ Safe fix

    1   │ - //·@ts-ignore:·Blah·blah·blah
      1 │ + //·@ts-expect-error:·Blah·blah·blah
    2 2 │   let·foo:·boolean·=·1;
    3 3 │


```

### `1: formatted`

```ts
// @ts-expect-error: Blah blah blah
let foo: boolean = 1;

```

### `2`

```

 lint/ts/useTsExpectError/reject/3/filename.ts:1 lint/ts/useTsExpectError  FIXABLE  ━━━━━━━━━━━━━━━━

  ✖ Prefer @ts-expect-error to get notified when suppression is no longer necessary.

  > 1 │ /* @ts-ignore */
      │ ^^^^^^^^^^^^^^^^
    2 │ let foo: boolean = 1;

  ℹ Safe fix

    1   │ - /*·@ts-ignore·*/
      1 │ + /*·@ts-expect-error·*/
    2 2 │   let·foo:·boolean·=·1;
    3 3 │


```

### `2: formatted`

```ts
/* @ts-expect-error */
let foo: boolean = 1;

```

### `3`

```

 lint/ts/useTsExpectError/reject/4/filename.ts:1 lint/ts/useTsExpectError  FIXABLE  ━━━━━━━━━━━━━━━━

  ✖ Prefer @ts-expect-error to get notified when suppression is no longer necessary.

  > 1 │ /** @ts-ignore */
      │ ^^^^^^^^^^^^^^^^^
    2 │ let foo: boolean = 1;

  ℹ Safe fix

    1   │ - /**·@ts-ignore*/
      1 │ + /**·@ts-expect-error*/
    2 2 │   let·foo:·boolean·=·1;
    3 3 │


```

### `3: formatted`

```ts
/** @ts-expect-error*/
let foo: boolean = 1;

```

### `4`

```

 lint/ts/useTsExpectError/reject/5/filename.ts:1 lint/ts/useTsExpectError  FIXABLE  ━━━━━━━━━━━━━━━━

  ✖ Prefer @ts-expect-error to get notified when suppression is no longer necessary.

  > 1 │ /**
      │ ^^^
  > 2 │  * @ts-ignore */
      │ ^^^^^^^^^^^^^^^^
    3 │ let foo: boolean = 1;

  ℹ Safe fix

    1 1 │   /**
    2   │ - ·*·@ts-ignore·*/
      2 │ + ·*·@ts-expect-error·*/
    3 3 │   let·foo:·boolean·=·1;
    4 4 │


```

### `4: formatted`

```ts
/**
 * @ts-expect-error */
let foo: boolean = 1;

```

### `5`

```

 lint/ts/useTsExpectError/reject/6/filename.ts:1 lint/ts/useTsExpectError  FIXABLE  ━━━━━━━━━━━━━━━━

  ✖ Prefer @ts-expect-error to get notified when suppression is no longer necessary.

  > 1 │ /**
      │ ^^^
  > 2 │  ** @ts-ignore */
      │ ^^^^^^^^^^^^^^^^^
    3 │ let foo: boolean = 1;

  ℹ Safe fix

    1 1 │   /**
    2   │ - ·**·@ts-ignore·*/
      2 │ + ·**·@ts-expect-error·*/
    3 3 │   let·foo:·boolean·=·1;
    4 4 │


```

### `5: formatted`

```ts
/**
 ** @ts-expect-error */
let foo: boolean = 1;

```

### `6`

```

```

### `6: formatted`

```ts
// @ts-expect-error
let foo: boolean = 1;

```

### `7`

```

```

### `7: formatted`

```ts
// @ts-expect-error: Blah blah blah
let foo: boolean = 1;

```

### `8`

```

```

### `8: formatted`

```ts
/* @ts-expect-error */
let foo: boolean = 1;

```

### `9`

```

```

### `9: formatted`

```ts
/** @ts-expect-error*/
let foo: boolean = 1;

```

### `10`

```

```

### `10: formatted`

```ts
/**
 * @ts-expect-error */
let foo: boolean = 1;

```

### `11`

```

```

### `11: formatted`

```ts
/**
 ** @ts-expect-error */
let foo: boolean = 1;

```
