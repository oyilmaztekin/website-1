# 🍰 Recipes

## React

First we need to install the dependencies for React.

[Blog Post](http://blog.jakoblind.no/react-parcel/)

```bash
npm install --save react
npm install --save react-dom
npm install --save-dev parcel-bundler
```

<sub>Or if you have the optional Yarn package manager installed</sub>

```bash
yarn add react
yarn add react-dom
yarn add --dev parcel-bundler
```

Add Start script to `package.json`

```javascript
// package.json
"scripts": {
  "start": "parcel index.html"
}
```

## Preact

First we need to install the dependencies for Preact.

```bash
npm install --save preact
npm install --save-dev parcel-bundler
```

<sub>Or if you have the optional Yarn package manager installed</sub>

```bash
yarn add preact
yarn add --dev parcel-bundler
```

Add Start script to `package.json`

```javascript
// package.json
"scripts": {
  "start": "parcel index.html"
}
```

## Vue

First we need to install the dependencies for Vue.

```bash
npm install --save vue
npm install --save-dev parcel-bundler
```

<sub>Or if you have the optional Yarn package manager installed</sub>

```bash
yarn add vue
yarn add --dev parcel-bundler
```

Add Start script to `package.json`

```javascript
// package.json
"scripts": {
  "start": "parcel index.html"
}
```

## TypeScript

First we need to add Parcel and TypeScript to our project.

```bash
npm install --save-dev typescript
npm install --save-dev parcel-bundler
```

<sub>Or if you have the optional Yarn package manager installed</sub>

```bash
yarn add --dev typescript
yarn add --dev parcel-bundler
```

### Compiling from index.html

Add Start script to `package.json`

```javascript
// package.json
"scripts": {
  "start": "parcel index.html"
}
```

Then, in your `index.html` file, simply reference your `.ts` file.

```html
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
</head>
<body>
    <!-- Here 👇 -->
    <script src="./myTypescriptFile.ts"></script>
</body>
</html>
```

Done!

### Compiling the `.ts` file directly

Add Start script to `package.json`

```javascript
// package.json
"scripts": {
  "start": "parcel myTypescriptFile.ts"
}
```

Done! 😄 Compiled `.js` file can be found inside the dist folder.
