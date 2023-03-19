## 1 本地与远程Git仓库同步
1.GitHub新建空仓库（注意不要添加任何文件）
![[c913f58ccf614d4f8a71bae9351fd0b.png|800]]

2.本地新建文件夹，文件夹内新建README.md文件。右键git bash here,按上图步骤操作

3.在本地仓库文件夹内新建Obsidian仓库，或者直接复制到文件夹内

4.执行命令push到remote 
```
git add .
git commit -m ""
git push origin main
```

## 2 基本配置
1.取消缩进  

2.复制插件和主题文件到.obsidian文件夹下

## 3 clone到本地仓库
[(272条消息) 如何使用git从github拉取自己的私有仓库(Token方式、本地秘钥方式)_Night-Breeze晚风的博客-CSDN博客](https://blog.csdn.net/qq_45491549/article/details/128825216?spm=1001.2101.3001.6650.3&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EYuanLiJiHua%7EPosition-3-128825216-blog-124340158.pc_relevant_3mothn_strategy_recovery&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EYuanLiJiHua%7EPosition-3-128825216-blog-124340158.pc_relevant_3mothn_strategy_recovery&utm_relevant_index=6)

参考上述连接
* token
 `git clone https://Mofy-freshman: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@ghproxy.com/https://github.com/Mofy-freshman/Obsidian.git`
* ssh key
