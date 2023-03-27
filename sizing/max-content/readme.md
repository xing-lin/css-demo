# max-content

1. 兼容性 https://caniuse.com/?search=max-content

2. 表示最大宽度内容。实际开发中没有任何场景必须要使用 max-content 关键字。

3. 满足以下条件可以体现 max-content 关键字的价值
   - 各项宽度不确定，整体宽度自适应
   - 当前项的内容较少
   - 当前项的宽度需要尽可能的小

4. 需要使用 max-content 关键字的场景，都能使用 white-space: nowrap 声明实现一模一样的效果。
