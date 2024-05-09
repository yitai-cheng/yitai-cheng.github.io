---
layout: page
title: About
permalink: /about/
---
<style>
  .content {
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.5s ease-out;
  }
  .toggle-button {
    cursor: pointer;
    text-decoration: underline;
  }
  p {
    text-align: justify; /* Aligns text within the paragraph */
  }
</style>

<img src="/assets/images/yitai-cheng.JPG" width="100" style="float: left; margin-right: 10px;"> Hi, My name is Yitai Cheng (程翊泰 in Chinese). I am currently seeking Ph.D. positions in Artificial Intelligence and Machine Learning related fields. 


I obtained my MSc Integrated Machine Learning Systems with distinction from University College London (UCL) in December 2023. Before that I was an undergraduate student studying Telecommunications Engineering with Management registered in Queen Mary University of London (QMUL) and Beijing University of Posts and Telecommunications (BUPT). I was awarded First Class Honours for my BSc(Eng) Telecommunications Engineering with Management by Queen Mary University of London.

During My MSc, I did several projects related to machine learning and data science.

<p class="toggle-button" onclick="toggleContent(this)"> <b>MSc Research Project: On-the-Sphere Residual Learning for Neural Compression of 360-degree Videos </b> </p>
<div class="content">
  <p>This project focus on the synergy of two current learning methods for video. The first is neural video compression, which improves traditional one certain steps. Traditional   compression captures motion between consecutive frames and performs linear transform and quantisation methods over the residual information in each frame to be encoded. Differently, neural video compression uses methods such as convolutional neural networks (CNNs) to capture motion and encoder-decoder architectures to propose to compress residual data. The second is spherical convolutional neural networks (CNNs) for 360-degree videos. The current compression of such 360-degree videos intensively relies on 2D planar projection and suffers from its distortion (e.g., poles are more sampled than equator). Therefore, neural compression using CNNs, which focus on 2D convolution over planar data, is damaged when applied to 360 videos. Some authors have evaluated the benefit of using spherical convolutions in learning tasks for 360 images. The project is experiments-oriented, and the student will focus on implementing neural compression methods but changing the CNN steps by ones using spherical convolutions.
  </p>
  <p><a href="https://github.com/yitai-cheng/MSc_IMLS_Research_Project.git">[Python code]</a> <a href="/assets/msc-dissertation.pdf">[Dissertation]</a></p>
</div>

<p class="toggle-button" onclick="toggleContent(this)"> <b>Data Acquisition and Processing Systems project</b> </p>
<div class="content">
  <p>This project simulates a real-life data-science situation thatcan be approached using the process including data acquisition, storing, preprocessing, exploration and inferring. Concretely, this project analyze the stocks data of American Airlines(AAL) and its correlation with weather and covid-19 data. The data is acquired by relevant application programming interface including Yahoo! Finance, NOAA,
and CDC API. Then the acquired data is stored both locally and in the cloud by MongoDB. The data could be retrieved from local disk and cloud database for the downstream preprocessing including data cleaning, visualization and transformation. Next, the exploratory data analysis is conducted to find potential pattern of the data and hypothesis testing is carried out to better understand the composition of your dataset and its representativeness. Finally, the preprocessed data is feed as input to train and test the LSTM model which could be later used to predict the trend of stock values in the future.
  </p>
<p><a href="https://github.com/yitai-cheng/DAPS_assignment22_23">[Python code]</a> <a href="/assets/DAPS-assignment.pdf">[Project Description]</a> <a href="/assets/Report_DAPS.pdf">[Report]</a></p>
</div>

<p class="toggle-button" onclick="toggleContent(this)"> <b>Applied Machine Learning Systems I project </b> </p>
<div class="content">
  <p>
There are two categories of tasks raised in this mini project. They are binary classification and multiclass classification for image datasets. Machine learning techniques including convolutional neural network (CNN), support vector machine (SVM), random forest (RF) and residual network (ResNet) are applied to address the image classification tasks. It is noticed that neural network (NN) based models including CNN and ResNet performs better than the other two models with the accuracy of 0.7550 for CNN and 0.8064 for ResNet respectively.
  </p>
  <p><a href="https://github.com/yitai-cheng/AMLS_assignment22_23">[Python code]</a> <a href="/assets/AMLS-assignment.pdf">[Project Description]</a> <a href="/assets/Report_AMLS.pdf">[Report]</a></p>
</div>

<p class="toggle-button" onclick="toggleContent(this)"> <b>Applied Machine Learning Systems II project </b> </p>
<div class="content">
  <p>
A malignant tumor in the brain is a life-threatening condition. The presence of Methylguanine methyltransferase (MGMT) promoter methylation has been shown to be a favorable prog- nostic factor and a strong predictor of responsiveness to chemotherapy. In this project, machine learning based models are proposed to deal with the detection of MGMT promoter methylation instead of invasive surgeries taking brain tissues out of patients’ body. Taking advantage of multiple modali- ties of MRI images, both Single Modality Model (SMM) and Multi-Modality Model (MMM) are proposed. The main building block of SMM is the feature extractor and that of MMM is feature extractor with the attention layer. By exper- iments and ablation study, it is found that multi-modal learn- ing based model MMM performs better than SMM thanks to the attention mechanism.
  </p>
  <p><a href="https://github.com/yitai-cheng/AMLS_II_assignment22_23">[Python code]</a> <a href="/assets/AMLS_II-assignment.pdf">[Project Description]</a> <a href="/assets/Report_AMLSII.pdf">[Report]</a>  </p>
</div>

<p class="toggle-button" onclick="toggleContent(this)"> <b>Deep Learning for Natural Language Processing project </b> </p>
<div class="content">
  <p>
    Recurrent Neural Networks (RNNs) are powerful models that have achieved excellent performance on sequence learning tasks. Although RNNs work well whenever large labeled training sets are available, they suffer from dealing with long squences. In this project, we present a general end-to-end approach to sequence learning that uses an encoder to map the input sequence to a context vector, and then another decoder to convert the vector to the target sequence. Then, we introduce attention mechanism enabling the decoder to focus on a certain part of the input sequence in each decoding step. Our main result is that on an English to French translation task from the WMT’14 dataset, the translations produced by the sequence to sequence model with greedy search algorithm achieve a BLEU score of 23.57 on the entire test set, where the LSTM’s BLEU score was penalized on out-of-vocabulary words. Additionally, beam search could improve the model performance due to its ability to explore on a larger result set. For comparison, a sequence to sequence model with beam size 2 achieves a BLEU score of 24.24 on the same test-set. Moreover, the upgraded sequence to sequence with attention model also achieves a higher BLEU score of 25.33 with greedy search. Finally, we found that stacking more than one LSTM (Multi-Layer LSTM) will improve the model’s performance markedly, because LSTM networks with multiple layers have higher modeling capacity compared to single-layer LSTM networks.
  </p>
    <p><a href="https://github.com/yitai-cheng/ELEC0141_Project">[Python code]</a> <a href="/assets/DLNLP-assignment.pdf">[Project Description]</a> <a href="/assets/Report_DLNLP.pdf">[Report]</a></p> 

</div>


<script>
  function toggleContent(element) {
    var content = element.nextElementSibling;
    if (content.style.maxHeight) {
      content.style.maxHeight = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
    }
  }
</script>



