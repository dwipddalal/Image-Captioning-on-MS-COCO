# Image Captioning 
This model is inspired from the <a href="https://arxiv.org/pdf/1502.03044.pdf"> show, attend and tell </a>. There I have used soft-attention mechanism. In this case convolution output(image tensor) of the Inception model is taken so as to preserve the spatial details of the image. Then attention mechanism is applied on this image vector to give a context vector which will be used to generate captions by using it through RNN architecture. Here I have used the method of teacher forcing for training the RNN model.

# Results 
![image](https://user-images.githubusercontent.com/91228207/163112583-816a1efb-5495-4d02-b2c2-6870b0571ec0.png)

