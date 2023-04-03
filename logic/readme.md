# logic

1. CSS 逻辑属性有 inline / block, start / end 。 inline 默认是从左往右水平排列，block 默认是从上往下垂直排列

   - margin-left -> margin-inline-start
   - margin-top -> margin-block-start
   - margin-right -> margin-inline-end
   - margin-bottom -> margin-block-end

2. CSS 逻辑属性需要配合 writing-mode 属性、direction 属性或者 text-orientation 属性才有意义。

3. width / height 对应的 CSS 逻辑属性

   - width -> inline-size
   - height -> block-size;
   - min-width -> min-inline-size
   - min-height -> min-block-size
   - max-width -> max-inline-size
   - max-height -> max-block-size

4. margin / padding / border

   - margin-inline-start, margin-inline-end, margin-block-start, margin-block-end -> margin-inline / margin-block
   - padding-inline-start, padding-inline-end, padding-block-start, padding-block-end -> padding-inline / padding-block
   - border-inline-start, border-inline-end, border-block-start, border-block-end -> border-inline / border-block
   - border-inline-start-color, border-inline-end-color, border-block-start-color, border-block-end-color -> border-inline-color / border-block-color
   - border-inline-start-style, border-inline-end-style, border-block-start-style, border-block-end-style -> border-inline-style / border-block-style
   - border-inline-start-width, border-inline-end-width, border-block-start-width, border-block-end-width -> border-inline-width / border-block-width

5. text-align: start; / text-align: end;

6. 绝对定位中用到的 inset

   - left -> inset-inline-start
   - right -> inset-inline-end
   - top -> inset-block-start
   - bottom -> inset-block-end
   - inset: 100px 200px 300px 400px;
   - inset: 100px 200px 300px;
   - inset: 100px 200px;
   - inset: 100px;
