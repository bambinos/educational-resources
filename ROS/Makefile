.PHONY: build run

run:
	docker run -p 8888:8888 -v $(PWD):/home/jovyan regression_story:latest 

build:
	docker build -t regression_story -f Dockerfile .
