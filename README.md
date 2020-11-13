# コマンド



ボリュームの確認  
docker volume ls

ボリュームの削除  
docker volume rm ボリューム名

ボリュームの全削除  
docker volume rm $(docker volume ls -qf dangling=true)
