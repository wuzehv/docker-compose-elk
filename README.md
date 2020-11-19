# docker compose for elk

### usage
1. `git clone https://github.com/wuzehv/docker-compose-elk.git`
2. `docker-compose up -d`
3. http://127.0.0.1:5601

### 备注
仅提供了最基本的测试环境，如果需要可以自行调整docker配置文件

logstash连接docker下的mysql，修改docker-compose.yml里面的网卡

logstash连接其他环境的mysql，修改logstash-mysql.conf连接

**elk对配置有一定要求，我的宿主机给docker分配了四核cpu，8G内存**