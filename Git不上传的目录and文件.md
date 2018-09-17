# Git不上传的目录and文件

```
# 创建.gitignore 文件 gitignore写法
# 此为注释 – 将被 Git 忽略

*.js        # 忽略所有 .js 结尾的文件
!lib.a      # 但 lib.js 除外
/TODO       # 仅仅忽略项目根目录下的 TODO 文件，不包括 subdir/TODO
build/      # 忽略 build/ 目录下的所有文件
doc/*.txt   # 会忽略 doc/notes.txt 但不包括 doc/server/arch.txt
```

