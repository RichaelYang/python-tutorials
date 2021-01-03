# python-tutorials
python自学教程

github排版https://www.cnblogs.com/ray-h/p/10487054.html

## 一、学会使用命令行

**1.** pwd 打印当前工作目录

**2.** cd ~ 回到home

**3.** mkdir 创建目录（文件夹）

**4.** cd temp/stuff 到达stuff目录下（文件夹下）
  
  cd ../.. 往回退两个目录

**5.** ls 查看当前列表的文件夹
  
  dir -R 查看当前目录下的文件夹，以及文件夹里面的所以文件夹

**6.** rmdir 移除目录

**7.** pushd 保存当前目录到达其他目录
  
   popd  弹出保存的目录并到达指定地点

**8.** New-Item  iamcool.txt 创建文件 

**9.** cp A B 将A文件复制一份命名为B
  
  cp A B/ 将A文件复制一份到B的目录里
  
  cp -r A B 将A文件包括文件里的全部东西复制一份到B文件

**10.** mv A B 将A文件改名为B
  
   mv A/* B 将A中的文件移动到B中
    
   mv * ../ 将当前目录下的所有文件复制到上一级目录下

**11.** more  A.txt 浏览A文本中的内容 空格可以翻页

**12.** rm A 删除文件但A中不包括其他文件夹
    
   rm -r A 删除A文件夹中的所有内容

**13.** exit 退出命令窗口 

## 二、输出和输入

### 1.输出print()

print("")

print(f"how to use print {varible}")

print("{},{},{}".format(1,2,3))

### 2.输入input()

weight=input("how much do you weigh?",end=" ") //end=" " 指的是不换行

### 3.argv输入法(系统变量输入法)

执行命令行

python ex12.py 1 2 3

from sys import argv

script,one,two,three=argv **解包

### 4.对文本进行处理

txt=open(filename，'w')打开文本 r w r+ w+ 文件指针都是放在开头，即如果是可以写入的模式，则会删除原来的内容。 a a+ 模式则指针放在文本结尾，用于添加内容不会删除原先内容。


print(txt.read())  **打印文本内容

txt.truncate() **清空文本

txt.write("a") **在文本中写入内容

txt.close() **关闭文本

txt.seek(0) **把读写位置放在文件最开头

txt.readline()  **读文本的一行内容

## 三、函数

### 1. 函数格式

    def function(*args):
    arg1,arg2=args

    return arg1
    

    def  function(arg):

     print(f"the variable is {arg}")

### 2. 函数的使用

function(1,2)





