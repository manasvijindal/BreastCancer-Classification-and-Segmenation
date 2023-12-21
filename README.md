# Advancing Breast Cancer Segmentation: An Ensemble Learning Approach

Automated breast cancer diagnosis heavily relies on the intricate analysis of medical images using machine learning models. Individual models play an important
role in this, but they frequently face issues such as overfitting, limited generalization, hyperparameter sensitivity, and vulnerability to noisy data. This study looks
into the revolutionary possibilities of ensemble learning in overcoming these limitations and improving the breast cancer image segmentation accuracy. Individual
models, including UNet, Attention UNet, Residual UNet, SegNet, and DeepLab,
were individually trained in this research. Despite achieving notable results in
segmenting the cancerous tumour, these models exhibited drawbacks such as overfitting to training data ,biased predictions, and limited adaptability to diverse
patterns within medical images. To address these problems, we propose the use
of ensemble learning—a strategy which involves combining different models and
applying a threshold.This method was remarkably effective in addressing the limitations of individual models and yielded improved segmentation results. DeepLab
and Attention UNet emerged as a powerful combination, attaining a Mean IOU
of 0.876 and a Mean Dice Coefficient of 0.932, resulting in an IoU Dice Balance
of 0.904 at a threshold of 0.9.Moreover, various ensemble combinations involving
three, four, and five models were explored, revealing their potential to further
boost segmentation accuracy. The structured approach, from data preprocessing
to data classification to ensemble learning, represents a significant advancement in
improving segmentation accuracy for medical image analysis, thus contributing to
more accurate healthcare diagnostics.
