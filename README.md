# Style-Transfer-karan

## Problem Statement 
- Objective is to apply the style of an image, which we will term as "style image" to a target image while preserving the content of the "target image". 

## Content Image - 
![input-style](japanese_garden.jpg)


## Style Image - 
![input-style](picasso_selfportrait.jpg)


## Generated output image - 
![output](combinaton_image.png)

<br><br>
## Procedure followed - 
- So as I read the problem statement I knew about CNN, Depp Learning, and computer vision but I did not know specifically about the style transfer.
- By looking at what this Style transfer is I was very excited to learn and work on it.
- So I started by reading some articles about the Style transfer then after knowing it I read the research paper that introduces the Style transfer using CNN.
- I learned a lot about how we can use the pretrained models like VGG16, VGG19 to solve this problem.
- I was aware about the tranfer learning so I have also tried other predefined models like Densenet, etc but they took significantly more time than VGG16 and the results were also poor as compare to VGG results.
- So at the end I choose to stick with the VGG model.
- In deep learning one of the most important thing is to choose the right hyperparameters. 
- After some experimenting, I selected the weights that gave the best output according to me.

<br><br>
## References - 
- To understand the concept and write code for this problem I have taken help from this resources.
<br><br>

1 -  Neural Style Transfer: Creating Art with Deep Learning using tf.keras and eager execution<br>
Link - https://medium.com/tensorflow/neural-style-transfer-creating-art-with-deep-learning-using-tf-keras-and-eager-execution-7d541ac31398
<br><br>

2 - Neural style transfer<br>
Link - https://www.tensorflow.org/tutorials/generative/style_transfer
<br><br>

3 - A Neural Algorithm of Artistic Style Research paper <br>
Link - https://arxiv.org/abs/1508.06576
<br><br>

4 - Artistic Style Transfer with Convolutional Neural Network <br>
Link - https://medium.com/data-science-group-iitr/artistic-style-transfer-with-convolutional-neural-network-7ce2476039fd
<br><br>

5 - Perceptual Losses for Real-Time Style Transfer and Super-Resolution Research paper <br>
Link - https://arxiv.org/abs/1603.08155
