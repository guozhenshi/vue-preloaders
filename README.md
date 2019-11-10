# Vue Preloaders 💡🍻📣
Stable, Flexible and Fully Customizable Vue and Nuxt preloaders library.

## Demo
https://vue-preloaders.netlify.com/

## Installation
```javascript
npm install vue-preloaders --save
```

## Mount
vue-preloaders instance is binded to **this** and **app**.
### Vue
main.js
```javascript
import VuePreloaders from 'vue-preloaders'
Vue.use(VuePreloaders, /*{ default global options }*/)
```
### Nuxt
nuxt.config.js
```javascript
{
    modules: [
        ['vue-preloaders/dist/nuxt-module', /*{ default global options }*/]
    ]
}
```

## Methods
### Open
Returns callback for closing the opened preloader.
```javascript
this.$preloaders.open()
```
```javascript
const close = this.$preloaders.open()
setTimeout(close, 1500)
```

### Close
```javascript
this.$preloaders.close()
```

## Options
