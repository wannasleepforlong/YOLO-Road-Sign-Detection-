# YOLO-Vehicle-Detection
## Vehicle detection using YOLOv8 pretrained model on custom dataset.

Classification : Labelling of an object with no bounding box 

Localization : Classification of an object with bounding box

Detection : Locallizing multiple objects

In our model, we bound image with labels and send it in a convolutional net and softmax will give us the classification.

%y =        pc   does image have any object/ objectness score,
%	   bx   bounding box cordinates, 
%	   by  
%	   bz
%	   bw	
%	   c1   probability of class 1,
%	   c2   probability of class 2,
%	   c3   probaiblity of class 3,  


loss = (y1-yp1)^2 + (y2-yp2)^2 + ...

We do this in our feature map by Conv


![image](https://github.com/wannasleepforlong/YOLO-Vehicle-Detection/assets/109717763/67535fb1-4cc5-463e-a188-c4401baa20ac)

