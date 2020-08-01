# Pet_Classification_CNN

<p>I have used a very small data set:</p>
<p>Training data - 40 images</p>
<p>Test data - 20 images</p>

<p>I have made two Convolutional Layers for our Convolutional Network:</p>
  <p>-- Convolutional layer 1 with 32 filters of kernel size[5,5]</p>
  <p>-- Pooling layer 1 with pool size[2,2] and stride 2</p>

  <p>-- Convolutional layer 2 with 64 filters of kernel size[5,5] </p>
  <p>-- Pooling layer 2 with pool size[2,2] and stride 2 </p>

  <p>--  Dense layer whose output size is fixed in the hyper parameter: fc_size=32</p> 
  <p>-- Dropout layer with dropout probability 0.4 </p>
  

<p><h3>The model is trained for 15 20 and 25 epochs.</h3></p>
<p>For 15 epochs -- Accuracy-75%.</p>
<p>For 20 epochs -- Accuracy-75%.</p>
<p>For 25 epochs -- Accuracy-69.99%.</p>


<p>Thus we see for such a small data we get maximum accuracy of 75% and as we increase the epochs the accuracy decreases.</p>
