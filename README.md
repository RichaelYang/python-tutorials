# python-tutorials
python自学教程

一、学会使用命令行

1.pwd 打印当前工作目录

2.cd ~ 回到home

3.mkdir 创建目录（文件夹）

4.cd temp/stuff 到达stuff目录下（文件夹下）
  
  cd ../.. 往回退两个目录

5.ls 查看当前列表的文件夹
  
  dir -R 查看当前目录下的文件夹，以及文件夹里面的所以文件夹

6.rmdir 移除目录

7.pushd 保存当前目录到达其他目录
  
  popd  弹出保存的目录并到达指定地点

8.New-Item  iamcool.txt 创建文件 

9.cp A B 将A文件复制一份命名为B
  
  cp A B/ 将A文件复制一份到B的目录里
  
  cp -r A B 将A文件包括文件里的全部东西复制一份到B文件

10. mv A B 将A文件改名为B
  
    mv A/* B 将A中的文件移动到B中
    
    mv * ../ 将当前目录下的所有文件复制到上一级目录下

11. more  A.txt 浏览A文本中的内容 空格可以翻页

12. rm A 删除文件但A中不包括其他文件夹
    
    rm -r A 删除A文件夹中的所有内容

13. exit 退出命令窗口
