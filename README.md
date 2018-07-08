# Design-Patterns



共享模式
：模式能够用更少的词汇座更充分的沟通。
将说话的方式保持在模式层次，可以减少琐碎的事情。
共享词汇可以帮住开发团队快速充电。
共享词汇帮助初级开发人员迅速成长。


库与框架长久以来，一直扮演着软件开发过程的重要角色，我们从中挑选所要的组件，把他们放进合适的地方，但是……库与框架无法帮助我们将应用组织成容易理解，容易维护，具有弹性的架构，所以需要设计模式。
设计模式告诉我们如何组织类和对象以解决某种问题。


OO基础：
抽象，封装，多态，继承。







设计原则 ：
一：封装变化：
找出应用中可能需要变化之处，把他们独立出来，不要和那些不需要变化的代码混在一起。
-->结果：代码变化引起的不经意后果变少，系统变得有弹性。
二：
针对接口编程，而不是针对实现编程。（针对接口编程的真正意思是：针对超类型编程。
--》
三：
多用组合，少用继承。
使用组合建立系统具有很大的弹性，不仅可以将算法簇封装成类，更可以在运行时动态的改变行为，只要组合的行为对象符合正确的接口标准即可。
