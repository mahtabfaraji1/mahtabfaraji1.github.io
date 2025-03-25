---
layout: page
title: Converting Handwritten Mathematical Equations to LaTeX Code
description: Designed a system using image processing and CNNs to convert handwritten equations into LaTeX code.
img: assets/img/hand_written.png
importance: 1
category: work
related_publications: false
---

## Converting Handwritten Mathematical Equations to LaTeX Code

This project focuses on the conversion of handwritten mathematical equations into LaTeX code using computer vision and deep learning techniques. By training CNN models to recognize symbols, we developed a system capable of interpreting mathematical expressions and converting them into syntactically correct LaTeX.

**Description:**  
Designed a system using image processing techniques and CNN models to classify handwritten symbols—including digits, Latin/Greek letters, and mathematical operators—and convert them into corresponding LaTeX code.

**Tools & Technologies:**  
Convolutional Neural Networks (CNNs), Image Processing, Python

**Outcome:**  
Demonstrated the capability of CNN models in accurately detecting and classifying mathematical symbols for LaTeX generation.

**GitHub Repository:**  
[Converting Handwritten Mathematical Equations to LaTeX Code](https://github.com/mahtabfaraji1/ECE515_LaTeX-Code-for-Handwritten-Mathematical-Equations)

---

### System Overview

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/handwritten_pipeline.png" title="the block diagram of the proposed method" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
The system architecture involves preprocessing handwritten images, segmenting symbols, classifying them using CNN models, and converting the sequence into LaTeX format. The pipeline effectively handles a wide range of mathematical expressions.
</div>

---

See <a href="https://drive.google.com/file/d/15KwRvpKmPm-wco7Si_mQT2nIt8PLmRaK/view?usp=sharing" target="_blank">Project Report</a> for more technical details and evaluation.
