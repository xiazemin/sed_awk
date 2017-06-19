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

