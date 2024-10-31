<h1 align="center">Deep Learning with PyTorch & Captum: Explainability in Image Classification</h1>

<p align="center">This personal project employs PyTorch and VGG19 for binary image classification, utilizing Captum for model explainability.</p>

---

This project classifies images into “smoking” and “not smoking” categories using Deep Learning, with a focus on model explainability through Captum. To address data scarcity and enhance performance, Data Augmentation and Transfer Learning with the VGG19 model were employed. Captum further adds explainability by identifying influential features, making the model’s classification process more transparent.

<h3>Libraries Used</h3>

- **PyTorch:** For building, training, and evaluating the Deep Learning model.
- **Captum:** For model explainability, helping to identify important features and understand how different layers contribute to predictions.

You can view the detailed Notebook for this project [here](https://github.com/NajdBinrabah/Deep-Learning-with-PyTorch-and-Captum/blob/main/Deep_Learning_with_PyTorch_%26_Captum_Explainability_in_Image_Classification.ipynb).

<h3>Models and Techniques Explored</h3>

**1. Data Augmentation**

Data augmentation increases the diversity of training data by introducing variations such as cropping, rotation, and color adjustments. This approach helps address data scarcity by providing the model with more varied examples, ultimately improving its ability to generalize to new images.

**2. Transfer Learning with VGG19**

Transfer Learning leverages a pre-trained model, VGG19, initially trained on a large-scale image dataset. For this project, VGG19’s depth was selected to capture subtle details in smoking vs. non-smoking images, which are critical for accurate classification. Transfer Learning speeds up training and boosts performance by applying knowledge from similar tasks.

**3. Captum Explainability**

Captum enables explainability in Deep Learning models by offering methods that highlight important features for each prediction. This project explores:

-	**Primary Attribution** methods to identify the most influential image regions in model decisions. 
-	**Layer Attribution** techniques to understand layer-wise contributions, revealing areas of the image the model emphasizes for classification.
