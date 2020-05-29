# FR_home_monitoring_system



    python3 extract_embeddings.py --dataset dataset --embeddings output/embeddings.pickle --detector face_detection_model --embedding-model openface_nn4.small2.v1.t7
    
    python3 train_model.py --embeddings output/embeddings.pickle --recognizer output/recognizer.pickle --le output/le.pickle
    
    python3 recognize_video.py --detector face_detection_model/ --embedding-model openface_nn4.small2.v1.t7 --recognizer output/recognizer.pickle --le output/le.pickle
    
## Directory tree
```txt

├── dataset
│   ├── Person1imgDirectory
│   ├── Person2imgDirectory
│   ├── Person3imgDirectory
│   ├── Person4imgDirectory
├── extract_embeddings.py
├── face_detection_model
│   ├── deploy.prototxt
│   └── res10_300x300_ssd_iter_140000.caffemodel
├── images
│   ├── img1.jpg
│   ├── img2.jpg
│   ├── img3.jpg
├── openface_nn4.small2.v1.t7
├── output
│   ├── embeddings.pickle
│   ├── le.pickle
│   └── recognizer.pickle
├── README.md
├── recognize.py
├── recognize_video.py
└── train_model.py
```

## Requirements V_2020.05.1
* Face reconginition


## Resources
* Dell Laptop Linux 18.04 LTS, 3GB ram, 500 GB hard drive, i3 processor
* 2 Mp camera

## Tasks
* Install python 3.7, PIP, open CV, openface, 



Ref: https://www.pyimagesearch.com/2018/09/24/opencv-face-recognition/
