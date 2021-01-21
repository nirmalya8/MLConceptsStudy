# MLConceptsStudy

# Curve Fitting
Polynomial Curve fitting has been conducted. We have used a synthetically prepared a dataset based on the sine function, adding some random noise to each datapoint. So, the actual function will be a bit different from sin x.
We have considered a polynomial to be of the form :
$$ yhat = w_0 +w_1 x^1+w_2x^2+ \dots + w_nx^n $$
Based on this, we fitted a curve of degree 3 based on the mean squared loss function using the Gradient Descent Optimizer.
