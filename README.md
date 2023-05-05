# openai-api-proxy
安全的openai api代理,移除可能泄漏真实IP的header信息
```
// 加载镜像
docker build -t openai-api-proxy .

//创建容器,容器端口80映射到主机端口8080
docker run -p 8080:80 openai-api-proxy 
```
