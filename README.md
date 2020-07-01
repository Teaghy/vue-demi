<p align="center">
<img src="./assets/logo.png" width="200"/>
</p>

<h1 align="center">Vue Demi</h1>

<h4 align="center">

[![npm](https://img.shields.io/npm/v/vue-demi)](https://www.npmjs.com/package/vue-demi)

</h4>

<p align="center">
<b>Vue Demi</b> (<i>half</i> in French) is a developing utility that allows you to write <b>Universal Vue Plugins</b> for Vue 2 and 3. See more details in <a href='https://antfu.me/posts/make-libraries-working-with-vue-2-and-3'>this blog post</a>.
</p>

> 🚧 Expiremental

## Usage

Install this as your plugin's dependency:

```bash
npm i vue-demi
# or
yarn add vue-demi
```

```json
{
  "dependencies": {
    "vue-demi": "latest"
  }
}
```

Import everything related to Vue from it, it will redirect to `vue@2` `@vue/composition-api` or `vue@next` based on users' environments.

```ts
import { ref, reactive, defineComponent } from 'vue-demi'
```

Then publish your plugin and all is done!

## Examples

See [examples](./examples)

## License

MIT License © 2020 [Anthony Fu](https://github.com/antfu)