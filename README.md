# openai-api-proxy
安全的openai api代理,移除可能泄漏真实IP的header信息
docker build -t openai-api-proxy .
docker run -p 8080:80 openai-api-proxy 
