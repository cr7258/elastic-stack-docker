启动命令。
```bash
docker-compose up -d
```
浏览器输入： 
http://localhost:5061 访问 Kibana。
https://localhost:9200 访问 Elasticsearch，Elasticsearch 集群 TLS 加密。
用户名：elastic，密码：czw123456，可以在 *.env* 文件中进行设置。

停止命令。
```bash
docker-compose down
```
停止并删除持久卷。
```bash
docker-compose down -v
```

参考链接
- [Install Elasticsearch with Docker](https://www.elastic.co/guide/en/elasticsearch/reference/8.0/docker.html#docker-file)
