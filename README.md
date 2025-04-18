# JCIA Hackathon 2025 – Plum Fruit Detection System

## Team BytePulse 
- Dyl Padaran Ambe Munjo Level400 University of Buea FET (Faculty of Engineering and Technology) ML-MLOps Developer
- Messi II Rostand Innocent Level500 University of Buea FET (Faculty of Engineering and Technology) Flutter Developer
- Teku Ndi Betrand Level400 University of Buea FET (Faculty of Engineering and Technology) Flutter Backend Developer and Integrations

## Steps To Replicate
- Enter Google Colab
- Import the Juypter Notebook in this repository
- Select runtime type and select T4 GPU
- Run each cell
- All the visualisations are saved in the session filesystem

## Overview

Welcome to the official repository of our project developed during the JCIA Hackathon 2025. Our objective was to create an intelligent system capable of detecting and classifying plum fruits using machine learning techniques. By implementing an enhanced VGG16 model, inspired by the study "Defect Classification of Green Plums Based on Deep Learning" by Haiyan Zhou et al. because their classes closely mirror our classes and they obtained performances at 96.5% mean accuracy, we achieved significant milestones in training and validation accuracy. Testing finetuned models like EfficientNet, ConvxNet and object detection models didn't give performances above 76%. We found out the very popular dataset given to use had over **1533** **duplicates** severely affecting model performance

## Project Highlights

- **Training Accuracy**: 99.67%
- **Maximum Validation Accuracy**: 78.77%
Our model demonstrated exceptional performance, particularly in real-world scenarios, by accurately classifying images sourced randomly from the internet.

- **Data Augmentation Techniques**: Implementing brightness adjustments and other augmentation strategies to improve model robustness in varying environmental conditions.

## Methodology

### Model Architecture

We employed an enhanced VGG16 model, incorporating stochastic weight averaging (SWA) and a weighted softmax loss function, as detailed in the referenced study. This approach facilitated efficient classification of plum defects, achieving an average recognition accuracy of 93.8% in the original study citeturn0search1.

### Data Preprocessing

To ensure the robustness of our model, we implemented a hashing technique to identify and remove duplicate images from our dataset, addressing the issue of data redundancy that can skew model performance.

## Mobile Application

Experience our plum detection system on the go with our mobile application.

- [link the Mobile App](https://github.com/Messi002/Plum-AI-Classifier)

## Presentation

Gain insights into our project's development and findings through our comprehensive presentation.

- [View the Presentation](https://youtube.com/shorts/b2CVsJGmOQM?si=i6liMiIKQIQhlpRS)

## Team Members

Meet the dedicated individuals behind this project.

- [Team Profiles](https://youtube.com/shorts/ImENvE9BysM?si=eoVxdHc6NoIik8cR)

## Future Work

To enhance the generalization capabilities of our model, we plan to explore the following avenues:

- **Integration with YOLO Models**: Leveraging YOLOv5 and YOLOv7 architectures for improved object detection and classification, inspired by studies such as "CAM-YOLO" citeturn0search6 and "YOLOv7-Plum" citeturn0search3.


- **Advanced Loss Functions**: Exploring loss functions like MIoU, DIoU, and SIoU to enhance model convergence and accuracy.

- **Real-Time Deployment**: Developing a real-time detection system by integrating our classification model with YOLO-based object detection frameworks.

## References

1. Zhou, H., Zhuang, Z., Liu, Y., Liu, Y., & Zhang, X. (2020). Defect Classification of Green Plums Based on Deep Learning. *Sensors*, 20(23), 6789. citeturn0search1

2. Arulselvi, G., & Balaji, G. N. (2023). CAM-YOLO: Tomato detection and classification based on improved YOLOv5 using combining attention mechanism. *PeerJ Computer Science*, 9, e1463. citeturn0search6

3. Liu, C., Lin, W., Feng, Y., Guo, Z., & Xie, Z. (2023). ATC-YOLOv5: Fruit Appearance Quality Classification Algorithm Based on the Improved YOLOv5 Model for Passion Fruits. *Mathematics*, 11(16), 3615. citeturn0search2

4. Zhang, Y., Wang, J., Li, X., & Liu, Y. (2023). YOLOv7-Plum: Advancing Plum Fruit Detection in Natural Environments with Deep Learning. *Plants*, 12(15), 2883. citeturn0search3

5. Fongang, A. N., et al. (2024). Intelligent Vision System with Pruning and Web Interface for Real-Time Defect Detection on African Plum Surfaces. *Information*, 15(10), 635. citeturn0search0

---

# Hackathon JCIA 2025 – Système de Détection de Fruits de Prune

## Aperçu

Bienvenue dans le dépôt officiel de notre projet développé lors du Hackathon JCIA 2025. Notre objectif était de créer un système intelligent capable de détecter et de classer les fruits de prune en utilisant des techniques d'apprentissage automatique. En implémentant un modèle VGG16 amélioré, inspiré de l'étude "Defect Classification of Green Plums Based on Deep Learning" de Haiyan Zhou et al., nous avons atteint des étapes significatives en termes de précision d'entraînement et de validation.

## Points Forts du Projet

- **Précision d'Entraînement** : 99,67%
- **Précision de Validation Maximale** : 78,77%

Notre modèle a démontré une performance exceptionnelle, en particulier dans des scénarios réels, en classant avec précision des images provenant aléatoirement d'internet.

## Méthodologie

### Architecture du Modèle

Nous avons utilisé un modèle VGG16 amélioré, incorporant l'optimiseur SWA et une fonction de perte softmax pondérée, comme détaillé dans l'étude référencée. Cette approche a facilité la classification efficace des défauts de prune, atteignant une précision moyenne de reconnaissance de 93,8% dans l'étude originale  
