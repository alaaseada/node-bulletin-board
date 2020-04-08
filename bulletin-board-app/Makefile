lint:
	hadolint --ignore=DL3013 Dockerfile

build:
	docker build --tag bulletinboard:1.0 .
	
run:
	docker run --p 8000:8080 -d --name bb bulletinboard:1.0
		
all:  lint build run 
