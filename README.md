# Image Captioning 
This model is inspired from the <a href="https://arxiv.org/pdf/1502.03044.pdf"> show, attend and tell </a>. There I have used soft-attention mechanism. In this case convolution output(image tensor) of the Inception model is taken so as to preserve the spatial details of the image. Then attention mechanism is applied on this image vector to give a context vector which will be used to generate captions by using it through RNN architecture. Here I have used the method of teacher forcing for training the RNN model.

Results
![image](https://user-images.githubusercontent.com/91228207/163112384-307991f8-04d4-4f4c-a539-ec6225247037.png)
