This Project was to validate claims made by Paper:
 [2015 ICML] [Show, Attend and Tell] Show, Attend and Tell: Neural Image Caption Generation with Visual Attention

In this paper, an attention-based methodology for automatically creating captions for images is described. The model has an attention
mechanism that enables it to concentrate on important aspects of the image and provide captions that are more in-depth and comprehensive.
By obtaining cutting-edge performance on three benchmark datasets—Flickr8k, Flickr30k, and MS COCO—the authors show the model's
effi cacy. Additionally, they demonstrate that the model is capable of automatically learning to fix its gaze on important items as it produces the
matching words in the output sequence, underlining the potential benefi t of attention visualization for readability.

We validated following claims:
Claim 1:
The author makes a claim that the attention component can attend or focus on "non object" salient regions. The phrasing of the claim from the
author hints that other models which use object detection might not be able to pick this detail.
Claim 2:
The author admits the shortcomings with the model but further states that the mistakes made by the model could be exploited by visualization
as to get an intuition into why the model might be predicting what it is predicting.
