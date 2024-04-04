# oneliners

### Docker 
// Выполняем команду на контенере с фильтром 
docker exec $(docker ps |awk '/test_container.1/ {print $1}') cat /etc/passwd
