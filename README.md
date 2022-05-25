## Classifying Traffic Images

In this notebook, I classify traffic images as 'accident', 'dense_traffic', 'fire', or 'sparse_traffic.' 

The data can be found here: https://github.com/OlafenwaMoses/Traffic-Net. It consists of 4400 .jpg images of traffic, evenly distributed among the four classes. 

I use a number of techniques to classify the images, including a simple dense network, a convolutional neural network, and transfer learning. I also experiment with data augmentation and dropout. 

Using accuracy to evaluate my models, I achieve the following results: 

| Model                                  | Accuracy | 
| :----                                  |    ----:   |
| Baseline (random)                      | .25       | 
| Dense Net                              | .4        |
| CNN                                    | .67        |
| CNN with dropout & data augmentation   | .78        |

To code this notebook, I relied heavily on the instruction provided in the book *Deep Learning with Python, Second Edition* by François Chollet.
