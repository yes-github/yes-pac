# yes-pac

#### 介绍
代理自动配置（PAC）文件是一个 JavaScript 脚本，其核心是一个 JavaScript 函数，用来决定网页浏览请求（HTTP、HTTPS，和 FTP）应当直连目标地址，还是被转发给一个网页代理服务器并通过代理连接。

#### 脚本使用前的准备工作
- [安装GenPAC](https://github.com/JinnLynn/genpac/tree/master#readme)
```bash
# 安装或更新
pip install -U genpac
# 或从github安装更新开发版本
pip install -U https://github.com/JinnLynn/genpac/archive/dev.zip
# 卸载
pip uninstall genpac
```

#### 参考资料
- [代理自动配置文件（PAC）文件](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Proxy_servers_and_tunneling/Proxy_Auto-Configuration_PAC_file)