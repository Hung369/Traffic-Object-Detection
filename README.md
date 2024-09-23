# Traffic-Object-Detection
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1QzZ45lcXrT0UR1zTBwrCVoGOBN9TH058?usp=sharing)

Training a YOLOv8 model on traffic object dataset, so that it can detect objects participating in traffic.


## Dependencies

* Python 3.10 - 3.11 is needed
* Python IDE: Google Colab


## Dataset

For the training dataset, you can download it from [here](https://drive.google.com/drive/folders/1cN_cDove4POQnAzi8BB1n_-lWa7QKiFC?usp=sharing).

There are 2 folders in the zip file: **dataset** and **addition**, and these 2 folders are used for the training.
Meanwhile, test_video_1 and test_video_2 are 2 testcase videos for inference by the trained model.

## Deployment

To deploy this project, please do these following steps:

1. Upload and extract the given dataset on your own drive.
2. Mount the colab code to drive and adjust the path to **dataset** and **addition** if needed.
3. Run all cells in GPU runtype environment.
4. The output1.mp4 and output2.mp4 are the inference results, you can download it after running all notebook cells.



## Demo

Insert gif or link to demo


## Related

Here are some related projects

[Awesome README](https://github.com/matiassingers/awesome-readme)
