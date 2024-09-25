# Traffic-Object-Detection
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1QzZ45lcXrT0UR1zTBwrCVoGOBN9TH058?usp=sharing)

Training a YOLOv8 model on traffic object dataset, so that it can detect objects participating in traffic.


## Dependencies

* Python 3.10 - 3.11 is needed
* Python IDE: Google Colab


## Dataset

For the training dataset, you can download it from [here](https://drive.google.com/drive/folders/1cN_cDove4POQnAzi8BB1n_-lWa7QKiFC?usp=sharing).

There are 2 folders in the file: **dataset** and **addition**, and these 2 folders are used for the training.

Meanwhile, test_video_1 and test_video_2 are 2 testcase videos for inference by the trained model.

## Deployment

To deploy this project, please do these following steps:

1. Upload and extract the given dataset on your own drive.
2. Mount the colab code to drive and adjust the path to **dataset** and **addition** if needed.
3. Run all cells in GPU runtype environment.
4. The output1.mp4 and output2.mp4 are the inference results, you can download it after running all notebook cells.



## Demo

Here are some demo videos

First video:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/bkNN-X7U_o4/0.jpg)](https://www.youtube.com/watch?v=bkNN-X7U_o4)

Second video:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/PoGs9knxQOE/0.jpg)](https://youtu.be/PoGs9knxQOE)


## Related
* Dataset ref

``` yaml
@misc{
traffic-object-hgekc_dataset,
title = { traffic object Dataset },
type = { Open Source Dataset },
author = { university project },
howpublished = { \url{ https://universe.roboflow.com/university-project-zqrun/traffic-object-hgekc } },
url = { https://universe.roboflow.com/university-project-zqrun/traffic-object-hgekc },
journal = { Roboflow Universe },
publisher = { Roboflow },
year = { 2024 },
month = { mar },
note = { visited on 2024-09-23 },
}

@misc{
train_dataset-qoqeb_dataset,
title = { train_dataset Dataset },
type = { Open Source Dataset },
author = { Major Project },
howpublished = { \url{ https://universe.roboflow.com/major-project-qscuq/train_dataset-qoqeb } },
url = { https://universe.roboflow.com/major-project-qscuq/train_dataset-qoqeb },
journal = { Roboflow Universe },
publisher = { Roboflow },
year = { 2024 },
month = { sep },
note = { visited on 2024-09-23 },
}

@misc{
detection-ydrk9_dataset,
title = { Detection  Dataset },
type = { Open Source Dataset },
author = { saifullah },
howpublished = { \url{ https://universe.roboflow.com/saifullah/detection-ydrk9 } },
url = { https://universe.roboflow.com/saifullah/detection-ydrk9 },
journal = { Roboflow Universe },
publisher = { Roboflow },
year = { 2024 },
month = { aug },
note = { visited on 2024-09-23 },
}
```

* YOLOv8 [paper](https://arxiv.org/pdf/2305.09972) 
