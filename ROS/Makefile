.PHONY: build run

run:
	docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v $(PWD):/home/jovyan regression_story:latest 

build:
	docker build -t regression_story -f Dockerfile .
