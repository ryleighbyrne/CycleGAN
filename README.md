# CycleGAN
Domain-Cycling: An Exploration into Unpaired Image-To-Image Domain Mapping

Significant prior research has been done in the image-processing field of “style-transfer.”  Most popularly, style-transfer has been utilized to transform the style in which various pieces of artwork are drawn into a completely different style by that of a different author.  This phenomenon can be extended to the act of isolating key objects in images and videos and transforming such objects from their original domain-style to an entirely new domain (ex. zebras transformed into horses).  We seek to generalize this approach and utilize Cycle-Consistent Adversarial Networks to perform unpaired image-to-image domain mapping.  

Utilizing this CycleGAN deep-learning model, we seek to process various example images whose output following input to the deep-learning model contain features that were mapped from an original domain to a new domain.  For the purposes of discussion, we will refer to untransformed images as Class A images and transformed images as Class B images. 

<img width="178" alt="Screen Shot 2023-08-02 at 3 04 38 PM" src="https://github.com/ryleighbyrne/CycleGAN/assets/62968936/2a3b7592-792f-4d23-bd61-37b5bda4f544">

Following this, we seek to compare the performance of various image-processing techniques upon the Class A images as well as their corresponding Class B images.  For the purposes of discussion, we will refer to the post image-processing-technique Class A images as Class A’ and similarly refer to the post image-processing-technique Class B images as Class B’.  Finally, the Class A’ images will be compared to their corresponding Class B’ images in quantitative or qualitative ways, depending on the image-processing technique utilized (where A’ serves as the “ground-truth” for B’). 

<img width="318" alt="Screen Shot 2023-08-02 at 3 04 45 PM" src="https://github.com/ryleighbyrne/CycleGAN/assets/62968936/0fd6a6fd-70f1-4bca-94a4-d26d052027e8">

This project was completed for the course ECE 588 at Duke University (Fall 2022). 

Final project report with results and findings can be found in 'Final Report.pdf' 

CycleGAN model and code can be found in CycleGAN.ipynb
