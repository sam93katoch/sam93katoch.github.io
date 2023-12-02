---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

> The pdf version of cv can be found <a href="{{ base_path }}/files/Resume_SK.pdf">here</a>


## Education

* B.Tech in Electrical Engineering, NIT Srinagar, 2015
* M.S. in Electrical Engineering, Arizona State University, 2018
* Ph.D in Electrical Engineering, Arizona State University, 2022

## Work experience

* Present: Senior Machine Learning Engineer, Qualcomm, San Diego, CA
  * Duties included: Developing memory efficient deep learning models using neural network architectures such as, Long Short Term Memory (LSTM), Recurrent Neural Networks (RNNs), Convolutional Neural Networks (CNNs) and Transformers for multiple applications including Speech Separation and Speech Enhancement for products in VoiceUI and infotainment. Conducting experiments to tune relevant hyperparameters such as learning rate, chunk size and weight decay to make the model real time realizable. Convert trained models to ONNX format for on-chip implementations for multiple downstream products. Documenting research findings in manuscripts submitted to different publishing venues (NeurIPS, ICASSP, Interspeech) and developing live demonstrations to effectively communicate the application.
  * Supervisor: Asif Mohammad

* Summer 2020: Student Computing Intern, Lawrence Livermore National Labs, CA
  * Duties included: Developing a structured meta-learning paradigm for effective domain adaptation and multi-task learning and showcased the effectiveness of the method using datasets such as iMaterialist, DeepFashion, iNaturalist, OfficeHome, PACS, CUB-200 and DomainNet. Performing a study using knee X-ray dataset to derive the meta information such as age, sex, gender and BMI information. This study was performed to understand whether such medical image data, preserves the privacy of the patients or if it is relatively easy to extract meta-information clues using machine learning. To this end, individual Efficient Net based deep learning models were developed in Pytorch for each meta information criterion. Developing encryption strategies using data manipulation techniques such as, mixup to perform patient data de-identification for safe data sharing within healthcare organizations. Developed privacy preserving machine learning models that were trained on conventional medical image data with a constraint such that, the trained models can also perform with high accuracy on encrypted data for machine learning based diagnostic applications.
  * Supervisor: Jayaraman J. Thiagarajan
  <!-- * Supervisor: Professor  -->

* Summer 2018: Data Scientist Intern, Prime Solution Group, AZ
  * Duties included: Developing a python script to pre-process multivariate weather data to study the seasonal trends and make the data suitable for predictive modelling. Developing a deep learning based predictive model using recurrent neural networks (RNNs) to perform irradiance prediction using weather attributes including cloud type, temperature, relative humidity, etc. Developing a deep learning based joint predictive model using Long Short Term Memory (LSTM) Neural Network for photovoltaic power forecasting based on multivariate weather data for the Arizona region.
  * Supervisor: John Cadigan
  <!-- * Supervisor: Professor Hub -->
  
## Skills

* Programming Languages: Python (Numpy, Scipy, Pandas, OpenCV), Matlab, C, C++
* Tools and Libraries: Pytorch, Keras, Tensorflow, Git, Audition, SPSS, LateX, Microsoft Visio

## Publications

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Teaching

* Teaching assistant
 1. EEE407/591 - Digital Signal Processing
 1. EEE334 - Circuits II 
  
## Awards

* IEEE Al Gross Award, IEEE, April 6 2019 
