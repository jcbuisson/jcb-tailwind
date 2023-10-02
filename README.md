
Voir https://software-engineering-corner.hashnode.dev/using-tailwindcss-with-web-components-and-shadowdom-in-litelement

# Run in dev
```
npm run dev
```

# Build
```
npm run build   # --> dist/jcb-tailwind.js
```

# Test in a VueJS 3 project
```
npx create-vite@latest test-jcb-tailwind --template vue
cd test-jcb-tailwind
npm i jcb-tailwind
```

Modifier App.js :
```
<template>
   <jcb-tailwind>Hello</jcb-tailwind>
</template>

<script setup>
import 'jcb-tailwind'
</script>
```

```
npm run dev
```
