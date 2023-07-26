Introduction:

  Platforms that aggregate user content are the foundation of knowledge sharing on the internet Blogs, forums, discussion boards, and, of course, Wikipedia. But the catch is that not all people on the Internet are interested in participating nicely, and some see it as an avenue to vent their rage, insecurity, and prejudices. The problem with this is that people will frequently write things they shouldn’t, and to maintain a positive community this toxic content and the users posting it need to be removed quickly. But they don’t have the resources to hire full-time moderators to review every comment. The project will be done with Python and colab notebooks,



Literature review:

   The Kaggle challenge based on this dataset uses ROC/AUC, or the area under a receiver operating characteristic curve, to evaluate submissions. This is a very generous metric for the challenge, as axes for the curve represent recall (a.k.a. sensitivity), the ratio of positive predictions to all samples with that label, and specificity, the ratio of negative predictions to all negative samples. This metric would work well if the positive and negative labels were relatively even, but in our case, where one label represents less than a third of a percent of the data, it’s too easy to get a high score even with hardly any true-positive predictions.
Used libraries:

Pandas &NumPy: Pandas is an open source Python package that is most widely used for data science/data analysis and machine learning tasks. It is built on top of another package named NumPy, which provides support for multi-dimensional arrays. As one of the most popular data wrangling packages, Pandas works well with many other data science modules inside the Python ecosystem, and is typically included in every Python distribution, from those that come with your operating system to commercial vendor distributions like Active State’s Active Python.
NumPy can be used  for performing numerical operations in wide range. NumPy (Numerical Python) is an open source Python library that’s used in almost every field of science and engineering. and it’s at the core of the scientific Python and PyData ecosystems.NumPy users include everyone from beginning coders to experienced researchers doing state-of-the-art scientific and industrial research and development.
TensorFlow:
TensorFlow is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML powered applications.
The dataset has been trained from Kaggle and mentioned as ml_data. Dataset was related to toxic comments in Kaggle .
Gradio:
The GUI  interface to get output.

Dataset :
      https://www.kaggle.com/datasets/julian3833/jigsaw-unintended-bias-in-toxicity-classification

Proposed methodology:


Workflow of  the project:
1.  Installing and importing the required libraries.

2.  Uploading data set using Google drive.

3.  Pre-processing dataset using Text vectorization which converts text to numeric representation.

4.  Building a deep learning model for the task.

5.  Feeding the training data to the model using model.fit() command.

6.  Analysing the trained model’s performance by feeding validation data to the trained model.

7.  Plotting accuracy and loss scores of the model for visual representation of the model’s performance.

8. Making Predictions on custom input.

9. Adding gradio’s GUI to make the project easy to use for everyone.

EPOCHS USED 1

159571 





