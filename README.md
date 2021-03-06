# TIR_CAR
Dataset for for identify electric and fuel cars.

![图片1](https://user-images.githubusercontent.com/52853099/159113219-2e5a2b4d-6015-4012-b637-b3d99978c3c1.png)
 
We made a dataset for identify electric and fuel cars, we found that electric cars differ in thermal infrared images from fuel cars, based on this we can distinguish them, so we made this dataset.

<img width="418" alt="figure2" src="https://user-images.githubusercontent.com/52853099/159114072-40eb8146-867c-4fc5-a47b-b9a04597cc07.png">

The labeling method shown in the figure is used: the entire body and the rear heat flow are completely included, and additional space is reserved at the rear of the electric cars.
![figure5](https://user-images.githubusercontent.com/52853099/159113535-97778673-8c3b-4f80-b064-e7e46a8e182d.png)

For hybrid cars, determine which category they belong to based on the type of drive system when they are imaged. The picture below is a hybrid car, which is labeled as a fuel car.

<img width="419" alt="figure6" src="https://user-images.githubusercontent.com/52853099/159114078-134fcbe7-959d-4367-9af9-cfe537e995cc.png">

The dataset contains more than 3000 images, about 7000 fuel cars and 3500 electric cars.

<img width="588" alt="figure9" src="https://user-images.githubusercontent.com/52853099/159114010-1112d416-8670-47c0-8fb7-d48f6aca145e.png">

Experiment result is shown below, trained using YOLOv5.
![figure12](https://user-images.githubusercontent.com/52853099/159113805-2524a150-d162-4178-88cf-af9ff64575c2.png)

The dataset is avaliable from Google drive:https://drive.google.com/drive/folders/1S2VLrD8l39EkPtZNuhxCkTn_qFm_QteK?usp=sharing

The paper is avaliable in:https://www.tandfonline.com/eprint/6WYC4NUMXC28HXC5RIXJ/full?target=10.1080/01431161.2021.1978586

Contact: zhang_yj@whu.edu.cn
