# Project

FileCompress是在Linux中开发的，所以只有一些头文件和源文件，可以把要压缩的文件拷贝至工程根目录下，按照指定的命名格式命名文件，
运行程序，会在工程根目录下生成压缩文件。  (文件命名格式在 config.hpp中，修改相应的文件名就可以了)

STL实现平台是Windows下Visual Studio 2015，容器中的STL是开发时的整个工程，可以整体下载下来，在不低于VS2015版本中可直接运行。

DownloadTool是仿照迅雷实现的一个下载工具，使用ncurses库简单实现了一个界面。使用时，需要make，生成mythunder可执行文件，
运行该文件，在相应的url输入栏输入要下载资源的链接，在显示窗口可显示各个文件的下载情况，该工具支持断点续传。
