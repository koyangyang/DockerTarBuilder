## 🤔 这是什么？
它是一个工作流。可快速构建指定架构/平台的单个或多个docker镜像 并存储在Artifact文件或Release文件

## 使用说明
- 如果你的docker镜像小于2GB 你可以使用红色框框这三种Release工作流<br> 
- 如果你的docker镜像大于2GB且小于5GB 你可以使用蓝色框框的这三种Artifact工作流<br>
- 如果你的docker镜像大于5GB 比如 `vllm/vllm-openai:v0.6.4.post1` 抱歉了 只能自己解决网络问题直接pull了 本项目爱莫能助啦！

```bash
# 1.解压
unzip docker-images-tar.zip

# 2.再解压：
tar -zxvf x86-64-images.tar.gz

# 3.导入
docker load -i alpine:latest-amd64.tar
```
