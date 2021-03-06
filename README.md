# Incremental Deep Learning for Image Classifiication
<p align = "center">
  COMING SOON!
</p>
 
 **Final Year Project @ Monash University**
<p><li>'Incremental Deep Learning for Image Classificationâ€™ is a continual-learning problem in various classification fields where many of the image classification datasets, such as Facial expression recognition and brain tumor radio-genomic classification datasets, available in the field are of smaller size and this makes the training of a neural network more difficult.</li>
<li>Developing a deep learning algorithm to apply an incremental learning model or approach to this dataset where the knowledge learned from training one dataset is transferred to another dataset. Implemented using PyTorch and a high-end GPU.</li></p>

<p align = "center">
  <img src = "https://www.markspaneth.com/assets/images/blog/_list_image/02_02_18_508408464_AAB_560x292.jpg">
</p>

>**Abstract:**<br>
A crucial open problem on the road to artificial intelligence and machine learning is the development and evolution of incrementally learning systems that learn about more and more concepts over time from a stream of data. It is often thought that the data for training different tasks is readily available at the beginning. However, when working in real-world applications where data arrive over time and previous data may no longer be available, it is definitely not an ideal solution to use conventional deep learning architectures due to the fact that these networks exhibit a significant drop in performance due to the downside effect of catastrophic forgetting. Instead, these networks are required to incrementally learn new and different tasks allocated to them and hence, different incremental learning strategies are required. In this work, we introduce the state-of-the-art incremental deep learning techniques and a new training strategy, iCaRL, where only the training data for a small number of classes has to be present at the same time and new classes can be added progressively. Moreover, a new algorithm to prevent forgetting is proposed, where a forgetting factor is implemented together with the loss functions which indicates the importance to preserve knowledge of previously learned data. This distinguishes the model from earlier works that were fundamentally limited to fixed data representations and therefore incompatible with deep learning architectures. The experiments are conducted on CIFAR-100 data, and comparisons are made between state-of-the-
art methods, iCaRL and the proposed model where the latter can learn many classes incrementally over a long period of time where other strategies such as fine-tuning algorithm
and knowledge distillation fail quickly.
