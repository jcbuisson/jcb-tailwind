
Voir https://software-engineering-corner.hashnode.dev/using-tailwindcss-with-web-components-and-shadowdom-in-litelement

# Run in dev
```
npm run dev
```

# Build and run
```
npm run build   # --> dist/lit-tailwind-integration.js
```

```
// dist/index.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Vite + Lit + Tailwind</title>
    <script type="module" src="./lit-tailwind-integration.js"></script>
  </head>
  <body>
    <my-element>
      <h1>Vite + Lit + Tailwind</h1>
    </my-element>
  </body>
</html>
```

```
cd dist
parcel index.html
```
