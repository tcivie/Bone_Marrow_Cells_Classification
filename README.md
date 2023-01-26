# Welcome to my "Introduction to Artificial Intelligence" final project repository!

In this project, I explored how different preprocessing techniques and configurations of artificial neural networks (ANNs) can impact the performance of a model for the task of classifying bone marrow cells. I used a dataset containing a collection of over 170,000 de-identified, expert-annotated cells from the bone marrow smears of 945 patients stained using the May-Grünwald-Giemsa/Pappenheim stain. I implemented a variety of preprocessing methods, such as normalization, standardization, and feature selection, to prepare the data for model training. I then trained multiple ANNs with different architectures and hyperparameter settings, and evaluated their performance using various metrics.

My project aims to provide a comprehensive analysis of the effects of preprocessing and ANN/SVM configurations on model performance for this specific task, and to give insights into best practices for these tasks in real-world applications. I hope that this project will be useful for students and practitioners alike as a reference for understanding the impact of these factors on model performance in the context of bone marrow cell classification.

The project is implemented in Python using popular libraries such as Keras and Numpy. The code is fully documented and organized into clear, modular functions for easy understanding and reuse.

I welcome any feedback on this project. Thank you for checking it out!

## Files
* [Main PDF with the work and the conclusions](Final%20Project%20in%20AI.pdf)
* [Colab notebook for the CNN](AI_Project_CNN.ipynb)
* [Colab notebook for the SVM](AI_Project_SVM.ipynb)

## Bibliography
### Data Citation

Matek, C., Krappe, S., Münzenmayer, C., Haferlach, T., & Marr, C. (2021). An Expert-Annotated Dataset of Bone Marrow Cytology in Hematologic Malignancies [Data set]. The Cancer Imaging Archive. https://doi.org/10.7937/TCIA.AXH3-T579

### Publication Citation

Matek, C., Krappe, S., Münzenmayer, C., Haferlach, T., and Marr, C. (2021). Highly accurate differentiation of bone marrow cell morphologies using deep neural networks on a large image dataset. https://doi.org/10.1182/blood.2020010568

### TCIA Citation

Clark K, Vendt B, Smith K, Freymann J, Kirby J, Koppel P, Moore S, Phillips S, Maffitt D, Pringle M, Tarbox L, Prior F. The Cancer Imaging Archive (TCIA): Maintaining and Operating a Public Information Repository, Journal of Digital Imaging, Volume 26, Number 6, December, 2013, pp 1045-1057. DOI: 10.1007/s10278-013-9622-7
