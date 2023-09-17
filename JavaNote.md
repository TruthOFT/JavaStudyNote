# Java 基础语法

一个 Java 程序可以认为是一系列对象的集合，而这些对象通过调用彼此的方法来协同工作。下面简要介绍下类、对象、方法和实例变量的概念.

对象：对象是类的一个实例，有状态和行为。例如，一条狗是一个对象，它的状态有：颜色、名字、品种；行为有：摇尾巴、叫、吃等.

类：类是一个模板，它描述一类对象的行为和状态.

方法：方法就是行为，一个类可以有很多方法。逻辑运算、数据修改以及所有动作都是在方法中完成的.

实例变量：每个对象都有独特的实例变量，对象的状态由这些实例变量的值决定.
```
public class HelloWorld {
    /* 第一个Java程序
     * 它将输出字符串 Hello World
     */
    public static void main(String[] args) {
        System.out.println("Hello World"); // 输出 Hello World
    }
}
```
#### *<font color=Blue>public</font>*  *<font color=Red>static</font>* *<font color=Brown>void</font>* *<font color=Coral>main</font>*(*<font color=Cyan>String[]</font>* *<font>args<font>*)
#### <font color=Blue>访问修饰符</font> <font color=Red>关键字</font> <font color=Brown>方法返回值类型</font> <font color=Coral>方法名</font> <font color=Cyan>变量类型(String 类)</font> <font>参数名<font>