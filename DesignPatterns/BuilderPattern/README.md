## 建造者模式  
老师为Director角色，学生为Builder角色，Teacher隔离了客户端与具体步骤的依赖在一些项目中，经常需要构建一些比较复杂的对象，并对其多个属性进行赋值的复杂操作，程序员的一些忽略可能导致某个属性未被赋值而引起对象的失效，在这种情况下使用构造者模式，创建一个Director来按部就班地指挥一个对象的创建，可以有效的避免意外的发生。使用创建者模式，用户只需要指定创建的类型就可以得到相应的对象，而具体的建造过程和细节就被Director和Builder隐藏了，这正是依赖倒转的体现：抽象不应该依赖于细节，细节应该依赖于抽象。
