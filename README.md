# Shopee_Product_Detection
Problem from shopee code league 2019

![image](https://user-images.githubusercontent.com/62899961/120929170-2f30d400-c712-11eb-8b81-67781029f0be.png)


#### Statement : Background

At Shopee, we always strive to ensure the correct listing and categorization of products. For example due to the recent pandemic situation, face masks become extremely popular for both buyers and sellers, everyday we need to categorize and update a huge number of masks items. A robust product detection system will significantly improve the listing and categorization efficiency. But in the industrial field the data is always much more complicated and there exists mis-labelled images, complex background images and low resolution images, etc. The noisy and imbalanced data and multiple categories make this problem still challenging in the modern computer vision field.

#### Task :

In this competition, a multiple image classification model needs to be built. There are ~100k images within 42 different categories, including essential medical tools like masks, protective suits and thermometers, home & living products like air-conditioner and fashion products like T-shirts, rings, etc. For the data security purpose the category names will be desensitized. The evaluation metrics is top-1 accuracy.

#### DATASETS LINK : https://www.kaggle.com/c/shopee-product-detection-open

### Result :

1st try -> LeNet5 Model ------------------------> training acc = 0.3 

2nd try -> EfficientNetB7 ----------------------> training acc = 0.7

3rd try -> Bilinear Using EfficientNetB7 -------> training acc = 0.8 ----> test acc = 0.79 
