# Boilerplate for VueJS Plugins
Copy this project to quickly create the scaffolding for building VueJS plugins using TailwindCss and NPM

## How to use
Clone this repository
```
git clone https://github.com/akash-mitra/vue-npm-tailwind-boilerplate.git
```

The demo app is named `HelloWorld`. You must change this name to your app's name.

1. In the package.json, change the string `hello-world` to your app's name
2. In the `src` directory, change the file `hello-world.vue`. In the same directory, open `wrapper.js` and change the file name from `hello-world.vue` to whatever filename you have provided. Also change the application name from `HelloWorld` to your app name in PascalCase format.
3. Open the `build/rollup.config.js` file and change the `output.name` to your app's name in PascalCase format.

Finally, execute the `npm install` followed by `npm run build`

You are all set. Build something awesome!
