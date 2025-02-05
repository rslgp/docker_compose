TEST_DIR = test

setup:
	mkdir -p redis-data
	chmod 700 redis-data
	make run
run:
	docker compose up -d
stop:
	docker compose down
delete:
	docker stop my_redis
	docker rm my_redis
