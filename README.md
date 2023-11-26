# type_of_leaf_veins_classification
This is model to classified type of leaf veins. This model has 4 class, there are : 
    1. Melengkung: pepper leaves, betel leaves, hibiscus leaves
    2. Menjari: sun leaves, papaya leaves, cassava leaves
    3. Menyirip: mango leaves, guava leaves, orange leaves
    4. Sejajar: corn leaves, sugar cane leaves, rice leaves

This model has 2000 dataset which is split into train and test set. Training set has 1440 and 360 for test set. 
![Screenshot (277)](https://github.com/itatrilestari/type_of_leaf_veins_classification/assets/126906101/c48d1e0e-81ee-4c84-9441-247c7204904b)

The dataset collect from Kaggle and Roboflow. 
1. Menyirip
    Mango : 500 image
    https://www.kaggle.com/datasets/aryashah2k/mango-leaf-disease-dataset
    
    Guava : 50 image + 100 image
    https://www.kaggle.com/datasets/syaikhulanam/datasetsjenisdaun
    https://universe.roboflow.com/sipklpk-1tugas-1/deteksi-penyakit-daun-jambu-biji
    
    Orange : 747 image
    https://universe.roboflow.com/itera-tq5vn/deteksi-daun-jeruk-jcthw

2. Sejajar
    Corn : tidak full gambar
    https://github.com/ibnujakaria/dataset-daun-jagung
    
    Sugar Cane : 
    https://www.kaggle.com/datasets/pungliyavithika/sugarcane-leaf-disease-classification
    file di download
    
    Rice leaves : 3355 image
    https://www.kaggle.com/datasets/shayanriyaz/riceleafs

And i use InceptionResnetV2 as a base model because InceptionResNetV2 was trained on a large-scale image classification task, ImageNet, and achieved state-of-the-art performance. This pre-training on a diverse dataset helps the model to learn rich hierarchical features, which can be beneficial when fine-tuning for a specific classification task.
![Screenshot (278)](https://github.com/itatrilestari/type_of_leaf_veins_classification/assets/126906101/16359a45-2a9f-441c-a300-952b96d1ab4f)

The model has good accuracy and is stable at 99% with 10 epochs.
![Screenshot (279)](https://github.com/itatrilestari/type_of_leaf_veins_classification/assets/126906101/15fe6a52-871a-4629-8861-a6466da152eb)

As you can see in this plot of the training and test result.
![Uploading Screenshot (280).png…]()



