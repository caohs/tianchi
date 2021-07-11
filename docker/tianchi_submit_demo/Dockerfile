# Base Images
## 从本地基础镜像构建
FROM registry.cn-shanghai.aliyuncs.com/caohs/python:3-cv2

## 把当前文件夹里的文件加载到构建的镜像的根目录下
ADD . /

## 指定默认工作目录为根目录
WORKDIR /

## 镜像启动后统一执行 sh run.sh
CMD ["sh", "run.sh"]
