### 关于compile和build的区别

---

*  compile是**编译**的意思，build是**链接**的意思
*  compile的作用是对你的代码进行语法检查，将你的文本程序语言转化成计算机可运行的二进制文件。
*  build的作用是将你在程序中调用到的类库融合到你的程序中，比如你用到了printf()函数，那么实现该函数的类库代码就会添加到你的程序中。
*  compile的过程生成.obj文件或.o文件，这取决于编译器。
*  build过程生成.exe文件，可直接运行。
