# git版本管理工具学习记录  
---
#### 基础操作  
---
##### 初始化  
>git init  

##### 进行添加文件  
> git add filename  

##### 进行提交  
>git commit -m"说明"  

##### 进行远程推送  
>git push

##### 克隆远程仓库  
>git clone git@git.xxxxxxxxxxx  

##### 进行远程拉取
>git pull

&emsp;&emsp;当我们进行git add的时候，其实是把文件添加进了暂存区；当git commit的时候，就把文件添加进入了当前分支；git push则是进行推送到远程分支；  

##### 查看提交日志  
>git log  （--pretty=oneline）

- HEAD指向的版本就是当前版本，git reset --hard commit_id即可回退到指定版本。
- git reflog 查看历史指令



