## PCA vs B-splines dimension reduction in a fashion data set

**Project description:** I've been recently learning about regularization methods paired with dimensionality reduction algorithms like PCA and B-splines and when 
I found this collection of images intended as a substitute to the MNIST handwritten digits used extensively in the Data Science community, I wanted to try to apply these algorithms to classify them comparatively.
The Fashion-MNIST is a dataset of Zalando's article images. Each example is a 28 x 28 grayscale image, associated with a label of 10 classes. Learn more about this dataset from Kaggle [here](https://www.kaggle.com/zalando-research/fashionmnist?select=fashion-mnist_train.csv).

### 1. Dimensionality Reduction and Regularization.
When presented with a data set that has many dimensions it becomes difficult to process it but high-dimensional data usually has a low dimensional structure. Hence, the relevant information is contained in fewer dimensions that can be extracted to conduct further analysis, the rest are treated as non-informative and noise. One common approach to dimensionality reduction is Principal Component Analysis (PCA), which transforms the original data projecting it onto a set of orthogonal axes.

Another approach is to try fitting a polynomial regression using splines which are linear combinations of piecewise polynomial functions.

Regularization can help adjust model complexity to avoid overfitting. One such form of regularization, the LASSO (Least Absolute Shrinkage and Selection Operator) shrinks large coefficients and truncates small coefficients to zero.

To compare both methods, I used B-splines with 10 knots to reduce dimensionality and then applied LASSO regularization. Similarly, I applied Principal Component Analysis and kept the 12th largest eigenvectors to do a LASSO regularization with them. The following plots show the regularization for the reduced coefficients on each algorithm and for the first response value. 

You can find the R code [here]

```javascript
if (isAwesome){
  return true
}
```

### 2. Assess assumptions on which statistical inference will be based

```javascript
if (isAwesome){
  return true
}
```

### 3. Support the selection of appropriate statistical tools and techniques

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).