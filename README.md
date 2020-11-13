# コマンド

プロジェクト内のコンテナ起動  
docker-compose up -d  

実行中コンテナの中でコマンド実行  
docker-compose exec [コンテナID or コンテナ名] [コンテナ内で実行するコマンド]

ボリュームの確認  
docker volume ls    

コンテナ削除後、ボリュームを削除する。  

ボリュームの削除  
docker volume rm [ボリューム名]

ボリュームの全削除  
docker volume rm $(docker volume ls -qf dangling=true)
