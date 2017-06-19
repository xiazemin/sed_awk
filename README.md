# ed

sed &awk是基于unix的行编辑器ed

$ ed tes

tes: No such file or directory

?

$ ed id.txt

375

p（显示当前行）

986821055,021

2（移至第二行）

971778119,021

q（退出）

d（删除当前行）

2d（删除第二行）

／regular /d  \(删除包含regular的行\)

g／regular /d \(删除包含regular的所有行\)

1（地址，不指定，对当前行操作）s/4（模式）/24（替换成的对象）/ （替换）

1（地址）s/4（模式）/24（替换成的对象）/ g（一行多次出现，替换）

![](/assets/imported.png)

grep实际上是来源于命令

g/re/p \(全局正则式打印）

ed具有脚本化的工作能力，可以将命令放在脚本中，把脚本名作为参数传入

ed test &lt; ed-script

sed 与ed的主要区别是它是面向字符流的，不会修改原始输入文件

ed 不是面向字符流的，文件本身会改变，脚本退出的时候必须有保存文件的命令

sed会遍历文件，每一行都使用命令

awk也是面向字符流的，并且能解释脚本







