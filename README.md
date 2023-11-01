适用于管理 115 离线下载的 Telegram Bot

## 运行

补全脚本中的相关字段

执行 `python3 115bot.py`

## 反向代理

填写 Caddyfile 执行 `caddy start` 命令开启反向代理

注意 Telegram 的 webhook 只支持下列端口: 443, 80, 88 8443

## 常见问题

Q: 设置好了机器人没反应

A: 访问 [getWebhookInfo](https://api.telegram.org/bot%7Bmy_bot_token%7D/getWebhookInfo) 查看是否成功设置 webhook


Q: cookie 失效

A: 使用手机客户端抓取的 cookie，如果使用 alist，最好和 alist 部署在同一台服务器上
