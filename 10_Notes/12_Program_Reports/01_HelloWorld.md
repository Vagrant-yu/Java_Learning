## [01_HelloWorld_Report](../../20_Programs/01_HelloWorld/src/HelloWorld.java)

---

### 实验报告：第一个 HelloWorld 程序

**一、 实验环境**

* **操作系统：** macOS
* **开发工具：** Visual Studio Code

**二、 实验代码**

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("hello world!");
    }
}

```

**三、 代码结构逐行解释**

1. **`public class HelloWorld {`**
    * **解释：** 这是类的声明。Java 是一门面向对象的语言，所有代码逻辑都必须包含在**类（class）** 中。`public` 访问修饰符表示这个类是公开的。
    * **注意：** 在 Java 中，被 `public` 修饰的类，其名称必须与保存的文件名（如 `HelloWorld.java`）完全一致。末尾的 `{` 代表类作用域的开始。


2. **`public static void main(String[] args) {`**
    * **解释：** 这是程序的主方法，也是 Java 程序的固定入口点。Java 虚拟机（JVM）启动时会寻找并执行这个方法。
    * `public`：保证 JVM 能够调用该方法。
    * `static`：表示这是静态方法，JVM 无需先创建类的实例对象即可直接运行它。
    * `void`：表示该方法执行完毕后没有返回值（与 C 语言中的 void 用法一致）。
    * `String[] args`：是一个字符串数组，用于接收通过命令行传入的外部参数。




3. **`System.out.println("hello world!");`**
    * **解释：** 这是核心的执行语句，用于在控制台输出信息。它调用了 Java 系统核心类 `System` 里的标准输出对象 `out`，并使用 `println` 方法将双引号内的字符串 `"hello world!"` 打印到屏幕上，同时在末尾自动添加一个换行符。末尾的分号 `;` 是语句结束的标志。


4. **`}` (倒数第二行)**
    * **解释：** 闭合 `main` 方法的大括号，标志着主方法执行逻辑的结束x。


5. **`}` (最后一行)**
    * **解释：** 闭合 `HelloWorld` 类的大括号，标志着整个类代码块的结束。



**四、 运行结果截图**
![](./Asset/截屏2026-03-09%2019.39.11.png)

---
