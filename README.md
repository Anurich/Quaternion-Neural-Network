<h2> Paper. </h2>
https://arxiv.org/pdf/1903.00658.pdf

<h2> Quaternion Neural Network </h2>
When dealing with multi-channelinputs  (e.g.,  color  images), 
the  convolution  kernels  merges  these  channels  by summing up the convolution results and output one single channel per kernel accordingly.
Although  such  a  processing  strategy  performs  well  in  many  practical  situ-ations,  
it  congenitally  suffers  from  some  drawbacks  in  color  image  processing tasks. Firstly, for each kernel it just sums up the outputs corresponding to dif-ferent channels and ignores the complicated interrelationship between them. 
Ac-cordingly,  we  may  lose  important  structural  information  of  color  and  obtainnon-optimal  representation  of  color  image  [36].  Secondly,  simply  summing  upthe outputs gives too many degrees of freedom to the learning of convolutionkernels, and thus we may have a high risk of over-fitting even if imposing heavyregularization  terms. 
How  to  overcome  these  two  challenges  is  still  not  fully-investigated
