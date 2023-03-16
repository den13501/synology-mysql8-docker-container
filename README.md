# mysql8-docker-container

## MySQL容器設置

```console
# 範例為mysql8容器目錄位於/volume1/docker/mysql8，若沒有請先進DSM創好目錄

# 下載zip檔，複製到/volume1/docker/mysql8下，然後原地解壓縮
![image](https://user-images.githubusercontent.com/58270741/225689859-9e2da996-3938-49d6-8a67-d800cff5cb00.png)

# 創建並啟動 MySQL8.0 容器
方式一: docker-compose up --build -d
方式二: 透過portainer->add stack，將docker-compose.yml內容貼到編輯區內

# 容器起動
方式一: docker-compose ps
方式二: portainer上個步驟deploy the stack啟動，會需要幾分鐘時間將mysql8容器創建並初始化

# DB初始化
$ bash ./init-mysql.sh
```
