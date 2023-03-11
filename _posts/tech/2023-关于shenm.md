####layout	title	category	tags	keywords
post
Docker 使用总结
工具
Docker
Docker
Docker 基本概念
镜像 Image
镜像是一些打包好的已有的环境，可以被用来启动和创建容器，本身不能被直接修改。

容器 Container
容器是镜像的实例化，是可以修改的，但是都是临时修改。

容器启动过程
检查本地是否存在指定的镜像，不存在就从公有仓库下载
利用镜像创建并启动一个
