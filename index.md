# 这个第一个功能
# 这是第二个新功
## 这是第三个新功
### 这是第四个功
## $ git commit --all(全都) -m "这是一次性放入仓储的命令"
- 新的功能
 	+ `git log` 查看提交修改日志
 	+ `git log --oneline` 查看简洁的日志 
## 回退到指定的版本 （代码）
- `git reset --hard Head~0`
	+ 表示回退到上一次代码提交时的状态
- `git reset --hard Head~1`
	+ 表示回退到上上次代码 Head~2 一次类推n+
- `git reflog`
	+ 可以看到每一次切换版本的记录：可以看到所有提交的版本号