
## 初期化文件环境配置
path:
    1.～/.bash_profile   单一用户
    2./etc/profile      所有用户

### GOROOT
    ```
        export GOROOT = /usr/local/go
    ```

### GOPATH Go语言工作区的集合
    ```
        export GOPATH=~/golib:~/goproject
    ```

### GOBIN 存放编译后的GO的可执行文件
    ```
        export GOBIN = ~/gobin
    ```

### PATH 为了方便GO语言命令和GO程序的可执行文件，需要追加其值
    ```
        export PATH = $PATH:$GOROOT/bin:$GOBIN
    ```

### source <profile>