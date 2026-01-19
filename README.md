# 🚀 【x-panel】x-panel安装教程
<div align="center">
  <a href="https://www.youtube.com/@%E8%B5%9B%E5%8D%9A%E4%BA%91%E6%A2%AF">
    <strong>🚀 点击访问赛博云梯 YouTube 主页</strong>
  </a>
</div>
<br><br>
x-panel开源项目：https://github.com/xeefei/X-Panel
<br><br>
准备工作：VPS一台、域名一个
<br><br>

### 更新系统并安装依赖软件：
```
apt update -y&&apt install -y curl&&apt install -y socat
```

### 安装命令：
```
bash <(curl -Ls https://raw.githubusercontent.com/xeefei/x-panel/master/install.sh)
```
> <small>
> **注意： 若你用的是伊朗老哥的3X-UI，是可以直接〔覆盖安装〕的，因为数据库文件等位置是没有改变的，所以直接覆盖安装，并不会影响你〔原有节点及配置〕等数据。如果是其他分支版本，那直接覆盖安装的话，并不能确保一定就能够兼容
</small>
<br><br>

openSSH下载地址：https://github.com/PowerShell/Win32-OpenSSH/releases
> <small>
> 如果出现"不是内部或外部命令，也不是可运行的程序或批处理文件"，就到这里下载ssh工具安装
</small>
