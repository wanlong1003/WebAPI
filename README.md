# WebAPI

演示如何将一个 asp.net 打包为 docker 镜像并上传到 ghrc(GitHub Container Registry). 

代码提交到 master 后 action 打包 image 并 push 到 ghrc. 然后从 项目右侧的 Packages 中就可以看到打包好的镜像

然后通过下面的命令即可下载镜像
```bash
docker pull ghcr.io/wanlong1003/webapi:latest
```
