# Vue Web Component Sample

Very Simple WebComponent sample with vue-cli 3, TypeScript is supported.

## Requirement
* node 8.11.1+  
* @vue/cli 3.0.0+
  * `npm install -g @vue/cli` or `yarn global add @vue/cli`  
* (optional) scss support
  * install dependency globally, just one time.
  * `yarn global add node-sass sass-loader`
  

## How-to
* Development
  * `vue serve MyH1.vue`
* Build
  * `vue build --target wc --name my-h1 MyH1.vue`
  * you can try your component in demo.html, for example: `<my-h1 name="Allen"></my-h1>`