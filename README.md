# xray for CodeSandbox

在 CodeSandbox 部署 xray 节点

## 项目特点

* 本项目用于在 CodeSandbox 上部署 xray ，采用的方案为 Node.js + WebSocket + VMess/Vless/Trojan/Shadowsocks + TLS
* vmess 和 vless 的 uuid 或 trojan 和 shadowsocks 的密码，路径既可以自定义，又或者使用默认值
* 部署完成如发现不能上网，请检查域名是否被墙，可使用 Cloudflare CDN 或者 worker 解决。

## 步骤

* 注册 [CodeSandbox](https://codesandbox.io/)
* 进入首页，找到“Start from a template”，选择下面Node.js
* <img width="1154" alt="image" src="https://github.com/aikeji/Codesandbox/assets/37612638/c47b09f4-5157-4369-b19d-a35918916aa1">
* 创建成功之后，左边栏，把所有文件全部删除，包含.codesandbox文件夹也删除
* 下载项目文件到本地，
* 网页中，在左边栏，右键，选择“Upload files”，然后上传项目文件到项目中（除了LICENSE和README.md），我下面的图是已经运行过后项目自动添加了一些文件
* <img width="491" alt="image" src="https://github.com/aikeji/Codesandbox/assets/37612638/5fb650a7-cea1-4cbc-9cbf-00f66d9ee619">
* 点击左上角的正方形图标，然后点击“settings”
* <img width="389" alt="image" src="https://github.com/aikeji/Codesandbox/assets/37612638/1676f582-bee4-4b9c-86bd-8c668e1710ff">
* 转到“Env Variables”处，设置环境变量
* UUID，NEZHA_SERVER，NEZHA_PORT，NEZHA_KEY......
* <img width="1138" alt="image" src="https://github.com/aikeji/Codesandbox/assets/37612638/31e0d8f2-f5e4-4a1b-92b1-45d03082cdf5">
* 设置完成后，点击左上角的正方形图标，然后点击“Restart Sandbox”按钮
* <img width="390" alt="image" src="https://github.com/aikeji/Codesandbox/assets/37612638/d0866385-d577-4d37-b64b-b6afce869810">


