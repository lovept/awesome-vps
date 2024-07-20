```bash
docker pull mysql

docker run --name mysql \
-e MYSQL_ROOT_PASSWORD=1234567890 \
-dp 3306:3306 \
mysql

docker exec -it mysql bash

mysql -uroot -p1234567890
```
![](1721060097527.png)