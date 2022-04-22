# GIT常用语句 
### 构建仓库
``` git init ```
### 添加文件
##### 添加文件到暂存
``` git add [file1] [file2] ... ```

##### 添加指定目录到暂存区，包括子目录：
``` git add [dir] ```
##### 添加当前目录下的所有文件到暂存区：
``` git add . ```
##### 用于查看项目的当前状态
``` git status ```
##### 查看远端
``` git remote -v ```
### 设置远端
` git remote add origin [url] `
##### 设置多个远端分支
``` 
git remote add [名字] [地址1]

git remote set-url [名字（和上面一样）] --push --add [地址1]
git remote set-url [名字（和上面一样）] --push --add [地址2]

#推送
git push -u [名字] [分支] 


```



- 1
- 2
- 3
1. aa

2. vvv

3. bb

4. lkjfgd 

```
fun(){
	val i = 0
	(1..45).foreach{
		
	}
}
```