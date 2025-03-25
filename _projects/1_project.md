---
layout: page
title: Iris and Pupil Detection in Cataract Surgical Data
description: Object detection in cataract surgery images using YOLO to monitor intraoperative deviations.
img: assets/img/catarct_surgical_images.png
importance: 1
category: work
related_publications: true
---

## Iris and Pupil Detection in Cataract Surgical Data

This project focused on detecting the iris and pupil in cataract surgery images using deep learning techniques. The goal was to enable better intraoperative monitoring and support enhanced post-operative outcomes by precisely identifying these ocular features in real-time.

**Description:**  
Implemented YOLO object detection to identify iris and pupil in cataract surgery images for monitoring intraoperative deviations and optimizing post-operative outcomes.

**Tools & Technologies:**  
YOLO Object Detection (You Only Look Once)

**Outcome:**  
Achieved a Mean Average Precision (mAP) range of **0.75–0.80** across multiple datasets.

**GitHub Repository:**  
[YOLO Object Detection](#) _(replace this with the actual link)_

---

### Sample Images

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="Detected iris/pupil" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="Pre-op image example" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="YOLO detection output" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Left: Detected iris/pupil. Middle: Pre-op image example. Right: YOLO model output during surgery.
</div>

---

You can expand this section with more results, metrics, and visualizations if you want to show before/after comparisons or overlayed bounding boxes.

Let me know if you want help linking the GitHub repo or uploading images!
