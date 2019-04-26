# huffman_unzip
基于哈夫曼编码实现的解压缩器(C语言实现)

【基本要求】
设计一个哈夫曼编码、译码系统。对一个文本文件中的字符进行哈夫曼编码，生成编码文件；反过来，可将编码文件译码还原为一个文本文件。
(1) 读入一篇英文短文(文件扩展名为txt)；
(2) 统计并输出不同字符在文章中出现的频率(空格、换行、标点等也按字符处理)；
(3）根据字符频率构建哈夫曼树，并给出每个字符的哈夫曼编码；
(4）哈夫曼编码；
(5）利用已建好的哈夫曼树，将文本文件进行编码，生成压缩文件(编码文件后缀名为.huf)；
(6）用哈夫曼编码存储的文件和输入文本文件大小进行比较，计算文件压缩率；
(7）进行译码，将huf文件译码为txt文件，与原txt文件进行比较。

【程序流程】
在屏幕上显示菜单选项→用户输入选择→进行压缩/解压/比较/退出操作

【各程序模块之间的层次关系】
main.cpp调用menu.cpp、yasuo.cpp、jieya.cpp和check.cpp的内容。
 
