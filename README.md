# Python课程

## Day 1

Python 3 零基础完全入门
<https://www.udemy.com/course/python3-chinese/learn/lecture/12959852#overview>

- 第一节: Introduction - 55 mins

## Day 2

Python 3 零基础完全入门
<https://www.udemy.com/course/python3-chinese/learn/lecture/12959852#overview>

- 第二节：基本数据类型 - 49 mins

## Day 3

### 中文课程

Python Flask Web开发入门与实践
<https://www.udemy.com/course/python-flask/learn/lecture/13881140#overview>

- 第一节：Hello World - 24 mins

### English

Python Flask for Beginners: Build aCRUD web app using Flask
<https://www.udemy.com/course/python-flask-beginners/learn/lecture/8978806?start=0#overview>

- 第一节：Introduction and Course Structure - 3 mins
- 第二节：Understanding how the web works - 4 mins
- 第三节：Setting up your development enviornment and your first Flask application - 30 mins

## Day 4 - Git and GitHub

需要安装的软件

- Git <https://git-scm.com/>
- GitHub Desktop <https://desktop.github.com/>
- Visual Studio Code <https://code.visualstudio.com/>

## Day 5 - 基本命令行使用

Mac电脑使用Cmd+Space启动搜索框，然后输入 iterm 打开命令行

如果没有iTerm，请从<https://iterm2.com/>下载并安装

```shell
## 查看当前文件夹位置
pwd

## 列出当前文件夹内容
ls -la

## 进入特定文件夹
## 文件夹名称不用输入完整，可以输入几个字符以后按Tab键，系统会自动补齐
cd <文件夹名称>

## 返回上级文件夹
cd ..

## 文件操作中
## . 代表当前文件夹
## .. 代表上级文件夹

## 相对路径和绝对路径
## 假设你处于 /a/b/c/d 的 c文件夹中
## 如果要进入下一级文件夹可以使用
## 相对路径
cd d
## 绝对路径
cd /a/b/c/d
## 所以绝对路径就是从磁盘根目录开始的完整路径，而相对路径就是从当前位置开始的部分路径

## 创建目录
mkdir <文件夹名称>

## 删除目录 - 注意：rm 操作非常危险，因为它不会给你任何确认信息，甚至可以直接抹除整个磁盘的内容，慎重使用
rm -rf <文件夹名称>

## 删除文件
rm -rf <文件名>

## 在任何需要输入<文件名>和<文件夹名称>的地方都可以使用部分输入+Tab的方式快速完成输入
```
