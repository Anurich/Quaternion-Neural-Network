<h2> Paper. </h2>
https://arxiv.org/pdf/1903.00658.pdf

<h2> Quaternion Neural Network </h2>
When dealing with multi-channelinputs  (e.g.,  color  images), 
the  convolution  kernels  merges  these  channels  by summing up the convolution results and output one single channel per kernel accordingly.
Although  such  a  processing  strategy  performs  well  in  many  practical  situ-ations,  
it  congenitally  suffers  from  some  drawbacks  in  color  image  processing tasks. Firstly, for each kernel it just sums up the outputs corresponding to dif-ferent channels and ignores the complicated interrelationship between them. 
Ac-cordingly, we  may  lose  important  structural  information  of  color  and  obtainnon-optimal  representation  of  color  image.  Secondly,  simply  summing  upthe outputs gives too many degrees of freedom to the learning of convolutionkernels, and thus we may have a high risk of over-fitting even if imposing heavyregularization  terms. 
How  to  overcome  these  two  challenges  is  still  not  fully-investigated.

<h2> Project Overview </h2>
In this work we replicate the work and approach discuss in this paper to build the <b>QCNN</b> which is also called <b> Quaternion Neural Network </b>.
We use Encoder decoder approach as well as instead of doing the normal convolution, we perform the Quaternion convolution where Convolution in the quaternion domain is done by convolving quaternion  filter <img src="http://www.sciweavers.org/upload/Tex2Img_1608651260/render.png" alt="alt text" width="200" height="50"/> by a quaternion vector <img src=""/>
