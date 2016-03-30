build:
	docker build -t myapp .

run:
	docker run --name nodeapp -p 3000:3000 -dit myapp node /src/bin/www

stop:
	docker stop nodeapp
	docker rm nodeapp


