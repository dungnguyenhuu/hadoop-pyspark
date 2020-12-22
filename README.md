# hadoop-pyspark
cài đặt môi trường hadoop và pyspark
- mở terminal có chứa file docker-compose.yml
- gõ lệnh: docker-compose up
- truy cập địa chỉ localhost:8888 trên trình duyệt
- để có địa chỉ ip của spark-master gõ trong terminal: docker inspect -f "{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}" spark-master

