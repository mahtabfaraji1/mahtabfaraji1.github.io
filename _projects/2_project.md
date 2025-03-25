---
layout: page
title: Classification of Surgeon Skill Level
description: Classifying surgeon skill levels from cataract surgical videos using using V-JEPA and LSTM Models.
img: assets/img/cataract_surgeon_skill_classification.png
importance: 1
category: work
related_publications: true
---

## Classification of Surgeon Skill Level using V-JEPA and LSTM Models

This project aimed to classify surgeon skill levels from cataract surgical videos using temporal modeling and feature extraction techniques. Leveraging the **Cataract101** dataset, we utilized both self-supervised learning and sequential models to learn meaningful patterns and predict expertise levels.

**Description:**  
Classified surgeon skill levels based on surgical videos. The project utilizes the Cataract101 dataset, leveraging both the V-JEPA model and an LSTM model with a ResNet-18 feature extractor.

**Tools & Technologies:**  
V-JEPA (Video Joint Embedding Predictive Architecture), LSTM, ResNet-18

**Outcome:**  
Achieved an accuracy of **83%** with LSTM and **93%** with V-JEPA models.

**GitHub Repository:**  
[V-JEPA: Video Joint Embedding Predictive Architecture](#)(https://github.com/monkeygobah/surgical_classification)

---

### Model architecture

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Vjepa.png.png" title="Vjepa model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
 A) V-JEPA and attention probe architecture. The open source encoder and predictor weights from Meta (Vit-L) were used, and an attention probe was fine tuned for surgical video skill level classification. B) LSTM network architecture used. The whole video was used as input with frameskip of 4, features were extracted from each frame using a ResNet-18 pretrained on ImageNet, 2 LSTM layers with a hidden size of 256 were then trained along with 2 fully connected layers to produce the final classification result.
</div>

---

You can explore the dataset and here:  
<a href="http://ftp.itec.aau.at/datasets/ovid/cat-101/" target="_blank">Cataract101 Dataset</a>

See <a href="https://docs.google.com/document/d/1uCtWCGGY4TMgrgtyK3U0uNzPn4oZ1f5jL-aDRxwgxaE/edit?usp=sharing">Project Report</a> for more details of this project
