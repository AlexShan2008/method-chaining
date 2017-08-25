## A simple way to realize jQuery chaining method

### 链式操作的优点：
```
1. 节约jS代码；
2. 因为操作所返回的都是同一个DOM对象，可以提高性能。
```
### DOM需要解决的问题：
```
1.通过简单扩展原型方法并通过return this的形式来实现跨浏览器的链式调用。

2.利用JS下的简单工厂模式，来将所有对于同一个DOM对象的操作指定同一个实例。
```
###