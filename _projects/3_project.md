---
layout: page
title: Exploring Uncharted Chemical Space using GNN
description: Predict MS/MS data 
img: assets/img/491graphdef.PNG
# redirect: https://unsplash.com
importance: 1
category: robotics
---

The model lives within our client’s GPU server which acts as the machine where we
perform training. The data preprocessing pipeline will transform the NIST2020 and
GNPS datasets through four stages: graph creation, graph splitting, dimensionality
reduction, and feature engineering. The output of this pipeline is a graph structure
compatible with GNN training models and methods. Finally, the product provides a
training pipeline to train and evaluate the performance of the GNN model.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/491pipeline.PNG" title="Pipeline" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The data pipeline is responsible for taking in a dataset of molecules (including their
structural and MS/MS data) and doing a series of transformations on this data to
create a graph. This figure describes the data filtering and processing processes applied.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/491poster_00.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

