# sed

sed  ［－e\]  'instruction' file\(多个指令的时候才加－e，加引号是为了替换空格和特殊字符\)

![](/assets/importsed.png)

使用脚本文件：

sed -f scriptfile file &gt; newfile  不能重定向到当前文件，否则会出现乱码，sed会默认输出每个输入行，－n选项可以组织自动输出





