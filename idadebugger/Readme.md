		该模块为ida调试插件；ida官方调试插件为每个平台写server以及client(如android_server/iphone_server)，而没有复用已有的比较好的server端(如gdb/lldb等)，而本插件致力于解析远程调试协议以便实现ida利用gdb/lldb进行调试。由于ida要求调试类型的插件不能是python，因为使用c++作为代理调试器调用python写的协议解析器，完成整个调试过程

		目前尚在开发中