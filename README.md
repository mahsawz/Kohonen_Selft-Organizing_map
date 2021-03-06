# Kohonen_Selft-Organizing_map

A self-organizing map (SOM) or self-organizing feature map (SOFM) is a type of artificial neural network (ANN) that is trained using unsupervised learning to produce a low-dimensional (typically two-dimensional), discretized representation of the input space of the training samples, called a map, and is therefore a method to do dimensionality reduction. Self-organizing maps differ from other artificial neural networks as they apply competitive learning as opposed to error-correction learning (such as backpropagation with gradient descent), and in the sense that they use a neighborhood function to preserve the topological properties of the input space.

This makes SOMs useful for visualization by creating low-dimensional views of high-dimensional data, akin to multidimensional scaling. The artificial neural network introduced by the Finnish professor Teuvo Kohonen in the 1980s is sometimes called a Kohonen map or network.

Here, I train a Kohonen’s Self-Organizing Feature Map (SOFM) which can map a dataset of 3- Dimensional data into a 2-Dimensional space.

First, I create 1600 colors in RGB space randomly. All Red, Green, and Blue values must be between 0 and 255. Then feed this dataset of 3D data to the network and represent it into a 40x40 map of nodes, which can be shown as a picture with height and width of 40 pixel.

<img src="https://github.com/mahsawz/Kohonen_Selft-Organizing_map/blob/main/input-image.png" width="200" height="200">

The goal is to take the 3D color vectors and map them onto a 2D surface in such a way that similar colors will end up in the same area of the 2D surface.

<img src="https://github.com/mahsawz/Kohonen_Selft-Organizing_map/blob/main/result-image.png" width="200" height="200">
