# FastNet
Official Repository for FastNet, An Efficient Convolutional Neural Network Architecture,  highly optimized for Edge Devices and Mobile Applications.

<a href="http://vixra.org/abs/1801.0192" >Read The Paper</a> for more details

In light of the great need for intelligence at the edge of smart devices including SmartPhones, IoT devices, Smart Cameras and low cost drones, we have developed a new architecture that archieves high accuracy on standard datasets while being incredibly fast on both GPUs and CPUs.
Recent Architectures have explored absolute depth, very great width and layer parallelization. We explictly avoid using any of these as they lead to models that can only be used on the cloud and are too slow and too large to be deployed on Smart Devices. We instead, make use of medium depth and medium width throughout the network and we greatly optimized the parameters of the network to archieve highly competetive accuracies at very low computational cost. Our architecture is also very simple and can be replicated by any ML engineer using any Deep Learning library.

<br>

<center><img src="https://github.com/johnolafenwa/FastNet/raw/master/model.png" width=300 /></center>

<h1>ACCURACIES</h1>

<h2>Number of Parameters: 1.6 Million</h2>
<h2>CIFAR 10 Accuracy: 93.98 %</h2>
<h2>CIFAR 100 Accuracy: 70.81 %</h2>

Our architecture completes 200 training epochs in just three hours, despite we were using real-time data augmentation and saving the models at every epoch while we conducted our experiments. Our experiments were conducted using keras with Tensorflow backend, running on a NVIDIA P100.

The scripts provided in this repository would complete 200 epochs is less than 3 hours, if run using the same environment. 




