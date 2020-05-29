# FR_home_monitoring_system

Ref: https://www.pyimagesearch.com/2018/09/24/opencv-face-recognition/


    python3 extract_embeddings.py --dataset dataset --embeddings output/embeddings.pickle --detector face_detection_model --embedding-model openface_nn4.small2.v1.t7
    
    python3 train_model.py --embeddings output/embeddings.pickle --recognizer output/recognizer.pickle --le output/le.pickle
    
    python3 recognize_video.py --detector face_detection_model/ --embedding-model openface_nn4.small2.v1.t7 --recognizer output/recognizer.pickle --le output/le.pickle
    
## Directory tree
...txt

[01;34m.[00m
├── commands.txt
├── [01;34mdataset[00m
│   ├── [01;34mName1[00m [30 entries]
│   ├── [01;34mName2[00m [87 entries]
│   ├── [01;34mName3[00m [50 entries]
│   ├── [01;34mName4[00m [31 entries]
├── extract_embeddings.py
├── [01;34mface_detection_model[00m
│   ├── deploy.prototxt
│   └── res10_300x300_ssd_iter_140000.caffemodel
├── [01;34mimages[00m
│   ├── [01;35mimg1.jpg[00m
│   ├── [01;35mimg2.jpg[00m
│   ├── [01;35mimg3.jpg[00m
├── openface_nn4.small2.v1.t7
├── [01;34moutput[00m
│   ├── embeddings.pickle
│   ├── le.pickle
│   └── recognizer.pickle
├── README.md
├── recognize.py
├── recognize_video.py
└── train_model.py
...

## Requirements V_2020.05.1
* Face reconginition


## Resources
* Dell Laptop Linux 18.04 LTS, 3GB ram, 500 GB hard drive, i3 processor
* 2 Mp camera

## Tasks
* Install python 3.7, PIP, open CV, openface, 
