# BroadCF: A new neural network-based recommendation framework.

In this paper, we have proposed a new neural network based recommendation framework called Broad Collaborative Filtering (BroadCF). Compared with the existing DNNs-based recommendation algorithms, the proposed BroadCF model is also able to capture the nonlinear relationship between users and items, and hence generate very satisfactory recommendation performance. However, the superiority of BroadCF is that it is very efficient compared with the DNNs-based methods, i.e., it consumes relatively very short training time and only requires relatively small amount of data storage, in particular trainable parameter storage. The main advantage lies in designing a data preprocessing procedure to convert the original rating data into the form of (Rating collaborative vector, Rating one-hot vector), which is then feed into the very efficient BLS for rating prediction.

Please cite our paper if you use our codes. Thanks! 

BroadCF (Broad Collaborative Filtering) is one of the BroadRS algorithms, a series of recommendation algorithms based on broad learning system (BLS). It is developed by BroadRS Research Team formed by SCAU, SYSU and SCUT.

# Environment Settings
We are using python 3.8.8 for development

# Example to run the codes
The instruction of commands has been clearly stated in the codes .

Run BroadCF:
```python
python init.py --dataset ml-la
```
# Dataset
We provide six processed datasets: MovieLens 1 Million (ml-1m), A-DigitalMusic, A-Grocery-and-Gourmet-Food, A-Patio-Lawnand-Garden, A-Automotive,and A-Baby.
