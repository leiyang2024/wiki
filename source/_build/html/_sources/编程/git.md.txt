# git
 
## 常用命令

初始化设置

```
echo "# wiki" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/leiyang2024/wiki.git
git push -u origin main
```

## 一些有用的设置
- 设置不同步项，一些大文件等内容，通常不需要同步
- readthedoc不需要build内的文件 

创建配置文件
```
code .gitignore
```
写入忽略路径
```
gitignore
```
