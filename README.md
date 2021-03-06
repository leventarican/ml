# Machine Learning
* based on Hans-On Machine Learning with Scikit-Learn & Tensorflow; Aurelien Geron, O'Reilly; First Release

## create environment / workspace
* we'll use a virtual environment with: 
```
pip3 install --user --upgrade virtualenv
```
* create isolated python environment with: 
```
virtualenv env
```
* activate environment __everytime when use it__: 
```
source env/bin/activate
```
* now install all required modules with: 
```
pip3 install --upgrade jupyter matplotlib numpy pandas scipy scikit-learn
```
* check installation with: 
```
python3 -c "import jupyter, matplotlib, numpy, pandas, scipy, sklearn"
```
* fire up Jupyter [localhost:8888 will open in browser] with: 
```
jupyter notebook
```

## Training Models
* Linear Regression 
* Gradient Descent
* Polynomial Regression
* Learning Curves
* Regularized Linear Models
* Logistic Regression
