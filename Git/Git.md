### git常用命令
git commit -m '提交的描述信息内容' --no-verify  
--no-verify跳过eslint代码检查提交（webstorm中取消git hook也可跳过检查）

#### 只更新某个文件/夹  
- 文件夹：
    ```
    cd projectFolder //进入文件夹目录
    git fetch
    git checkout origin/master ./
    ```
    
- 指定文件：
    ```
    cd projectFolder //进入文件夹目录
    git fetch
    git checkout origin/master ./index.js //更新index.js文件
    ```