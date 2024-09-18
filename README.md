# bark_shell
**简陋的 shell 脚本，使用 curl 推送到 Bark ios app，无需手动转换 url 编码**

应能在 dash，bash，zsh 上正常运行

### 必须安装的依赖

	curl, sed, jq, gawk, coreutils

### 可选安装的依赖

	jo

不安装只能使用 GET 方式推送，无法使用 POST 和推送加密（这个也用的 POST）

	openssl

不安装无法使用推送加密
