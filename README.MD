

```js
npm i
npm start
```

- js 的加载执行会阻塞 dom 树的解析
- css 的加载解析会阻塞 render 树的解析
- css 的加载解析会阻塞 js 的执行，所以 css 也能阻塞 dom 树的解析

### 所以通常把样式表放在上面，把 js 放在下面
