# SimpleToDo App PWA-based

This project is a simple Todo [PWA] (Progressive Web App) inspired by [TodoMVC]. Based on [Vue.js] framework and [Vuetify] UI-kit technologies.
Also, available Android and iOS hybrid mobile apps builds generation with [Capacitor 3].

[capacitor 3]: https://capacitorjs.com/docs/v3
[pwa]: https://developers.google.com/web/progressive-web-apps
[todomvc]: http://todomvc.com
[vue.js]: https://vuejs.org
[vuetify]: https://vuetifyjs.com

<p align="center">
  <a href="https://mayoujin.github.io/" target="_blank" rel="noopener">
    <img src="https://vuetifytodo.davidgaroro.es/github/app.png">
    Live Demo
  </a>
</p>

## Features

- Vue CLI 3 + Webpack + vue-loader for single file Vue components
- Vue + vue-router + vuex working together
- Vuetify a-la-carte (reduce project's size in production)
- Progressive Web App - App manifest - Service worker - Workbox options - [Cache Google Fonts] - 100/100 Lighthouse score
- Android and iOS Hybrid mobile apps

[cache google fonts]: https://developers.google.com/web/tools/workbox/guides/common-recipes#google_fonts

## Built With

### Dependencies

| Name         | Description                               |
| ------------ | ----------------------------------------  |
| [vue]        | Progressive JavaScript Framework          |
| [vue-cli-3]  | Standard Tooling for Vue.js Development   |
| [vue-router] | Official Router for Vue.js                |
| [vuex]       | Centralized State Management for Vue.js   |
| [vuetify]    | ️Material Component Framework for Vue.js  |

### Development Dependencies

| Name                    | Description                                  |
| ----------------------- | -------------------------------------------- |
| [vue/cli-plugin-babel]  | Compiler for next generation JavaScript      |
| [vue/cli-plugin-eslint] | Pluggable JavaScript linter                  |
| [vue/cli-plugin-pwa]    | JavaScript Library for adding support to PWA |
| [@capacitor/*]          | A cross-platform native runtime for web apps |

[vue/cli-plugin-babel]: https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel
[vue/cli-plugin-eslint]: https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint
[vue/cli-plugin-pwa]: https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-pwa
[@capacitor/*]: https://github.com/ionic-team/capacitor

## Installation & Setup

### Install dependencies

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Capacitor init

```
npx cap init
```

### Capacitor add [Android](https://capacitorjs.com/docs/v3/android)

```
npx cap add android
```

### Open [Android Studio](https://capacitorjs.com/docs/v3/getting-started/environment-setup#android-development)

```
npx cap open android
```

### Capacitor [sync](https://capacitorjs.com/docs/v3/cli/sync)

```
npx cap sync
```

### Android [Troubleshooting](https://capacitorjs.com/docs/v3/android/troubleshooting)


