# bfc 块格式化上下文
## 触发条件
- 根元素 html
- 浮动 float
- 绝对定位  
- 行内块元素  inline-block
- 弹性盒子 display flex
- hidden overflow

## bfc特点
- 内部是文档流
- 是一个隔离的容器，子元素不影响外面的元素
- 计算高度  浮动元素也在计算计算范围

## 个人理解
- 每个bfc的容器就是独立的板块，内部是正常的文档流布局，高度计算包括浮动元素。