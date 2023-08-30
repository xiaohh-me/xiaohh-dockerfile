# 使用MySQL作为基础镜像
FROM mysql:5.7.43

# 作者名字
LABEL org.opencontainers.image.authors="XiaoHH <xiaohh@yueyang.city>"

# 复制sql脚本内容到容器当中
COPY ./sql/nacos-mysql.sql /docker-entrypoint-initdb.d
