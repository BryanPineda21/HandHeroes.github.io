# HandHeroes


**Developed a bidirectional CNN system that translates ASL alphabet signs to English text and provides visual ASL demonstrations from text input, addressing the critical shortage of qualified ASL instructors affecting deaf children's education. Applied advanced computer vision techniques including transfer learning and performance optimization within a comprehensive machine learning project.**


## Problem Statement <!--- do not change this line -->

**American Sign Language serves as the primary language for many deaf individuals, yet significant barriers exist in ASL education accessibility. Research indicates that language deprivation remains a critical issue for deaf children, with many lacking access to qualified ASL instructors. Only about one-fourth of parents first learn about ASL from their early intervention provider, highlighting the shortage of professional support. Our project addresses this gap by creating an interactive, engaging platform for children to learn ASL alphabet recognition, making ASL learning more accessible to both deaf and hearing children.**

## Key Results <!--- do not change this line -->


1. *Developed bidirectional ASL recognition system capable of translating ASL alphabet signs to English text      and generating visual ASL demonstrations from text input*
2. *Achieved 93% training time optimization by transitioning from single-threaded to multi-threaded data loading (num_workers=0 to multi-core) and batch size optimization, reducing training time from 7+ hours to 30 minutes*
3. *Trained CNN models on 87,000+ images across 29 ASL alphabet classes with robust data preprocessing and augmentation techniques*
4. *Implemented transfer learning using multiple pre-trained architectures (ResNet-50, VGG-16, InceptionV3) for enhanced model performance*
5. *Designed child-friendly educational tool with gamification elements to make ASL learning engaging and accessible*


## Methodologies <!--- do not change this line -->

*To accomplish this, we utilized supervised learning with Convolutional Neural Networks (CNNs) for image classification. The system was trained on Google Colab using PyTorch and TensorFlow frameworks. We implemented transfer learning techniques with pre-trained models including ResNet-50, optimized for hand gesture recognition. Custom data preprocessing pipelines were developed using NumPy for image normalization and resizing, while matplotlib was used for data visualization and model performance analysis. The training process was significantly optimized through multi-threaded data loading and batch size tuning, resulting in a 93% reduction in training time while maintaining model accuracy across 29 ASL alphabet classes.*


## Data Sources <!--- do not change this line -->

*Kaggle Datasets: [ASL-Alphabet](https://www.kaggle.com/datasets/grassknoted/asl-alphabet) - 87,000 images across 29 classes (26 letters + space, delete, nothing), 3,000 images per class with consistent 200x200 pixel resolution*

## Technologies Used <!--- do not change this line -->

- *Python*
- *PyTorch*
- *TensorFlow*
- *NumPy*
- *matplotlib*
- *Google Colab*
- *Convolutional Neural Networks (CNN)*
- *Transfer Learning (ResNet-50)*


## Authors <!--- do not change this line -->

*This project was completed in collaboration with:*
- *BRYAN PINEDA ([bpineda2@fordham.edu](mailto:bpineda2@fordham.edu))*
- *Cecilia Tran ([ctran0905@berkeley.edu](mailto:ctran0905@berkeley.edu))*
- *James Boateng ([boatengj@lafayette.edu](mailto:boatengj@lafayette.edu))*
