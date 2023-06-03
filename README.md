# Knife detection with YOLOv5m

This is a YOLOv5 fork repo finetuned with a custom dataset that includes 23285 images of knives.
It can detect a knife in person`s hands or just a separate knife anywhere on an image/video/CCTV.
However it shows only ~80 mAP50 score, it was trained on one T4 for only 26 epochs, and it is just a pet-project.

## Usage
#### 1. Clone the repo and install all dependencies
`!git clone https://github.com/chistotinsa/knife_detection_YOLOv5 \
!pip install -U -r knife_detection_YOLOv5/requirements.txt \
%cd /content/knife_detection_YOLOv5`


