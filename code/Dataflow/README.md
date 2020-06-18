# wino_stream
Streaming architecture for winograd convolution

### Demo Video
[![Demo Video](https://img.youtube.com/vi/r0CQHH15nIY/0.jpg)](https://www.youtube.com/watch?v=r0CQHH15nIY)

### Block Diagram
![Block Diagram](/code/Dataflow/media/block_diagram.png)


# Lenet MNIST Results

### Neural Network Architecture
![Resources](/code/Dataflow/media/mnist_lenet/lenet_labelled.png)


### Without Slicer
![Resources](/code/Dataflow/media/mnist_lenet/resources_noSlicer.png)
##### FPS
	17.1k images/sec

### With Slicer
![Resources](/code/Dataflow/media/mnist_lenet/resources.png)
##### FPS
	22.2k images/sec but uses 28 more BRAMs

### Electric Sliding window
![Resources](/code/Dataflow/media/mnist_lenet/electric_slide.png)
##### FPS
	20.15k images/sec and slightly more resources than Xilinx sliding window



# CNV Cifar10 Results

### Neural Network Architecture
![Resources](/code/Dataflow/media/cifar10_cnv/cifar10_cnv.png)


### Without Slicer
![Resources](/code/Dataflow/media/cifar10_cnv/orig_smallest_footprint.png)
##### FPS
	573 images/sec



