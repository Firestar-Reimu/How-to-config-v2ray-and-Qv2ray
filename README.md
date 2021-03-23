# v2ray 和 Qv2ray 使用指南 

### 下载 v2ray 和 Qv2ray

v2ray-core 的下载地址：

https://github.com/v2fly/v2ray-core/releases

Qv2ray 的下载地址：

https://github.com/Qv2ray/Qv2ray/releases

**Manjaro 上可以直接用包管理器分别下载这两个软件：`yay -S v2ray qv2ray`**

### 安装 v2ray 和 Qv2ray

**Manjaro 上直接用包管理器安装即可**

Windows 上，建议先安装 Qv2ray 再安装 v2ray

Qv2ray 下载后是一个 `.exe` 安装文件，默认安装即可

v2ray 下载后是一个压缩包，解压缩后复制到 `C:\Users\(user_name)\AppData\Local\qv2ray`，并更改文件名为 `vcore`

### 购买服务器

可以在这里购买：（可以使用支付宝付款）

https://v2sx.com/cart.php?gid=1

登陆账号购买后，在用户主界面的“您已激活的产品/服务”中可以找到服务器的信息：

用户信息：**UUID**

线路列表：**名称**、**服务器地址**、**端口**

### 配置 Qv2ray

首选项 --> 内核设置 --> 点击“检查 V2Ray 核心设置” --> 若弹出“V2Ray 路径配置检查通过”窗口，说明 v2ray 配置成功

默认分组 --> 新建 --> 手动输入 --> 简单编辑器 --> “标签”填入“**名称**”，主机填入“**服务器地址**”，端口填入“**端口**”，UUID填入“**UUID**”

**这四个值必须与网站上的值一一对应**

这时在“默认分组”中便可以找到新建的服务器，右键点击该服务器，选择“连接到此服务器”即可

### 配置浏览器

Edge 不需要任何设置

Firefox 设置如下：

首选项 --> 网络设置 --> 选择“自动检测此网络的代理设置”，或选择“使用系统代理设置”并双击 Qv2ray 图标，在“系统代理”一栏启用系统代理

### 仍然存在的问题

Firefox 浏览部分网页会出现“PR_END_OF_FILE_ERROR”，应该与服务器选择有关

### 参考资料

Qv2ray -- 快速上手
https://qv2ray.net/lang/zh/getting-started/
