# fresh-design-pattern

## JAVA 设计模式

#### 简单工厂模式

定义超类，子类通过继承重写方法实现多态，创建一个Factory工厂类，调用统一的超类接口，实例化相应的子类对象，实现解耦。

#### 策略模式

封装实现同一功能的不同算法，通过Context上下文方式加载不同策略，可以和简单工厂模式结合使用。

#### 单一责任原则

就一个类而言，应该只有一个引起它变化的原因。

#### 开放封闭原则
软件实体应该是可以扩展的，但是不可修改。

#### 依赖倒转原则

1.高层模块不应该依赖底层模块，两个都应该抽象依赖。

2.抽象不应该依赖细节。细节应该依赖抽象。

#### 装饰模式

动态地给一个对象添加一些额外的职责，就增加功能来说，装饰模式比生成子类更加灵活。

#### 代理模式

为其他对象提供一种代理以控制对这个对象的访问。

#### 工厂方法模式

定义一个用于创建对象的接口，让子类决定实例化哪一个类。工厂方法使一个类的实例化延迟到了其子类。

#### 原型模式

用原型实例指定创建对象的种类，并且通过拷贝这些原型创建新的对象。

#### 模板方法模式

定义一个操作中的算法的骨架，而将一些步骤延迟到子类中。模板方法使得子类可以不改变一个算法的结构即可重定义该算法的某些特定的步骤。

#### 迪米特法则

如果两个类不必彼此直接通信，那么这两个类就不应该发生直接的相互作用。如果其中一个类需要调用另一个类的摸一个方法的话，应该同通过第三方转发这个调用。

#### 外观模式（门面模式）

为了系统中的一组接口提供一个一致的界面，此模式定义了一个高层接口，这个接口使得这以子系统更加容易使用。

#### 建造者模式

将一个复杂对象的构建与他的表示分离，使得同样的构建过程可以创建不同的表示。

#### 观察者模式（发布订阅）

一对多的依赖关系，让多个观察者对象同时监听某一个主题对象。这个主题对象在状态发生变化时，会通知所有观察者对象，使它们能够自动更新自己。

#### 抽象工厂方法

提供一个创建一系列相关或相互依赖对象的接口，而无需具体指定他们的实现。

#### 状态模式

当一个对象的内在状态改变时允许改变其行为，这个对象看起来像是改变了其类。（状态模式主要解决的是控制一个对象状态转换的条件表达式过于复杂时的情况）

#### 适配器模式

将一个类的接口转换成客户希望的另一个接口。Adapter模式使得原本由于接口不兼容而不能一起工作的那些类可以一起工作。

#### 备忘录模式

在不破坏封装性的前提下，捕获一个对象的内部状态，并在对象之外保存这个状态。这样以后就可将对象恢复到原先保存的状态。

#### 组合模式

将对象组合成树形结构以表示 “部分-整体” 的层次结构。组合模式使得用户对单个对象和组合对象的使用具有一致性。 



