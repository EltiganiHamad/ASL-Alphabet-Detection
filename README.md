# Fine-Tuning Deep Learning Models for American Sign Language Alphabet Detection

This project delves into the domain of computer vision and human-computer interaction by exploring the fine-tuning of three prominent deep learning object detection models for the task of American Sign Language (ASL) alphabet recognition. The models under investigation include:

<ul>
<li><b>YOLO (You Only Look Once):</b> Renowned for its real-time inference speed, YOLO is a single-stage detector that excels in high-frame-rate applications.</li>
<li><b>Faster R-CNN (Region-Convolutional Neural Network):</b> A two-stage detector that offers a balance between speed and accuracy, often providing more precise bounding boxes compared to single-stage models.</li>
<li><b>SSD (Single Shot MultiBox Detector):</b> Another single-stage detector known for its speed and efficiency, making it suitable for resource-constrained scenarios.</li>
</ul>

### Objective:

The primary goal is to evaluate the performance of these pre-trained models when fine-tuned on an ASL alphabet dataset. The fine-tuning process aims to adapt the models' learned features from generic object detection tasks to effectively recognize the distinct visual characteristics of ASL hand signs representing individual letters.

### Dataset

The data set is a collection of images of alphabets from the American Sign Language, separated in 29 folders which represent the various classes.

<b>Link to Dataset:</b> https://public.roboflow.com/object-detection/american-sign-language-letters
