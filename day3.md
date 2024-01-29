## day3

vim 语法: 操作 + 范围
操作：
删除：d
删除并进入插入模式：c
复制：y

基于单词/字串的移动：
移动到单词的结尾：e
移动到上一个单词的开头：b
移动到单词的开头：w

组合：
删除当前单词：cw
在当前单词结尾处添加：ea

===  
练习：

function insertNum(num){
let str = 'hello world'
let newStr = `${str} ${num}`
return newStr
}

hello worldworldworldworldworldworldworldworldworldworldworldddworldworldworldworldworldworld

first elevenninthseventhfifththirdsecondforthsixtheighthtenthtwelve first

first second third fourth fifth sixth seveth eighth ninth tenth
