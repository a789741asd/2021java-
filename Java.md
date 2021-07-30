# Java

[toc]



## 基础

### 异常

#### error和exception

![image-20210716112550538](/Users/qiuzhangyu/Library/Application Support/typora-user-images/image-20210716112550538.png)

都继承了throwable类

- **Exception** :程序本身可以处理的异常，可以通过 catch 来进行捕获。Exception 又可以分为 checked- Exception(必须处理) 和 Un-Checked-Exception不受检查异常(可以不处理)。
- **Error** ：Error 属于程序无法处理的错误 ，我们没办法通过 catch 来进行捕获 。例如，Java 虚拟机运行错误（Virtual MachineError）、虚拟机内存不够错误(OutOfMemoryError)、类定义错误（NoClassDefFoundError）等 。这些异常发生时，Java 虚拟机（JVM）一般会选择线程终止。

常见运行时异常：空指针异常 数组越界 类型转换异常 。

Error：虚拟机运行错误，超内存，栈溢出。





