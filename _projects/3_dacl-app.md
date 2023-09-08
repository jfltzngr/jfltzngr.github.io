---
layout: page
title: dacl-app
description: Android app for live image defect classification
img: 
importance: 3
category: work
giscus_comments: true
---

The dacl-app, which is the acronym for “damage classiﬁcation-application”, performs live image multi-target classiﬁcation of four reinforced concrete defects with two state-of-the-art CNNs. Live image classiﬁcation means that a speciﬁc amount of video frames of the live camera output is constantly fed into the deployed CNN. The model’s inference time depends on the hardware of the smartphone and the model’s architecture, mostly its number of parameters and the applied data types. Therefore, the app displays measurements to describe its computational performance. The dacl-app can be used to spontaneously test our models in the wild. In addtion, the results of our analysis show that real-time inference on state-of-the-art smartphones is possible.   

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/ScreenCast.mp4" title="ScreenCast dacl-app" class="img-fluid rounded z-depth-1" autoplay="True" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Thumbnail.jpg" title="Thumbnail dacl-app" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    dacl-app and a corresponding thumbnail during the classification of Spalling, Exposed Reinforcement and Corrosion.
</div>


