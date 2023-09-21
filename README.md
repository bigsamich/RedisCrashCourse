# RedisCrashCourse

#Setup Redis and Redis Insight Instructions


docker pull redis

docker pull redislabs/redisinsight

docker run -d --name redis -p 6379:6379  redis:latest

docker run -d --name redis-insight --network host redislabs/redisinsight

Open a web browser and navigate to 127.0.0.1:8001
