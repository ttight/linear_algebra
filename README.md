
# Computational Linear Algebra Use Cases

In this repo, I'll be showing a few use cases built out using Linear Algebra techniques to solve real world problems in Python projects. 


## Projects

- Number recognition using clustering in Principal Component Analysis
- Jordan Form Calculation witout existing libraries





### Number Recognition

In this project I wanted to show an example of how PCA is used to recognize/classify images. To do this, I use a training set of many black and white 20x20 pixel images of hand drawn numbers. Then, I use PCA to map these images to a 2 dimensional plane. By doing this I then use various clustering classification methods to find clusters of points on the 2d grid that map to the same image. Then we test out the PCA & clustering algo to attempt to predict which numbers new pictures represent. In this prohect, I was able to obtain a ~90% accuracy rating. Below is an example of a few images mapped onto a 2d plane. 
![Screen Shot 2023-06-04 at 4 51 55 PM](https://github.com/ttight/linear_algebra/assets/78621047/55c6d9b9-418a-4604-8f1b-597ed9cbbe46)

### Jordan Form Calculation

I create a function to calculate the Jordan form (P & J Matrices) for an inputted 2x2 matrix without libraries that would overly simplify this. This shows the logic of the Jordan form calculation process directly through python logic. 

### Linear Transformations on Elipses

Python function to apply linear transformations on small matrices. In the specific example the elipse used is $(x, y) | 3x^2 - 2xy + 3y^2 = 4$, where we rotate the given elipse using the function and show the effect of different inputs. Below is an example of the linear transformation: 

$$ 
\mathbf{X}_1 = \begin{pmatrix}
x_{1,1}\\
\vdots\\
x_{N,1}
\end{pmatrix} \mbox{ and }
\mathbf{X}_2 = \begin{pmatrix}
x_{1,2}\\
\vdots\\
x_{N,2}
\end{pmatrix}
$$
