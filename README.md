# 知识付费服务器端
- 这是一款知识付费服务器端
- 下载，激活即可永久使用。
- 可定时自动更新课程内容，每日都有新课程。
- 无企业：做代理，做推广，拿分成
- 有企业：自己运营网站，独立收益，可招代理和推广，分成自行设置。
- 你可以通过这个服务器迅速创建自己的知识付费服务器，迅速创业
- 课程永久就免费自动更新！

<img decoding="async" src="https://github.com/dhrdzy/KnowledgePayment_Server/blob/main/image/2.png" width="13%" hight="13%">
<img decoding="async" src="https://github.com/dhrdzy/KnowledgePayment_Server/blob/main/image/1.jpg" width="13%" hight="13%"> 

# 企业独立完整版（5000元）
- 必须有注册公司才能用，一次付费终生使用，下载后一键启动服务器。
- [下载](https://github.com/dhrdzy/KnowledgePayment_Server/releases/download/1.0.0.1/KnowledgePayment_Server_Enterprise.zip)

# 企业版本配置方法
- 1、去[支付宝开放平台](https://openhome.alipay.com/) 注册一个企业支付宝账户。
- 2、申请一个网页应用，填入所有必要的信息。
- 3、配置“appid.txt”文件内容：将刚申请的网页应用的appid粘贴到appid.txt内，不要有换行，保存并关闭即可。
- 4、生成公钥和私钥pem文件：去[文档中心](https://opendocs.alipay.com/common/02kipk?pathHash=0d20b438) 下载秘钥工具，进行公钥和私钥的生成，生成后，公钥改名成“支付宝公钥.pem”，私钥改名成“应用私钥_RSA2_非JAVA.pem”，覆盖到目录中文件即可。
- 5、配置“支付配置.txt”文件内容：文件内的“##”为间隔符，倒数第二个参数是价格，可以随意修改，按需求修改即可，最后一个参数是支付回调地址，也是按需求修改。
- 6、双击启动exe。
- 7、此时，外网可以直接通过公网IP直接访问，内网的话通过路由器进行端口映射后即可访问。

# 代理销售个人版（免费）
- 无需有注册公司，每笔销售价格按固定百分比给系统分成，无法修改。
- [下载](https://github.com/dhrdzy/KnowledgePayment_Server/tree/main/测试体验)
