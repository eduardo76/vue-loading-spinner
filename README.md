# vue-loading-spinner

> Just another collection of loading spinners with Vue.js

## Installation

``` bash
npm install --save vue-loading-spinner
```
or

``` bash
yarn add vue-loading-spinner
```

## Usage

``` vue
<template>
  <div id="app">
    <cube-spin></cube-spin>
  </div>
</template>

<script>
  import CubeSpin from 'vue-loading-spinner/components/Cube'
  export default {
    components: {
      CubeSpin
    }
  }
</script>

```

## Demo

List of all spinner: [Demo](https://nguyenvanduocit.github.io/vue-loading-spinner/)

## Development Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).