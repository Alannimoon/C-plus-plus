# DEMO 目录结构与依存关系

1. **Models 目录包含了User、Administrator、MD5、CipherText、Date、Time、DateTime、Message 类的头文件与源文件。**
2. **Controlers 目录包含了ControlerAbstractBase 的头文件与源文件。**
3. **Controlers 目录下的Controler_QT 目录包含了派生自ControlerAbstractBase类的Controler_QT类的头
   文件和源文件。**

4. **Projects 目录下的MAC/WINDOWS_QT_5_14_2 目录包括了可在Windows 和macOS 下以QT 编译的工程文件、main.cpp、窗口类的ui 文件、头文件、源文件。**
5. **Projects 目录下的MAC_XCODE_12_5_1 目录包括了可在macOS 下以xcode 编译的工程文件、main.cpp。**
6. **在其他环境中复用 xcode 中的main.cpp 文件，同样可以适用于vsCode、VS，在windows 系统中生成控制台程序。**
7. **Data 目录 用与测试的User.txt 和Messages.txt 文件**