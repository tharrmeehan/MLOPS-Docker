
# MLOPS-Docker

In this project, we containerize a python application with its own environment and packages. We will then train a huggingface model on it.

## Getting Started

### Prerequisities
In order to run this container you'll need docker installed.

* [Windows](https://docs.docker.com/windows/started)
* [OS X](https://docs.docker.com/mac/started/)
* [Linux](https://docs.docker.com/linux/started/)

### Cloning the Repo
When cloning the repo, you'll see 3 folders. The folder titled 'Task 2' is the one, which contains the docker container we are going to build and run.
To clone the repo

```shell
git clone https://github.com/tharrmeehan/MLOPS-Docker.git
```

then cd into our target directory
```shell
cd '.\Task 2\'
```
### Usage

To build and run the docker container, we are going to run the following commands inside the Task 2 folder

```shell
docker build -t mlops-docker .
```
You can rename the mlops-docker name, if you'd like.
Then run it directly using the following command

```shell
docker run mlops-docker
```
The output should be visible to you after some time. You can added your logger into the .py file, if you'd like and you can change the hyperparameters in the dockerfile, if you'd like aswell.

## Authors

* **Tharrmeehan Krishnathasan** - *Author*

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
