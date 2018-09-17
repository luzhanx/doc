# Git操作手册

1. 项目目录下初始化git
```
git init 
```
2. 关联到远程库
```
git remote add origin https://github.com/用户名/项目名.git
```

3. 拉取远程代码 获取远程库与本地同步合并（如果远程库不为空必须做这一步，否则后面的提交会失败）
```
git pull rebase origin master
```

4. 提交至远程仓库
```
git add .               // 提交全部
git commit "提交备注"    // 必须是双引号
git push -u origin      // 把本地库的内容推送到远程
```

## 下载代码
```
git clone https://github.com/用户名/项目名.git
```


## 配置使用人
```
git config --global user.name "用户名"
git config --global user.email "邮箱"
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
## Vscode提交代码
```
1. 点击加号+ 
2. 点击√ Commit暂存 输入上传信息
3. 发布分支
```
