# Fasri Digit Detection

In this project a research has been done on detection of farsi digits using Yolov5 network.
I prepared 3 datasets and exmined the network in all three of them.

## Custom Dataset1
A dataset of images taken from digits listed on books and food products and clock images available on the Internet.

![1](https://user-images.githubusercontent.com/52583295/138284255-5c9630ec-e3dd-4b3a-9dc5-50db05586db4.JPG)

This database has a great diversity in terms of color, backgrounds, shapes of numbers, fonts and intensity, which makes it not desirable for detecting. you can see results, notebook that is required for training and models in [custom-dataset1 directory](./custom-dataset1).

## Custom Dataset2 
A dataset of images of tag whith farsi digits which is available on the Internet.

![Capture](https://user-images.githubusercontent.com/52583295/138286933-c9ff76e5-463a-4bc4-a216-c10922fa7e5f.JPG)

Due to the limited images of this dataset in a specific context and the homogeneity of the frames, better results are seen than the previous database. you can see results, notebook that is required for training and models in [custom-dataset2 directory](./custom-dataset2).

## Hoda Dataset
A new dataset is generated from the [Hoda Farsi handwritten digits dataset](https://farsiocr.ir/%d9%85%d8%ac%d9%85%d9%88%d8%b9%d9%87-%d8%af%d8%a7%d8%af%d9%87/%d9%85%d8%ac%d9%85%d9%88%d8%b9%d9%87-%d8%a7%d8%b1%d9%82%d8%a7%d9%85-%d8%af%d8%b3%d8%aa%d9%86%d9%88%db%8c%d8%b3-%d9%87%d8%af%db%8c/) with the help of Python files in [hoda-detection-generator directory](./hoda-detection-generator) to perform the detection operation. You just need to run generate_data.py.

![2](https://user-images.githubusercontent.com/52583295/138288788-b977d43c-d81f-481e-abc4-92f82b130773.JPG)

Due to the homogeneity of the images in this dataset and the high quality of the frames, very good results can be seen for digit detection on the images in this data set. you can see results, notebook that is required for training and models in [hoda-dataset directory](./hoda-dataset).

## Required files and results
Use the notebook in [notebook directory](./notebook) to perform preprocessing and augmentation operations, as well as to splitting the dataset into train, test and validation sets.
You can find all the required files including models and datasets as well as the final results including diagrams and detected images in [this drive](https://drive.google.com/drive/folders/1ka5e9wZ_Am-MQSgfSzSUAO7xrNG-ymjU?usp=sharing).
