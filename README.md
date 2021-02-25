# eck-arm64
Elastic ECK deployment files for arm64 

## Description

Files used on the process of installing Elasticsearch ECK on Kubernetes **arm64** architecture.

The process description is in my personal blog on [https://seriousman.org/linux/elasticsearch/k8s/rpi/2021/02/16/elastic_eck_arm64/](https://seriousman.org/linux/elasticsearch/k8s/rpi/2021/02/16/elastic_eck_arm64/)

## Files on this repo

* `all-in-one.yml` - compiled from **cloud-on-k8s** official repo for **arm64** architecture
* `deploys/*yml` - files for deploying elasticseach nodes on k8s cluster based on the blog post
* `StorageClass/eck-nfs-storageclass.yml` - NFS storageClass definitions complatible with **cloud-on-k8s**

Have fun!

