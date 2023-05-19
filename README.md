# qs

This is a mirror of [qs](https://www.npmjs.com/package/qs), bundled and exposed as ES module.

## Install

```
npm install @bundled-es-modules/qs
```

## Use

```html
<script type="module">
  import qs from '@bundled-es-modules/qs';
  const obj = qs.parse('a=c');
  console.log(obj);

  const str = qs.stringify(obj)
  console.log(str);
</script>
```