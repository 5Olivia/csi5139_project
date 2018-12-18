# csi5139_project
  
  This is the implementation for CSI5139 course porject.  
  
  The original code of Mask R-CNN referenced is on the https://github.com/matterport/Mask_RCNN and the PASCAL VOC 2007 dataset used in this project was downloaded by the following commands:wget http://host.robots.ox.ac.uk/pascal/VOC/voc2007/VOCtrainval_06-Nov-2007.tar
wget http://host.robots.ox.ac.uk/pascal/VOC/voc2007/VOCtest_06-Nov-2007.tar
wget http://host.robots.ox.ac.uk/pascal/VOC/voc2007/VOCdevkit_08-Jun-2007.tar
  
The repository includes:
**train_pascal.ipynb**: Pascal dataset preparation, training code, detection code and evaluation.
  
**pascal folder**: Consisting of the two subfolders, one for data used for training and testing, and another one for weights learned by our model. 
  
**mask_rcnn_coco.h5**: Inital weights trained on MS coco dataset, which we used to initalize the mask r-cnn model.  
  
Other modules in the original Mask R-CNN reference code needed to import are not upload to this repository. 
