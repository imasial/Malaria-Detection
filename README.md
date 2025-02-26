# Malaria-Detection

The context: Why is this problem important to solve?
Malaria is a disease caused by Plasmodium parasites, which are spread to people through the bites of infected female Anopheles mosquitoes.

According to world Malaria report 2024, there were estimated 263 million malaria cases world wide in 2023, This figure shows 11 million increase comapre to 2022 when the estimate figure was 252 million. There were an estimated 5,97,000 death due to malaria in 2023. The WHO African region accounted for approximatly 95% of these death (around 5,69,000) with childern under 5 year old. Globaly, children under 5 accounted for 73.7% of all malaria death.

Traditional diagnose in labartory require carefull examination by proffesional to inspect the microscopic image of red blood cell infected or not infected. Which require not only lot of time but also very slow and chances of erorr are high.

Therefore an automated system can help with early and accuratly detection of Malaria. Application of automated classification with Machine Learning and Artificial Inteligence has proven the higher accuracy compare to manual classification. It would be highly benefical to prposed a method that perform malaria detection using deep learning techinque.

The objectives: What is the intended goal?
The objective of this program is to build a Computer Vision model that can Detect Malaria by Classifing the Infected Cell (Parasatized) and unifected (non-Parasatized) cell.

The key questions: What are the key questions that need to be answered?
The Key question is our model can detect weather the Microscopic cell image contain Parastized (Malaria) or no. in Simple word it will detect the infected images contain Malaria.

The problem formulation: What is it that we are trying to solve using data science?
✅ 1. Problem Understanding & Goal Definition

Identify the core problem: Detect malaria-infected cells from blood microscopic images.

Define success metrics: Accuracy, precision, recall, F1-score, and false positive/negative rates.

Understand domain-specific challenges: Similarity between infected and uninfected cells. Variability in image quality due to different microscopes or lab settings.

✅ 2. Feature Engineering & Model Development

Feature Extraction:

Extract features like cell shape, color intensity, texture, and edges using edge detection. Use Convolutional Neural Networks (CNNs) for automatic feature learning in image-based tasks.

Model Selection & Training:

Start with simpler models (SVM, Random Forest) and move to deep learning (CNNs, ResNet, EfficientNet) for complex patterns.

Experiment with transfer learning using pre-trained models like VGG16 or ResNet50.

Hyperparameter Tuning:

we will Optimize learning rate, batch size, and network architecture for the best performance.

✅3. Evaluation & Validation

Use Balanced Metrics:

In medical diagnosis, false negatives (missing an infected cell) are critical, so we will prioritize recall and F1-score.

Cross-Validation:

Ensure the model generalizes well to unseen data by using techniques like k-fold cross-validation.

Error Analysis:

Investigate misclassified samples to understand model weaknesses and iterate on improvements.

💡 Summary of Data Scientist's Goals in Malaria Detection:

1.Build accurate and reliable diagnostic tools. 2.Reduce time and cost of traditional malaria testing. 3.Improve healthcare accessibility in under-resourced areas. 4.Contribute to global efforts in malaria eradication through technology.

Data Description
There are a total of 24,958 train and 2,600 test images (colored) that we have taken from microscopic images. These images are of the following categories:

Parasitized: The parasitized cells contain the Plasmodium parasite which causes malaria
Uninfected: The uninfected cells are free of the Plasmodium parasites

