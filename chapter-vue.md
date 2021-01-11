# Vue 3
- SPC - Single Page Component
- Router
- Version: 2.6.11 - 3.0.5
# Overview
The following list covers the key points for Vue:
- a community framework supporting reactive components (MVVM model)
- similar to React and Angular but smaller in size
- clear documentation
# Configuration
- VueCLI
- Webpack
# General topics
## Hello World example
- in a single html
- ```<script src="https://unpkg.com/vue"></script>```
- ```<script src="https://cdn.jsdelivr.net/npm/vue@2.6.11/dist/vue.js"></script>```
- ```<script src="https://unpkg.com/vue@next"></script>```
- ```<script src="https://cdn.jsdelivr.net/npm/vue@3.0.5/dist/vue.global.js"></script>```
# Advanced topic 
## Single Page Component
Structure of a Hello World application

- main.js
- App.vue with 3 components:
    1. Template
    2. Script
    3. Style

```
Template:

<template>
    <div id="app">
        <img src-'./assets/logo.png'>
        <hello-world msg='Hello world'></hello-world>
    </div>
</template>
```

```
Script:

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
    name: 'App',
    components: { 
        HelloWord 
    }
}
</script>
```

```
Style:

<style>
</style>
```
## 
# Conclusion
Vue.js is a relatively easy to learn UI framework with tremendous support from the community.
# Appendix
# Reference
- https://vuejs.org
