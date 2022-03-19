# TIR_CAR
Dataset for for identify electric and fuel cars.

![图片1](https://user-images.githubusercontent.com/52853099/159113219-2e5a2b4d-6015-4012-b637-b3d99978c3c1.png)
 
We made a dataset for identify electric and fuel cars, we found that electric cars differ in thermal infrared images from fuel cars, based on this we can distinguish them, so we made this dataset.
![figure2](https://user-images.githubusercontent.com/52853099/159113483-9f854fbd-c301-4bf4-afb2-a94808a3433f.png)

The labeling method shown in the figure is used: the entire body and the rear heat flow are completely included, and additional space is reserved at the rear of the electric cars.
![figure5](https://user-images.githubusercontent.com/52853099/159113535-97778673-8c3b-4f80-b064-e7e46a8e182d.png)

For hybrid cars, determine which category they belong to based on the type of drive system when they are imaged. The picture below is a hybrid car, which is labeled as a fuel car.
![figure6](https://user-images.githubusercontent.com/52853099/159113573-398f64f0-99a9-4c23-a60e-c537b6c66c35.png)

The dataset contains more than 3000 images, about 7000 fuel cars and 3500 electric cars.
![figure9](https://user-images.githubusercontent.com/52853099/159113675-bf4b9000-7fd9-4cd1-abc0-8c63be5caa58.png)

Experiment result is shown below, trained using YOLOv5.
![figure12](https://user-images.githubusercontent.com/52853099/159113805-2524a150-d162-4178-88cf-af9ff64575c2.png)

The dataset is avaliable from Google drive:https://drive.google.com/drive/folders/1S2VLrD8l39EkPtZNuhxCkTn_qFm_QteK?usp=sharing
