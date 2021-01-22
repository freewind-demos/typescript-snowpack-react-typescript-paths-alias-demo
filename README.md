TypeScript Snowpack React Typescript Paths Alias Demo
=====================================================

如果在tsconfig.json中定义了`paths`，比如：

```
"paths": {
  "#src/*": [
    "./src/*"
  ]
}
```

则可以在`snowpack.config.js`中定义`alias`:

```
alias: {
  '#src': './src/'
}
```

与之相应。

```
npm install
npm run demo
```

It will open page on browser automatically.
