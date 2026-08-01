#include <iostream>
int main() {
	// 转义字符
	
	// 换行符\n 
	std::cout << "Hello, World!\n";	
	// 反斜杠 \\如果要输出反斜杠本身，需要使用两个反斜杠来表示一个反斜杠		

	std::cout << "\\\n";
	;
	// 水平制表符 \t  作用可以整齐输出数据
	std::cout << "aasaaaa\thelloworld \n";
	std::cout << "aaacaa\thelloworld \n";
	std::cout << "aaqaa\thelloworld \n";
	std::cout << sizeof('\\\\\n') << "\n";//查看转义字符占内存空间大小，为1个字节。C++ 标准明确规定：单引号中写多个字符时，数据类型是 int（整型），而不是 char（字符型）。char则只占一个字节。



    return 0;
}

# study
study C++
2026/8/1转义字符
