# BN_HTR
Line and Word segmentation for Bangla Handwritten Text Recognition using YOLO framework.<br/><br/>
**Trained Line and Word models using YOLOv5 >>**<br/>
Line Model (YOLOv5x6): https://drive.google.com/file/d/1ezo3rKEU1xNvGzwl63d2qz4hVKof7qmB/view?usp=sharing <br/>
Word Model (YOLOv5x6): https://drive.google.com/file/d/1-Y2e1l05e1inQIrmq5HubAh_Qq8Fkdik/view?usp=sharing <br/><br/>
**Code for BN-HTRd Dataset (Multiple (with) & Single images (without) output transitions) -> Necessary Links >>**<br/>
Splitted (Train-Val-Test) BN-HTRd dataset: https://drive.google.com/file/d/1rPgU-V7TOvyRPKuw_yuhGCohsHG5bJHB/view?usp=sharing<br/>
(**N.B.:** The *Code for BN-HTRd Dataset (Multiple images)* is used to segment all the test images & also to evaluate our system, on the other hand, the *Code for BN-HTRd dataset (Single Image output Transition)* is used to see how our system functions visually. However, in both the cases, we only need the images and their annotations/groundtruths provided here in the BN-HTRd Dataset's Test portion and the groundtruths are important to run the codes as both the codes are mainly designed for result comparison.)<br/><br/>
**Code for Automatic Annotation -> Necessary Links >>**<br/>
Dataset (Contains folders with Raw RGB images): https://drive.google.com/file/d/1yYvNFVyrh9nWuQAkTnRrDZa1GZ7gvvkc/view?usp=sharing<br/>
(**N.B.:** If you need to test with your own dataset, please download the dataset containing unannotated images provided in the link and set your dataset in that particular format)<br/><br/>

[*To generate output for any datasets with multiple images, GPU is highly recommended! But just to see the output transition for single image, GPU is not mandatory. Further instructions on how to operate the codes is given precisely on the google colab notebooks text section.*]
