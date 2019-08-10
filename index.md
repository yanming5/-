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
- `git branch dev` 创建dev
- `git branch` 查看创建的有哪些
- `git branch -d dev`删除dev分支环境
- `git checkout dev` 是切换到dev里面去
- `git merge dev` 代码合并到master里面
## GitHub 
- https://github.com
- 一个提供存储代码的网站 通过git上传代码的功
- `git push [地址] master`
	+ 会把当前分支的内容上传到远程的master分支上
- `git pull [url] master`
	+ 会把远程分支的数据获取到：（本地：注意需要初始化一个仓储！）
- `git clone [url]`
	+ 会得到远程仓储相同的数据，唯一不同的是会自动创建目录，如果多次执行会覆盖本地内容