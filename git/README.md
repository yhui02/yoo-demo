# GIT

### 项目中使用GIT

**create a new repository on the command line**

```shell
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git remote add origin https://github.com/yhui02/yoo-demo.git
$ git push -u origin master
```

**…or push an existing repository from the command line**

```shell
$ git remote add origin https://github.com/yhui02/yoo-demo.git
$ git push -u origin master
```

### 指定作者信息

```shell
# 全局
$ git config --global user.name "Yourname"
$ git config --global user.email "example@test.com"

# 局部
$ git config user.name "Yourname"
$ git config user.email "example@test.com"

# 显示
git config user.name    
git config --list
```

### 常用命令

- 拉取：`$ git pull`
- remote查看：`$ git remote -v`
- remote切换到https：`$ git remote set-url https://github.com/yourusername/repository.git`
- remote切换到ssh：`$ git remote set-url git@github.com:yourusername/repository.git`

### 附：SSH

```shell
$ ssh-keygen -t rsa -C "example@test.com"
```
