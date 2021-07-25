### python 多态
多态(polymorphism)指的是“为不同的基础形态(数据类型)提供相关接口的能 力”。接口，指的是函数或方法。下面就是一个多态的示例:

* print("Hello, World!")
* print(200)
* print(200.1)

* * Hello, World!
* * 200
* * 200.1  

* print 函数为字符串、整数和浮点数这 3 种不同的数据类型提供了相同的接口。 我们不必定义并调用 3 个不同的函数(如调用 print_string 打印字符串， print_int 打印整数，print_float 打印浮点数)，只需要调用 print 函数即可支 持所有数据类型。