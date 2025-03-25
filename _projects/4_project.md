---
layout: page
title: Mid-diastole Frame Detection using Echocardiography Images
description: Applied image processing and ML algorithms to detect mid-diastole frames in echocardiography for mitral valve stenosis diagnosis.
img: assets/img/echocardiography.jpg
importance: 1
category: work
related_publications: false
---

## Mid-diastole Frame Detection using Echocardiography Images

This project aimed to assist in the diagnosis of mitral valve stenosis by detecting the mid-diastole frame in echocardiography image sequences. By combining classical image processing with machine learning techniques, the system automatically identifies the optimal frame for analysis.

**Description:**  
Applied image processing and machine learning algorithms to detect the mid-diastole frame in echocardiography images. The system supports diagnostic workflows by highlighting the most clinically relevant frame for measuring mitral valve area.

**Tools & Technologies:**  
MATLAB, K-Means Clustering, Circular Hough Transform

**Outcome:**  
Achieved an average frame difference of **1.40 frames** compared to expert-selected frames (gold standard by echocardiologists), showing strong agreement and clinical viability.

**Paper link:**  
[Novel approach for automatic mid-diastole frame detection in 2D echocardiography sequences for performing planimetry of the mitral valve orifice](https://digital-library.theiet.org/doi/full/10.1049/iet-ipr.2019.1757)

---

### System Overview

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/mid-diastole-paper-overview.png" title="Echocardiography Frame Detection Pipeline" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
Overview of the proposed automatic algorithm for the mid-diastole frame determination. CLC: centre of the largest circle
