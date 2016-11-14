### 在异步序列中使用嵌套或命名的回调函数

------

### 谨记
+ **使用嵌套或命名的回调函数按顺序地执行多个异步操作。**
+ **尝试在过多的嵌套的回调函数和尴尬的命名的非嵌套回调函数之间取得平衡。**
+ **避免将可被并行执行的操作顺序化。**