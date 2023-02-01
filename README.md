#SSH

右键 Git Bash Here

## config
```
$ git config --global user.name "chenliujin"
$ git config --global user.email "liujin.chen@qq.com"
```

## 生成密钥
```
$ cd ~
$ pwd
/c/Users/Administrator

$ cd .ssh
$ ssh-keygen -t rsa -C "liujin.chen@qq.com"
$ cat id_rsa.pub
```
## Github配置SSH
* 点击用户头像
* Settings
* SSH and GPG keys
* New SSH key



## git clone
```
$ git clone https://github.com/chenliujin/Git.git
```

### git clone branch
```
# laravel branch 5.1
$ git clone -b 5.1 --single-branche https://github.com/laravel/laravel.git

# which branch
$ git branch
```

## 查看当前分支
```
$ git remote -v
origin  https://github.com/chenliujin/MapReduce (fetch)
origin  https://github.com/chenliujin/MapReduce (push)
```

## 提交修改
```
$ git add mysqldump.sh
$ git commit -m 'db backup'
$ git push origin master
```

## 撤销本地修改
```
$ git checkout {file}
```

## 移动文件
```
$ git mv xmlrpc.php blog/
$ git commit -m 'wordpress'
```


# 重置某个文件

```
git checkout README.md
```


- [腾讯](https://github.com/Tencent)
