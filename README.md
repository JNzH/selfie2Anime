# Selfie2Anime


### 项目参考代码
tensorflow1.14版 `https://github.com/taki0112/UGATIT`  
pytorch版 `https://github.com/znxlwm/UGATIT-pytorch`

### 环境要求
* python == 3.6
* tensorflow == 1.14

### 数据集
[Google Drive](https://drive.google.com/file/d/1xOWj1UVgp6NKMT3HbPhBbtq2A4EDkghF/view)

### 使用方法
```
├── dataset
   └── YOUR_DATASET_NAME
       ├── trainA
           ├── xxx.jpg (name, format doesn't matter)
           ├── yyy.png
           └── ...
       ├── trainB
           ├── zzz.jpg
           ├── www.png
           └── ...
       ├── testA
           ├── aaa.jpg 
           ├── bbb.png
           └── ...
       └── testB
           ├── ccc.jpg 
           ├── ddd.png
           └── ...
```

### 训练
```
> python main.py --dataset selfie2anime
```

### 测试
```
> python main.py --dataset selfie2anime --phase test
```
