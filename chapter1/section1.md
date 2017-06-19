# awk

与sed相似，每个输入行执行一套指令

awk  ‘instructions'  files

awk -f script files

awk更像一种编程语言，sed是命令集合

awk 将每个输入行解释为一条记录，将一行的每个单词（空格或制表符分隔）解释为字段 $0表示所有字段

