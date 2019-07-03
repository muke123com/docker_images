# 基于的基础镜像
FROM python:3.7

# 代码添加到code文件夹
ADD ./EF_NFCS /code

# 设置code文件夹是工作目录
WORKDIR /code

# 安装支持
RUN pip install -r requirements.txt

# 当启动容器时候，执行server.py程序
CMD ["python", "/code/package/server.py"]