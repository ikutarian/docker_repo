# 以 ubuntu:16.04 为基础镜像
FROM ubuntu:16.04

# 备份原有的源
RUN mv /etc/apt/sources.list /etc/apt/sources.list.bak

# 复制阿里源
COPY sources.list /etc/apt/sources.list

# 更新源
RUN apt-get update