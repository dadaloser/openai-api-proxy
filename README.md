# openai-api-proxy
安全的openai api代理,移除可能泄漏真实IP的header信息
```
// 加载镜像
docker build -t openai-api-proxy .

//创建容器
docker run -p 5440:5440 openai-api-proxy 

//后台运行
docker run --name openai-api-proxy -d -p 5440:5440 openai-api-proxy
```
