# Head detection during swimming races

This repositery gathers the python code and notebooks developed for the automatic detection of swimmers' heads.

## Notebooks

- training_notebook.ipynb to train Faster-RCNN on a custom dataset to detect swimmers head
- testing_notebook.ipynb to load a trained model and use it on images and videos

## .py required by Pytorch's FasterRCNN implementation 

- coco_eval.py
- coco_utils.py
- engine.py
- group_by_aspect_ratio.py
- presets.py
- train.py
- transforms.py
- utils.py

## Links to the dataset (images) and a trained model (dictionary containing the weights)

- Dataset : https://drive.google.com/file/d/1mHYiKxzKvSQb6jehLzeEJIQcM8rCd8bA/view?usp=sharing
- Model : https://drive.google.com/file/d/1brH4g-vgXZAH-ajark3xgX2iR9xmhXds/view?usp=sharing
