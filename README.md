
Voir https://software-engineering-corner.hashnode.dev/using-tailwindcss-with-web-components-and-shadowdom-in-litelement

# Run in dev
```
npm run dev
```

# Build
```
npm run build   # --> dist/jcb-camera.js
```

# Test in a VueJS 3 project
```
npx create-vite@latest test --template vue
cd test
npm i jcb-camera
```

Modifier App.js :
```
<template>
   <jcb-camera>
      <h1>Hello</h1>
   </jcb-camera>
</template>

<script setup>
import 'jcb-camera'
</script>
```

```
npm run dev
```
