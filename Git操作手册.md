# Git操作手册
> Git下载国内镜像地址 https://github.com/waylau/git-for-win

1. 下载代码到本地
```
git clone https://github.com/用户名/项目名.git
```
2. 关联到远程库
```
git remote add origin https://github.com/用户名/项目名.git
```

3. 拉取远程代码 获取远程库与本地同步合并
```
git pull rebase origin master
```

4. 提交至远程仓库
```
git add .                   // 提交全部
git commit "提交备注"        // 必须是双引号
git push origin master      // 把本地库的内容推送到远程
```

## 配置使用人
```
git config --global user.name "用户名"
git config --global user.email "邮箱"
```

## 查看配置使用人
```
git config --global user.name 
git config --global user.email 
```

## git pull rebase origin master失败解决方案
> 因为他们是两个不同的项目，要把两个不同的项目合并，git需要添加一句代码，在git pull,这句代码是在git 2.9.2版本发生的，最新的版本需要添加--allow-unrelated-histories

```
git pull origin master --allow-unrelated-histories
```


## 强制提交 提交冲突使用暴力神器
```
git push origin master -f
```
## 提交冲突解决方案
```
# 把远程代码更新下来
git pull origin master 

# Accept Current Change         // 使用当前代码
# Accept Incoming Change        // 使用最新仓库代码
# Accept Both Change            // 两者都要
# Compare Change                // 对比改变

# 改完之后 重新强制提交 -f
git add .
git commit -m "备注"
git push origin master -f
```

## 分支
```
git branch 不带参数：列出本地已经存在的分支，并且在当前分支的前面加“*”号标记 
git branch branchname 创建分支 
git checkout branchname 切换分支
```
## 回滚版本
```
git log     查看提交记录
git reflog  查看提交记录，寻找合适的commitId

git reset --hard commitid 回滚到指定的版本 commitid从git reflog查看
git reset --hard HEAD     会滚到之前一个版本
git push origin master -f 回退版本一定要强制提交仓库
```
