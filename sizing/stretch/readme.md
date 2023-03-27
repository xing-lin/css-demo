# stretch

1. 兼容性 https://caniuse.com/?search=width%3Astretch

2. 实际开发的时候，我们需要用到 stretch 关键字的场景并不多。首先，block 水平的元素、弹性布局和网格布居中的子项默认都自带弹性拉伸特性；其次，对于替换元素、表格元素、內联块级元素等这些具有“包裹性”的元素，建议使用“宽度分离原则”。

```css
.container {
  margin: 15px;
  padding: 10px;
}
.container > img {
  width: 100%;
}
```

3. 只有在 HTML 标签使用受限时，才需要考虑使用 stretch 关键字。例如一个 button，外部不方便嵌套其他标签元素。

```css
button {
  height: 40px;
  width: -webkit-fill-available;
  width: -moz-available;
  width: stretch;
  margin: 0 15px;
}
```

4. IE 和 Edge 浏览器是不支持 stretch 关键字。可以用 calc() 函数代替。

5. 使用 stretch 可以无需关心 margin 在水平方向上的变化。易于维护。
