# Object Detection with YOLOv8 and Faster RCNN

This Github repository presents an evaluation of two state-of-the-art pre-trained object detection models, Faster RCNN and YOLOv8, on a custom dataset of toy venom model and coffee cup. The models were not implemented from scratch, but rather were used as pre-trained models for detecting new objects.

The repository includes evaluation metrics such as Average Precision (AP) for both models, along with their inference times. Faster RCNN achieved an AP of 0.662 with an inference time of 0.01s, while YOLOv8 achieved an AP of 0.834 with an inference time of 0.074s. The evaluation results reveal that YOLOv8 performed better in detecting small objects located at the background, while Faster RCNN was more confident in detecting objects with approximately 100% probability for each object's bounding box.

Moreover, the repository provides an efficient way to evaluate pre-trained models on custom datasets for object detection tasks. The code includes data pre-processing, model evaluation, and visualization scripts. It also allows users to fine-tune the pre-trained models on their own datasets with minimal modifications to the code.

## Running the code

The code has been run in Google Colab environment. All additional libraries are installed using `pip`. You may find an original Google Colab notebook [here](https://colab.research.google.com/drive/1yJTjVd6tjFb_hbw0rPPCQkDn9JU0V3I4?usp=sharing)