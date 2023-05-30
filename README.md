<h1 align=center >Concrete Crack Classification Using VGG-16 and ResNet50: A Comparative Analysis</h1>

<img  src="https://raw.githubusercontent.com/doguilmak/Concrete-Classification-Computer-Vision-CoE/main/assets/concrete_crack_wp_meu_metu.png"  height=520  width=1000  alt="GitHub">
<small>Picture Source: <a  href="https://github.com/doguilmak">Doğu İlmak GitHub</a>

<br>  

<h2>Introduction</h2>  

<p>Concrete is widely used in construction due to its strength and durability. However, cracks can develop over time, compromising the structural integrity and aesthetics of concrete structures. In recent years, deep learning models have shown promising results in automating crack detection and classification. This scientific presentation focuses on the implementation and comparison of two popular convolutional neural networks (CNNs), VGG-16 and ResNet50, for concrete crack classification. The dataset from <a  href="https://data.mendeley.com/datasets/5y9wdsg2zt/2">mendeley</a> is used to train and evaluate the models, with the aim of providing insights into the performance and suitability of these models for crack classification tasks.</p>  

<br>  

<h2>Data Set</h2>

<p>The dataset contains concrete images having cracks. The data is collected from various <b>METU Campus Buildings</b>. The dataset is divided into two as negative and positive crack images for image classification. Each class has 20000 images with a total of 40000 images with <i>227 x 227</i> pixels with RGB channels. The dataset is generated from 458 high-resolution images (4032x3024 pixel) with the method proposed by Zhang et al (2016). <b>High-resolution images have variance in terms of surface finish and illumination conditions. No data augmentation in terms of random rotation or flipping is applied.</b></p> 

<br>  

<h2>Methodology</h2>  

<p>The methodology employed in this study involves the following steps: data collection, preprocessing, model architecture selection, training, and evaluation. The dataset used consists of images of cracked and non-cracked concrete surfaces. Initially, the data is preprocessed by resizing the images to improve model generalization. VGG-16 and ResNet50, both pre-trained on the ImageNet dataset, are chosen as the base architectures for transfer learning.</p>  

<p>Transfer learning is employed to fine-tune the networks on the concrete crack dataset. The last few layers of each model are replaced with fully connected layers, and the entire network is retrained using the dataset. During training, a suitable optimization algorithm and learning rate schedule are selected to ensure convergence and prevent overfitting. The models are then evaluated using various performance metrics, such as accuracy, precision, recall, and F1 score.</p>  

<br>  

<h2>Acknowledgements</h2>

<p>This dataset has been referred from <a  href="https://data.mendeley.com/datasets/5y9wdsg2zt/2">data.mendeley.com</a>.  

<i>If you use this dataset please cite: Özgenel, Çağlar Fırat (2019), “Concrete Crack Images for Classification”, Mendeley Data, V2, doi: 10.17632/5y9wdsg2zt.2</i></p>  

<br>  

<h2>License</h2>

<p>CC BY 4.0</p>

</p>The files associated with this dataset are licensed under a Creative Commons Attribution 4.0 International license.</p>

<p>What does this mean?</p>

  

<p>You can share, copy and modify this dataset so long as you give appropriate credit, provide a link to the CC BY license, and indicate if changes were made, but you may not do so in a way that suggests the rights holder has endorsed you or your use of the dataset. Note that further permission may be required for any content within the dataset that is identified as belonging to a third party.</p>  

<br>  

<h2>Objective:</h2>

<ul>
	<li>Understand the dataset.</li>
	<li>Build classification models to predict the concrete class.</li>
	<li>Also fine-tune the hyperparameters & compare the evaluation metrics of various classification algorithms.</li>
	<li>Evaluate the models.</li>
</ul>

  

<br>
<h2>Keywords</h2>
<ul>
	<li>Computer Science</li>
	<li>Classification</li>
	<li>Structure</li>
	<li>Neural Networks</li>
	<li>Concrete (Composite Building Material)</li>
	<li>Concrete Cracking</li>
</ul>

<br>

## Results and Discussion
  

<p>The trained VGG-16 and ResNet50 models are evaluated on a separate test set to measure their performance in concrete crack classification. The results show that both models achieve high accuracy, with VGG-16 obtaining an accuracy of 98% and ResNet50 achieving an accuracy of 94%.</p>  

<p>Further analysis reveals that VGG-16 outperforms ResNet-50 in terms of precision, recall, and F1 score, with values of <b>0.98</b>, <b>0.97</b>, and <b>0.98</b>, respectively. ResNet-50 exhibits slightly lower precision, recall, and F1 score values of <b>0.97</b>, <b>0.89</b>, and <b>0.94</b>, respectively. These findings suggest that VGG-16 has a higher ability to accurately classify cracks in concrete images.</p>  

<p>The superior performance of VGG-16 can be attributed to its deeper architecture and skip connections, which allow for better feature extraction and information flow through the network. On the other hand, residual connections in ResNet50 help mitigate the vanishing gradient problem, enabling more effective training.</p>  

<br>

## Conclusion  

<p>In conclusion, this study demonstrates the successful implementation of VGG-16 and ResNet50 for concrete crack classification. Both models achieve high accuracy, but <b>VGG-16</b> exhibits superior precision, recall, and F1 score. These findings highlight the importance of selecting an appropriate CNN architecture for accurate and reliable crack classification in concrete structures.<p>

<h1>Contact Me</h1>

<p>If you have something to say to me please contact me:</p> 

<ul>
	<li>Twitter: <a  href="https://twitter.com/Doguilmak">Doguilmak</a></li>
	<li>Mail address: doguilmak@gmail.com</li>
</ul>
