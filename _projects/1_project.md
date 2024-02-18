---
layout: page
title: Context-aware NMT using Selected Context
description: An offline context selection technique
img: assets/img/selected-context.jpg
importance: 1
category: work
related_publications: haq2022context
---

This work was presented at an international conference, The author proposed to use pre-trained models and context selection techniques to effectively encode the contextual information. The idea is to select the most significant context from existing data and encode contextual features using pre-trained models to have rich representation of context. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/selected-context.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of proposed approach. 
</div>

There can different context selection methodologies, we can have a number of previous sentences may have some relevant information about the topic and current sentence may have dependency on that. A current sentence that needs to be translated, a number of previous or next sentences can be selected as part of context. Our experiments suggest that considering more than 3 sentences as context may not improve the performance of system. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/results-selected.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The graphical illustration of results which indicate selected approaches ourperfromed fixed context baseline.  
</div>



