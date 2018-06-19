# frpc
[frp](https://github.com/qinmenghua/frp-docker-images) client for Qnap x86 linux.

A fast reverse proxy to help you expose a local server behind a NAT or firewall to the internet.

[![](https://images.microbadger.com/badges/image/leonismoe/frpc.svg)](https://microbadger.com/images/leonismoe/frpc "Get your own image badge on microbadger.com") [![](https://images.microbadger.com/badges/version/leonismoe/frpc.svg)](https://microbadger.com/images/leonismoe/frpc "Get your own version badge on microbadger.com")

# Run
``` sh
docker run -d --name frpc --restart=always -v /path/to/frpc.ini:/home/frpc.ini qinmenghua/frpc
```
