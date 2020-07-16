# Saliency-bounding-box 
We design a novel form of supervision for weakly supervision, namely saliency bounding boxes (SBBs). Each saliency bounding box covers a saliency region and follows the following labeling rules: 

• A saliency bounding box is a rectangular box that contains at least one salient object. 

• When an image has multiple salient regions, there should be no overlap between any two bounding boxes. 

Two overlapped bounding boxes would be merged into one saliency bounding box that encloses these two boxes. 
As shown in Figure 3, we divide the annotations of the dataset into 3 cases: (a) a single box with a single object, (b) a single box with multiple objects, (c) multiple boxes. Please note that our annotations are different from those used in existing object detection datasets, where one bounding box is assigned to one speciﬁc object. According to the above rules, one saliency bounding box may include multipleobjects.Foreground pixels only appear inside saliency bounding boxes, while the pixels outside saliency bounding boxes belong to the background.

 ![image](https://github.com/liuyuxuanlyx/Saliency-bounding-box/blob/master/image.png)


This paper is in peer review in IEEE TRANSACTIONS ON IMAGE PROCESSING. 
