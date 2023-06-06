# docker


## 以下是一些常用的 Docker 指令：

1. docker run：运行一个容器，例如 docker run -it ubuntu bash 可以在一个 Ubuntu 容器中运行 Bash 终端。

2. docker ps：列出正在运行的容器，例如 docker ps 可以列出所有正在运行的容器。

3. docker images：列出本地的镜像，例如 docker images 可以列出本地所有的镜像。

4. docker build：构建一个镜像，例如 docker build -t my-image . 可以在当前目录下构建一个名为 my-image 的镜像。

5. docker push：将一个镜像推送到 Docker Hub 或其他镜像仓库，例如 docker push my-image 可以将名为 my-image 的镜像推送到 Docker Hub。

6. docker pull：从 Docker Hub 或其他镜像仓库拉取一个镜像，例如 docker pull ubuntu 可以拉取最新的 Ubuntu 镜像。

7. docker stop：停止一个正在运行的容器，例如 docker stop my-container 可以停止名为 my-container 的容器。

8. docker rm：删除一个容器，例如 docker rm my-container 可以删除名为 my-container 的容器。

9. docker rmi：删除一个镜像，例如 docker rmi my-image 可以删除名为 my-image 的镜像。

10. docker exec：在一个正在运行的容器中执行命令，例如 docker exec -it my-container bash 可以在名为 my-container 的容器中运行 Bash 终端。

以上是一些常用的 Docker 指令，可以帮助你管理容器和镜像。需要注意的是，Docker 指令非常丰富，可以根据实际需求进行选择和使用。