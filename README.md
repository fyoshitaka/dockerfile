# コマンド

コンテナ起動  
docker-compose up -d

ボリュームの確認  
docker volume ls  
  
コンテナ削除後、ボリュームを削除する。  

ボリュームの削除  
docker volume rm ボリューム名

ボリュームの全削除  
docker volume rm $(docker volume ls -qf dangling=true)
