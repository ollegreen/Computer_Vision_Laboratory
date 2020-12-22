# The Computer Vision Lab

*Let's get down and dirty with CL using some popular frameworks on the same task and see how they differ.* 

![dl](https://miro.medium.com/max/2800/1*oDGkw6DWbYLiaFmFHGABaA.png)

## Info
- This is a repo to explore different deep learning models and their use-cases. 
- No copy pasting from other repos, only dirty code that you built yourself.
- **Trial & Error is the key concept here.**
- ```Goal:``` Be able to build these models from scratch in Keras, PyTorch or Tensorflow and apply it to fun problems 

<br/>

### Libraries we will check out
- **PyTorch** -- Based on recommendation, this seems to be the most prominent one on kaggle competitions and real life applications. However, it seems to have a steep learning curve, but my plan is to start with PyTorch and then proceeding to tensorflow 2.0 and finally keras, would make it easier to understand the TF and Keras as they seem to be a bit easier to digest than PyTorch. 
- **Tensorflow 2.0** -- TF2 (not the game ;)) seems to be the next area worth diving into for CV Neural Nets. 
- **Keras** 

<br/>

## TO-DO:
* ```Fundamentals``` Start with getting the theoretical fundamentals of pytorch before going into the easier ones --> Tensorflow and Keras. 
* ```Choosing correct models``` Emphasise when to use clustering, decision trees etc - https://dzone.com/articles/decision-trees-vs-clustering-algorithms-vs-linear
* ```Clustering vs CLassification``` - https://www.geeksforgeeks.org/clustering-in-machine-learning/
* ```Testing``` Test the libraries on simple applications to get familiar with how they work. 
* ```First Ambitious Project``` Pushup cv = reward, when you do 30 pushups in front of the ML-camera -> you get a reward https://youtu.be/x31c9FYypOs

<br/>

![Pic](https://www.toolshero.com/wp-content/uploads/2018/02/to-do-lists-toolshero.jpg)

<br/>

# Concepts
## What is a tensor? 
In accordance with [datacamp](https://www.datacamp.com/community/tutorials/investigating-tensors-pytorch);

* **A Pytorch tensor is**:  a multi-dimensional matrix containing elements of a single data type.

* **How do we use the PyTorch Tensors?** Basically, Tensors are a type of data structure used in linear algebra, and like vectors and matrices, you can calculate arithmetic operations with tensors.

* **But how does calculating arithmetic operations help us build cool computer vision models and Deep Learning models?** Good Question! Let's break it down to what our task is in this video based scenario. **What actually is a video?** In a technical sense it is a lot of pictures combined into frames that then could for example result in a visual representation of what your kid looked like when he was swinging on the swing 10 years ago. Ok then let's break down what a picture is, a picture is basically if you zoom in enough, a lot of really small colored squares, which is what we call pixels. These small squares could be turned into for example mathematical matrices, but a single matrix with a 2D-grid of numbers. For example we can see two of them below;

![matrices](https://helloacm.com/wp-content/uploads/2019/11/matrix1.png)

Here we can realise that higher quality images, that contain a larger resolution, thereby more pixels, will take more calculations when we are dealing with this. The importance of how accurate these things will be will be case specific, for example I could imagine that healthcare could in some cases could maybe get better insight from analysing millions of pictures of human rashes, but this is pure speculation on my part.  

**Now here's the kicker**, so a common 2d matrix is the same as a 2-dimensional array, where as a tensor is a multidimensional array. Ok what does that tell us and how is that different from a regular 2D-array? 

![tensor](https://cdn-images-1.medium.com/max/2000/1*_D5ZvufDS38WkhK9rK32hQ.jpeg)

**In short**, tensors are the basic building block for certain machine learning and deep learning models. (Quick side-note: the popularity for tensors today, according to "David" on a stats forum; Tensor algorithms often lend themselves well to parallelism, which hardware (such as GPU accelerators) are increasingly getting better at). 

At its core, these **tensors are data containers**. Mostly it contains numbers. Sometimes it even includes strings, but that is rare. ***So think of it as a bucket of numbers.***



#### Now, next thing: *what are data structures?*

Basically;

1. Linear: arrays, lists, 
2. Tree: binary, heaps, space partitioning etc.
3. Hash: distributed hash table, hash tree etc.
4. Graphs: decision, directed, acyclic etc.


