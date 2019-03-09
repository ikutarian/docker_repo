# 以 ubuntu:16.04 为基础镜像
FROM ubuntu:16.04

# 备份原有的源
RUN cp /etc/apt/sources.list /etc/apt/sources.list.bak

# 替换成阿里源，更新源
RUN sed -i 's/archive.ubuntu.com/mirrors.aliyun.com/g' /etc/apt/sources.list \
    && apt-get update