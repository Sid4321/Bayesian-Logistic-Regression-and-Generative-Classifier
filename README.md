I have implemented a Bayesian Logistic Regression Model for classification as well as a Probabilistically Generative Classifier in numpy from scratch. **No ML Libraries (Pytorch/Tensorflow) were used**  
First I trained using maximum likelihood and optimized the error function using iterative reweighted least squares (IRLS).  
Then i trained two models:  
1) Bayesian Logistic regression Model with a Gaussian prior over the weights. The posterior distribution was approximated to be a Gaussian using the Laplace Approximation.  
The predictive distribution was also approximated. Parameters were again optimized via IRLS.  
2) Probabilistically Generative model was implemented using Gaussian class conditional densities with a shared covariance matrix  
