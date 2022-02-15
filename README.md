# vue3-directive-long-press

Detected long press

Based on https://github.com/Kutuzovska/vue3-directive-long-press

# Features

- Сallback is triggered when the keys are held down for a long time

# Usage
### App.vue
```html
<template>
  <input v-long-press="longPress" />
</template>

<script>
import longPress from './longPress';

export default {
  directives: { longPress },
  methods: {
    longPress() {
      console.log('detect');
    }
  }
}
</script>
```

# License

<a href="https://raw.githubusercontent.com/Kutuzovska/vue3-directive-long-press/main/LICENSE">MIT</a> License
