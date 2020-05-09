# description

This project is created by Vue Cli3. Only next codes were added in `HelloWorld.vue` to help to locate source maps in the Devloper Tool of a browser

```js
mounted() {
    console.log("HelloWorld mounted.")
  }
```

Souce maps cannot be detected in Edge browser while it works in Chrome browser.

### Edge

![image-20200509155325212](README.assets/image-20200509155325212.png)

![image-20200509155525602](README.assets/image-20200509155525602.png)

### Chrome

![image-20200509155648750](README.assets/image-20200509155648750.png)

![image-20200509155810811](README.assets/image-20200509155810811.png)

# vue-cli-in-edge-browser

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
