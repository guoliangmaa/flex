## flex学习

### 1.常见父属性
- flex-direction: 设置主轴的方向
  - row：按照x轴
  - row-reverse：按照x轴，逆转
  - column：按照Y轴
- justify-content: 设置主轴上子元素的排列方式
  - flex-start: 从头部开始，默认
  - flex-end：从尾部开始
  - center：主轴居中对齐
  - space-around：平分剩余空间
  - space-between：**先两边贴合，再评分剩余空间**
- flex-wrap: 设置子元素是否换行
  - nowrap：不换行，默认
  - warp：换行
- align-content: 设置**侧轴**上的子元素的排列方式（多行）
  - flex-start: 从头部开始，默认
  - flex-end：从尾部开始
  - center：主轴居中对齐
  - space-around：平分剩余空间
  - space-between：**先两边贴合，再评分剩余空间**
- align-items: 设置**侧轴**上子元素的排列方式（单行）
  - flex-start：从头到尾
  - flex-end：从尾到头
  - center：居中
  - stretch：沿侧轴拉伸，注意不能设置**子元素宽度**
- flex-flow: 复合属性，相当于同时设置了flex-direction 和 flex-wrap
  - flex-flow: row wrap;
> 默认来说，主轴是水平向右，侧轴是竖直向下
> 元素是按照主轴来排列的