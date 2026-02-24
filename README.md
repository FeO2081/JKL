# JKL

JKLang是一个新的宏语言。它是基于C++的编译器和语法结构的。

JKLang is a new macro language. It is based on the C++ compiler and syntax structure.

---

版本0.1

1. 建立了文件目录结构。
   - com - 编译器文件
   - fam - 家庭关系列表
   - gen - 生成临时文件
   - out - 输出正式文件
   - src - jkl源代码
2. 编写了lisa的0.1版本
   - 属性值和函数权限默认为private
   - 没有函数体的视为虚函数
   - 带be前缀的是回调函数，否则为常规函数

Version 0.1

1. File directory structure established.
   - com - Compiler files
   - fam - Family relationship list
   - gen - Generate temporary files
   - out - Output final files
   - src - JKL source code
2. Version 0.1 of Lisa was written.
   - Attribute values ​​and function permissions are private by default.
   - Functions without a body are considered virtual functions.
   - Functions prefixed with "be" are callback functions; otherwise, they are regular functions.
