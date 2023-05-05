# openai-api-proxy
安全的openai api代理,移除可能泄漏真实IP的header信息
```
// 加载镜像
docker build -t openai-api-proxy .

//创建容器
docker run -p 5440:8080 openai-api-proxy 

//后台运行(由于是本机代理,所以直接监听8080的端口)
docker run --name openai-api-proxy -d -p 5440:8080 openai-api-proxy

//删除容器(-f 强制)
docker rm -f openai-api-proxy 

//删除镜像
docker rmi -f openai-api-proxy 


```
