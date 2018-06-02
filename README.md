# python-tensorflow

image classifier done in google's tensorflow.
Tensorflow is open source software library used for dataflow programming.It's also used for machine learning app such as neural network.

This project is about classifying dogs by breed. I made it only for four(4) breeds.

Main script is label_image. When you start that script you need to define a graph that is trained to recognize object on picture(in our case-dog), and you need to pass full adress of photo you want to test.

python -m scripts.label_image     --graph=tf_files/retrained_graph.pb      --image=/full/path/to/image.jpg

