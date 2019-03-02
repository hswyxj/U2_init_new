# 前提：

1、安装python3环境，并安装了atx—uiautomator2库
```bash
安装atx—uiautomator2库：pip install uiautomator2==0.1.11.dev1
```
2、ATX-server平台已经成功启动

3、适用uiautomator2最新版：0.1.11.dev1

# 启动

1. U2init.py目录下执行，初始化连接ATX-server
```bash
python -m U2init init --server ATX-server_ip:8000
```

2. 如果只是初始化，直接执行
```bash
python -m U2init init 
```
