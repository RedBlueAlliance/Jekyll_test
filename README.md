# Jekyll_test.github.io一个测试页面
### 如何创建一个jekyll项目
创建一个jekyll项目my_blog
>命令：
jekyll new my_blog

项目结构


进入my_blog目录，输入下面命令，开启jekyll服务
>命令：
jekyll serve

浏览器进入：http://127.0.0.1:4000/


$ echo "# Jekyll_test.github.io" >> README.md
$ git init
>已初始化空的 Git 仓库

$ git add README.md
$ git commit -m "first commit"
>
来设置您账号的缺省身份标识。
如果仅在本仓库设置身份标识，则省略 --global 参数。
fatal: empty ident name (for <(null)>) not allowed

$ git config --global user.email "you@example.com"
$ git config --global user.name "Your Name"
$ git commit -m "first commit"
>
[master（根提交） d9f771d] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

$ git remote add origin https://github.com/RedBlueAlliance/Jekyll_test.github.io.git
$ git push -u origin master
>
Username for 'https://github.com': RedBlueAlliance
Password for 'https://RedBlueAlliance@github.com':
分支 master 设置为跟踪来自 origin 的远程分支 master。

$ git add .
$ git commit -m "first commit"
>
[master 1ddf0ba] first commit
 32 files changed, 3485 insertions(+)

$ git push -u origin master
>
Username for 'https://github.com': RedBlueAlliance
Password for 'https://RedBlueAlliance@github.com':
对象计数中: 48, 完成.
Delta compression using up to 4 threads.
压缩对象中: 100% (41/41), 完成.
写入对象中: 100% (48/48), 48.21 KiB | 0 bytes/s, 完成.
Total 48 (delta 7), reused 0 (delta 0)
remote: Resolving deltas: 100% (7/7), done.
To https://github.com/RedBlueAlliance/Jekyll_test.github.io.git
   d9f771d..1ddf0ba  master -> master
分支 master 设置为跟踪来自 origin 的远程分支 master。
