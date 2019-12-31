# Git
**本文显示如何学习使用git。**
### **git 的`使用逻辑`如下：**
-  创建项目git clone git init
-  创建分支、推送分支、合并分支
- 删除分支、回退版本
### **使用流程如下：**
1. 在github或者gitee上找到喜欢的库（resporiy）.
2.  复制链接，在本地打开cmd 使用安装好的gitbash下载库。命令为 `git clone [链接]`
-  注意下载的命令分为三个部分 
    - `git` 是指使用git程序 
    - `clone` 是git 中的一个操作
    -  `[链接]` 这一部分是你要完整的用链接进行替换的。
- 下载完成后 在cmd中用`cd [文件夹名称]`进入git下来的文件夹

3.  开始开发，在长达一天/多天/几小时的开发过程中，你其实并不需要时刻链接网络，甚至可以关机重启。因为写的文件是保存在本地的，而你的一切git的操作只与本次的log文件有关，所以你只需要保证在将写的文件push到云的时候网络是畅通的即可。
    **关键操作如下：**
    - `git status `本文件夹下的信息，比如目前是在哪一个分支，如果新建了文件有没有提交到git上
    -  如果有新的文件，可以选择使用 `git add [文件名]`来添加文件
    -  如果新的文件有很多，可以选择使用 `git add . `来表示添加所有更新过的文件
	-  `git commit -m "有关这次提交的信息"` ，使用这一个命令来提交到本地git，""里面的内容是注释
	-  当觉得需要放到网上保险/和伙伴共享的时候，需要git push 来推送到云端(远程仓库)
		- 在 push 之前，可以使用 git remote -v 来查看远程仓库情况
		- 然后就可以使用 git push origin master 推送到远程仓库
- git branch -a 确定当前分支情况 


![示意图](https://bucket-for-things.oss-cn-beijing.aliyuncs.com/Learn/git/git-1.png)



You can use the [editor on GitHub](https://github.com/wsqstar/Learn-git/edit/master/README.md) to maintain and preview the content for your website in Markdown files.
Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.
### Markdown
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for
```markdown
Syntax highlighted code block
# Header 1
## Header 2
### Header 3
- Bulleted
- List
1. Numbered
2. List
**Bold** and _Italic_ and `Code` text
[Link](url) and ![Image](src)
```
For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
### Jekyll Themes
Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/wsqstar/Learn-git/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.
### Support or Contact
Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

