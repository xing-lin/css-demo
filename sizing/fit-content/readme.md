# fit-cotent

1. 兼容性 https://caniuse.com/?search=fit-content

2. 该关键字让元素有了明确的尺寸。非常典型的例子就是绝对定位元素使用 margin: auto; 实现居中效果时需要设置具体的 width 和 height 的属性值。

3. 用该关键字实现一个特殊的效果：一段文字，字数少的时候居中显示，字数多的时候左对齐显示。

```css
.content {
  width: fit-content;
  margin: auto;
}
```
