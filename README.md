

环境变量： CONFIG_JSON（配置）、


用notepad++将上述变量中 \r\n 替换为\\n，变成一行，导入容器。

客户端： android Actinium、windows v2ray 可用同一个服务端。

CONFIG_JSON配置文件

{ "log": { "loglevel": "warning" }, "inbound": { "protocol": "vmess", "port": 8080, "settings": { "clients": [ { "id": "uuid", "alterId": 233, "security": "aes-128-gcm" } ] }, "streamSettings": { "network": "ws" } }, "inboundDetour": [], "outbound": { "protocol": "freedom", "settings": {} } }

PC端配置： 端口443 底层传输安全tls
