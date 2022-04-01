# machinelearning
Adversarial Learning for Constrained  Image Splicing Detection 


With the rise of digital technology, digital image has gradually taken the place of the 
original analog photograph, and the forgery of digital image has become more and more 
easy and indiscoverable. Image splicing is a commonly used technique in image 
tampering. Digital images have become a dominant source of information and means of 
communication in our society. However, they can easily be altered using readily 
available image editing tools. In this paper, we propose a new blind image forgery 
detection technique which employs a new backbone architecture for deep learning 
which is called ResNet-conv. ResNet-conv is obtained by replacing the feature pyramid 
network in ResNet-FPN with a set of convolutional layers. This new backbone is used to 
generate the initial feature map which is then to train the Mask-RCNN to generate 
masks for spliced regions in forged images. The proposed network is specifically 
designed to learn discriminative artifacts from tampered regions. Two different ResNet 
architectures are considered, namely ResNet-50 and ResNet-101. The ImageNet, 
He_normal, and Xavier_normal initialization techniques are employed and compared 
based on convergence. To train a robust model for this architecture, several postprocessing techniques are applied to the input images. The proposed network is trained 
and evaluated using a computer-generated image splicing dataset and found to be more 
efficient than other techniques.
