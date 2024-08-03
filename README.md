# Automated Classification of Tumor Infiltrating Lymphocytes in Breast Cancer Using Deep Learning Techniques
Tiana Le, Naomi Yamaguchi, Ishaan Babbar (Group 4)
Georgetown University
August 3rd, 2024


## Abstract
	This study explores the application of deep learning neural networks to accurately identify Tumor-Infiltrating Lymphocytes (TILs) in breast cancer histopathology images. Given the intricate details and substantial storage demands of these images, traditional analysis methods often are less efficient and have less accuracy. By utilizing CNN architectures such as AlexNet, ResNet 50, GoogleNet, and VGG 16, we assessed the performance of these models based on top-1 and top-5 accuracy metrics. Our results demonstrated that GoogleNet achieved a perfect classification accuracy of 100%, followed by ResNet 50 with 97.1%, and AlexNet with 94.1%, while VGG 16 lagged significantly behind with accuracies of 52.9% and 51.4% respectively. These findings indicate that deep learning models can significantly enhance the identification of TILs, which can offer substantial improvements in diagnostic accuracy, efficiency, and consistency. This research supports the potential of integrating advanced neural networks into medical image analysis workflows, which can lead to enhanced patient outcomes and improved tools for clinical research.

## Introduction 
Breast cancer is one of the most common forms of cancer in the world. According to the American Cancer Society, it is the second leading cause of death in women with an estimation of 310,720 new diagnosed cases of invasive breast cancer in 2024. Breast cancer has a complicated biology with many different types. The different breast cancer types are classified by different biomarkers, such as hormones, proteins, and cell biology. Tumor infiltrating lymphocytes (TILs) are a type of immune cell that are an important biomarker in the prognosis of breast cancer. TILs can have a role in killing cancer cells. Breast cancer patients with triple negative breast cancer and high TIL scores have been shown to have improved treatment response and survival outcomes. Therefore, the presence and density of TILs can provide valuable insights into the tumor's cell biology and its interaction with the immune system. This may lead to the discovery of better treatments with immunotherapy and chemotherapy. As research into TILs continues to expand, understanding the role of TILs in fighting cancer could provide new directions for more personalized and effective treatment strategies, making them a potentially a critical prognostic factor in the evolution of breast cancer management.

Since the identification of TILs is an important determining breast cancer management, this project aims to find automated methods to classify TILs in breast cancer histopathology slides. The objective is to explore different computer vision techniques that will provide insights about the ability of data science methods to accurately predict the presence of TILs. The aim of our project is to compare the performance of four different deep learning neural networks in predicting the presence of TILs in histopathology images.

