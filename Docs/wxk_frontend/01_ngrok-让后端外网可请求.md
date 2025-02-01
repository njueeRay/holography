

### 内网穿透ngrok

#### 原理

ngrok相当于作为中间代理把我们的端口暴露到外面

ngrok有一些配套的安全配置（之后如果需要



#### 安装

按照ngrok官网linux版安装 [Setup - ngrok](https://dashboard.ngrok.com/get-started/setup/linux)

本来用的python SDK，但是不太方便修改配置，后换成linux应用版

```
...
sudo apt install ngrok
```

用了9898 kB



#### 查看配置文件

```
 vim /root/.config/ngrok/ngrok.yml
```

当前配置：backend端口8908，域名exact-relieved-yak.ngrok-free.app



#### 启动代理

在本机用fastapi 在localhost:8908 启动服务

```
/home/backend-test# python test.py
```

然后使用ngrok转发

```
ngrok start backend
```

访问[https://exact-relieved-yak.ngrok-free.app/](https://exact-relieved-yak.ngrok-free.app/) ，与访问 localhost:8908的内容一致。

浏览器可直接访问，或访问/docs ，可以看到所有的api信息
