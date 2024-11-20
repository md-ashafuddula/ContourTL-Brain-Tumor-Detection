# ContourTL-Brain-Tumor-Detection
Our work on Brain Tumor Detection entitled [ContourTL‐Net: Contour‐Based Transfer Learning Algorithm for Early‐Stage Brain Tumor Detection](https://onlinelibrary.wiley.com/doi/full/10.1155/2024/6347920) published in a reputable journal "International Journal of Biomedical Imaging (IF-3.3)" in 2024, we decided to share the code and data we used for this experiment.

## Abstract 

Brain tumors are critical neurological ailments caused by uncontrolled cell growth in the brain or skull, often leading to death. An increasing patient longevity rate requires prompt detection; however, the complexities of brain tissue make early diagnosis challenging. Hence, automated tools are necessary to aid healthcare professionals. This study is particularly aimed at improving the efficacy of computerized brain tumor detection in a clinical setting through a deep learning model. Hence, **a novel thresholding-based MRI image segmentation approach with a transfer learning model based on contour (ContourTL-Net) is suggested to facilitate the clinical detection of brain malignancies at an initial phase. The model utilizes contour-based analysis, which is critical for object detection, precise segmentation, and capturing subtle variations in tumor morphology. The model employs a VGG-16 architecture priorly trained on the “ImageNet” collection for feature extraction and categorization.** The model is designed to utilize its ten nontrainable and three trainable convolutional layers and three dropout layers. The proposed ContourTL-Net model is evaluated on two benchmark datasets in four ways, among which an unseen case is considered as the clinical aspect. Validating a deep learning model on unseen data is crucial to determine the model’s generalization capability, domain adaptation, robustness, and real-world applicability. Here, the presented model’s outcomes demonstrate a highly accurate classification of the unseen data, achieving a perfect **sensitivity and negative predictive value (NPV) of 100%, 98.60% specificity, 99.12% precision, 99.56% F1-score, and 99.46% accuracy**. Additionally, the outcomes of the suggested model are compared with state-of-the-art methodologies to further enhance its effectiveness. The proposed solution outperforms the existing solutions in both seen and unseen data, with the potential to significantly improve brain tumor detection efficiency and accuracy, leading to earlier diagnoses and improved patient outcomes.

## Major Contributions:

1. This study tackled the data diversity and robustness of the deep learning model by meticulously utilizing MRI image processing techniques. Particularly, the contour identiﬁcation and cropping with the maximum area and a thresholding-based tumor segmentation assisted in retaining the maximum notable features from images.
2. This study introduces a new thresholding based MRI segmentation procedure to segment brain tumor from the contour cropped image.
3. The key innovation lies in enabling three trainable convolutional layers and incorporating three dropout layers within the **VGG-16 transfer learning** model to oﬀer an advancement in the ContourTL-Net model for detecting and classifying braintumors. The incorporation of the dropout layers within the model mitigates overﬁtting and improves generalization for eﬃcient handling of unseen MRIdata with high eﬃcacy.

## Model Design

The detailed proposed architecture for eﬃcient brain tumor detection. This begins with preprocessing the input MRI images andthen employing transfer learning with a VGG-16 pretrained model for robust feature gathering and eﬀective tumor identiﬁcation. <img width="610" alt="image" src="https://github.com/user-attachments/assets/b7be5649-1ec8-4cd7-b934-a0aea47b9cab">

Process of brain contour cropping, showcasing image preprocessing techniques and enhancements to eﬀective contour detectionand cropping. 
<img width="673" alt="image" src="https://github.com/user-attachments/assets/8e0d0881-5117-4c1d-b505-1a1d0e4d406f">

<img width="350" alt="image" src="https://github.com/user-attachments/assets/075fc479-8eb5-42ec-b448-04c1837693cc">

**Algorithm 1:** Image segmentation threshold point. 
<img width="340" alt="image" src="https://github.com/user-attachments/assets/4cca3b29-b962-4606-8aa6-db92a62dd601">

**Transfer Learning model** 

<img width="683" alt="image" src="https://github.com/user-attachments/assets/9b6f964b-64fd-40ad-8675-a4fffeac8713">

## Dataset

<img width="685" alt="image" src="https://github.com/user-attachments/assets/f7e4f403-54b7-4ef6-8a0f-538a6cc4d176">

1. Dataset-1 [Brain MRI Images for Brain Tumor Detection, Version 1, 2019](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)
2. Dataset-2, [Br35H: brain tumor detection 2020 version 5, 2020](https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection)

## Result

<img width="680" alt="image" src="https://github.com/user-attachments/assets/3a999923-1123-4cbc-aa75-c048dc347ed6">

<img width="683" alt="image" src="https://github.com/user-attachments/assets/6962dfaa-2589-48b5-a4e0-5b4c5cce7182">

Experimental result (%) evaluation of the proposed methodology with the state-of-the-art methods for BR253 dataset. <img width="326" alt="image" src="https://github.com/user-attachments/assets/cb96cb1d-37f1-41a1-b3f7-85d494e073d6">

<img width="644" alt="image" src="https://github.com/user-attachments/assets/2a7c9ced-106d-4bf6-a27a-78c2eb70d402">

**Please cite our paper:**

```
@article{md2024contourtl,
  title={ContourTL-Net: Contour-Based Transfer Learning Algorithm for Early-Stage Brain Tumor Detection},
  author={Md. Ashafuddula, NI and Islam, Rafiqul},
  journal={International Journal of Biomedical Imaging},
  volume={2024},
  number={1},
  pages={6347920},
  year={2024},
  publisher={Wiley Online Library}
}
```


