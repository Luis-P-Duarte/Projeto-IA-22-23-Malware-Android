(The portuguese version of this file can be found in [README_PT.md](README_PT.md))
# Projeto-IA-22-23-Malware-Android
Detection and Classification of Android Malware with Deep Learning

This project was developed by Edgar Andrade and Luís Duarte under the guidance of Professor João da Silva Pereira and Professor Humberto Ferreira.
# Information
Here are relevant information about the contents of this repository.
## Dataset
In this work, the CICMalDroid2020 dataset[^1][^2] was used, which can be requested at https://www.unb.ca/cic/datasets/maldroid-2020.html.
## Feature Extraction
Feature Extraction
The feature extraction process used in this work was based on the project by Asim Darwaish and Farid Naït-Abdesselam[^3], which can be found at https://github.com/asimswati553/RGB-based-Andorid-Malware-detection.
## Notes
- The Images folder contains two RAR files that have images with dimensions 64x64 and 80x80 generated and used in this project.
  
- The Dataset and Models directories come with a ready-to-use structure, with the text files contained in them only serving to commit the directories.

- To use the application in its current state, it is necessary to insert three models into the [App/models/](App/models/) folder, with the names "flatten.hdf5," "conv2D.hdf5," and "resnet50.hdf5."
# Dependency Installation
This work was developed using Python version 3.10.9, and the use of this version is recommended.

To install all the necessary packages for the application to work, simply run the following command:
```shell
pip install -r requirements.txt
```
# Running the Application
To start the application, simply run the following command in the console, inside the App folder.
```shell
python MalwareClassificationApp.py
```
# References
[^1]: Samaneh Mahdavifar, Andi Fitriah Abdul Kadir, Rasool Fatemi, Dima Alhadidi, Ali A. Ghorbani; Dynamic Android Malware Category Classification using Semi-Supervised Deep Learning, The 18th IEEE International Conference on Dependable, Autonomic, and Secure Computing (DASC), Aug. 17-24, 2020.

[^2]: Samaneh Mahdavifar, Dima Alhadidi, and Ali A. Ghorbani (2022). Effective and Efficient Hybrid Android Malware Classification Using Pseudo-Label Stacked Auto-Encoder, Journal of Network and Systems Management 30 (1), 1-34.

[^3]: A. Darwaish e F. Naït-Abdesselam, “RGB-based Android Malware Detection and Classification Using Convolutional Neural Network,” 
RGB-based Android Malware Detection and Classification Using Convolutional Neural Network, 2020.
