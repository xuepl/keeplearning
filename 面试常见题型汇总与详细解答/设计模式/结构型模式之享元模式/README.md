#### 享元模式
- 用途
1. 享元模式是一个用于优化的设计模式
- 使用需要满足的条件
1. 应用需要使用大量的对象。
2. 对象太多，存储/渲染它们的代价太大。一旦移除对象中的可变状态（因为在需要之时，应
该由客户端代码显式地传递给享元），多组不同的对象可被相对更少的共享对象所替代。
3. 对象ID对于应用不重要。对象共享会造成ID比较的失败，所以不能依赖对象ID（那些在
客户端代码看来不同的对象，最终具有相同的ID）。


- 享元模式 可以创建不同类型的实例，相同类型的实例享元
