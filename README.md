# Crop Growth Stage Classification

<p align="center">
 <img src="https://github.com/a-jahani/CropGrowthStage/blob/master/demo.gif" width="300" height="400">
</p>

_______________
This project was completed for the [ATB Datathon](https://www.meetup.com/ATB-Transformation/events/258732806/) (Alberta's largest Datathon), with a team of 6. The goal of the competition was to solve problems impacting the lives of everyday Albertans, with potential for global impact. We created a computer vision classification model, using a deep neural network, to predict the growth stage for a given plant. This would help with herbicide application plannint, insect treatment and fungicide decisions, while allowing large scale farms to accelerate their decision making process. The aim was to then integrate this with a crop phenology model to validate the model's predictions.


Full Demo: https://www.youtube.com/watch?v=G6xBIVzubFk

Presentation: [Crop growth stage modeling and classification](https://drive.google.com/open?id=1P9jtOcwQjw0ygOf0gAYlQiGhG2rSv2cO)

Project Blog:
https://www.linkedin.com/pulse/computer-vision-technology-project-recognized-finalist-kurrant/
__________________
## Dataset
Download the [Aberystwyth Leaf Evaluation Dataset](https://zenodo.org/record/168158#.XKJz2kCYU_U) 
```
wget https://zenodo.org/record/168158/files/images_and_annotations.zip?download=1
unzip images_and_annotations.zip
```
**Note:** Dataset size is 61GB before extraction.

Preprocess the data and decide the growth stage split:
```
python preProcess.py
```

## Training 
We used tensorflow 1.12. To train run the following code:
```
python train.py
```


## Trained Model
[Trained Model](https://drive.google.com/open?id=1p2uP6Fic2GLnswXfaMa9xJZZKYb_eiHX)

________________
