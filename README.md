# Google-AutoML


# Edge端容器部署教程    
https://cloud.google.com/vision/automl/docs/containers-gcs-tutorial   


## 导出模型


## 下载并运行docker
```
export CPU_DOCKER_GCR_PATH=gcr.io/cloud-devrel-public-resources/gcloud-container-1.14.0:latest

sudo docker pull ${CPU_DOCKER_GCR_PATH}

```



```
sudo docker run --rm --name ${CONTAINER_NAME} -p ${PORT}:8501 -v ${YOUR_MODEL_PATH}:/tmp/mounted_model/0001 -t ${CPU_DOCKER_GCR_PATH}

```







------------------

#  GPU


```
apt update &&  apt-get install build-essential -y
```
