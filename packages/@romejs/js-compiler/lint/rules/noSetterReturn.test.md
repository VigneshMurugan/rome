# `noSetterReturn.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-compiler/lint/rules/noSetterReturn.test.ts --update-snapshots` to update.

## `no setter return`

### `0`

```

 unknown:5:10 lint/noSetterReturn ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Setter cannot return a value

    3 │       set name(value) {
    4 │         if (!value) {
  > 5 │           return 'wrong';
      │           ^^^^^^^^^^^^^^^
    6 │         }
    7 │       }

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `0: formatted`

```
class p {
  set name(value) {
    if (!value) {
      return 'wrong';
    }
  }
}
console.log(new p());

```

### `1`

```

 unknown:5:10 lint/noSetterReturn ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Setter cannot return a value

    3 │       static set name(value) {
    4 │         if (!value) {
  > 5 │           return 'wrong';
      │           ^^^^^^^^^^^^^^^
    6 │         }
    7 │       }

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `1: formatted`

```
class p {
  static set name(value) {
    if (!value) {
      return 'wrong';
    }
  }
}
console.log(p);

```

### `2`

```

 unknown:5:10 lint/noSetterReturn ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Setter cannot return a value

    3 │       set name(value) {
    4 │         if (!value) {
  > 5 │           return 'wrong';
      │           ^^^^^^^^^^^^^^^
    6 │         }
    7 │       }

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `2: formatted`

```
let p = {
  set name(value) {
    if (!value) {
      return 'wrong';
    }
  },
};
console.log(p);

```

### `3`

```
✔ No known problems!

```

### `3: formatted`

```
class p {
  set name(value) {
    if (!value) {
      return;
    }
  }
}
console.log(p);

```