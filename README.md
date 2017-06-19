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



