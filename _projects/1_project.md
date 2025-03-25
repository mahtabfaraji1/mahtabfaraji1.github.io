---
layout: page
title: Iris and Pupil Detection in Cataract Surgical Data
description: Object detection in cataract surgery images using YOLOv5 to monitor intraoperative deviations.
img: assets/img/sample_image_ctaract101.png
importance: 1
category: work
related_publications: true
---

## Iris and Pupil Detection in Cataract Surgical Data

This project focused on detecting the iris and pupil in cataract surgery images using deep learning techniques. The goal was to enable better intraoperative monitoring and support enhanced post-operative outcomes by precisely identifying these ocular features in real-time.

**Description:**  
Implemented YOLOv5 object detection to identify iris and pupil in cataract surgery images for monitoring intraoperative deviations and optimizing post-operative outcomes.

**Tools & Technologies:**  
YOLOv5 Object Detection (You Only Look Once)

**Outcome:**  
Achieved a Mean Average Precision (mAP) range of **0.75–0.80** across multiple datasets.

**GitHub Repository:**  
[YOLO Object Detection](https://github.com/mahtabfaraji1/yolov5)

---

### Sample Images

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sample_image_ctaract101.png" title="Sample images from Catarct 101 dataset" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/GT_sample_public_catarct.png" title="Ground-truth bounding boxes" class="img-fluid rounded z-depth-1" %}
    </div>
 <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/YOLOv5_result.png" title="YOLOv5 model output" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Left: Sample images from Catarct 101 dataset. Middle: Ground-truth bounding boxes. Right: YOLOv5 model output.
</div>

---
