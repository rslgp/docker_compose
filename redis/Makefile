run:
	docker compose up -d
stop:
	docker compose down
delete:
	docker stop my_redis
	docker rm my_redis

list_keys_oncontainer:
	redis-cli KEYS "*"
	redis-cli DEL KEY
	redis-cli FLUSHALL

