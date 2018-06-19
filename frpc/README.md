# frpc
[frp](https://github.com/qinmenghua/frp-docker-images) client for Qnap x86 linux.

A fast reverse proxy to help you expose a local server behind a NAT or firewall to the internet.


# Run
``` sh
docker run -d --name frpc --restart=always -v /path/to/frpc.ini:/home/frpc.ini qinmenghua/frpc
```

Qnap x86机型使用时请映射本地配置文件夹为/home，不适用于ARM机型。
