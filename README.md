## Intro

I am a vscode extension that provide some vue snippets.

## What could I do?

- vue3

| abbr.    | snippet               |
| -------- | --------------------- |
| `com`    | `computed(() => )`    |
| `watchE` | `watchEffect(()=>{})` |
| `onmo`   | `onMounted(()=>{})`   |
| `onun`   | `onUnmounted(()=>{})` |

> Use `<sc` to generate template

```vue
<script setup>
<script>

<template>
  <div>
  </div>
</template>
```

> Use `<st` to generate style

```vue
<style scoped></style>
```

- vue2

| abbr.                  | snippet                 |
| ---------------------- | ----------------------- |
| `vname`                | `name: '',`             |
| `vcreated`             | `created() {},`         |
| `vdata`                | `data() { return {} },` |
| ...`v` + other options | ...other options        |

> Use `vbase` to generate template

```vue
<template>
  <div></div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
```
