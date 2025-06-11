Rock vs Mine Prediction using Machine Learning

This project is built to classify sonar signals as either rocks or mines using a machine learning model. It was developed as part of my AI/ML learning journey during the AICTE–Microsoft Edunet Virtual Internship.

Problem Statement

In underwater environments, sonar signals are used to detect objects. However, distinguishing between a rock and a mine can be quite challenging. A misclassification could lead to serious consequences. The goal of this project is to automate this detection using a simple machine learning model trained on real sonar data.

Objective

The main aim is to create a machine learning model that can take sonar signal readings and predict whether the object is a rock or a mine. This is useful in marine defense, safety systems, and automated navigation.

Dataset Information

The dataset used is the Sonar dataset from the UCI Machine Learning Repository. It contains 208 records, each with 60 numerical features representing the strength of sonar signals reflected off different objects. The output label is either "R" for rock or "M" for mine.

Dataset source:
https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks)

Technologies and Tools Used

Python

Pandas

NumPy

scikit-learn

Google Colab

How the Model Works

First, the sonar data is loaded and explored using pandas.

Then the dataset is split into training and testing sets.

I used the Logistic Regression algorithm from scikit-learn to train the model.

After training, the model is tested on unseen data to check accuracy.

I also added a part where users can input custom values to get predictions.

Results

The model gives around 83% accuracy on test data, which is good considering the limited size and noise in sonar data. It correctly predicts most of the test values and provides immediate output when custom input is given.

Project Files

rock_vs_mine_prediction(ml_project).py – The main Python code

sonar data.csv – Dataset file

AICTE PROJECT.pptx – My submitted internship project report

README.md – This file

Future Scope

Trying different models like Random Forest, SVM, or Gradient Boost

Adding a web interface using Streamlit or Flask

Exploring deployment on Microsoft Azure or other cloud platforms

Including data visualization to make the model more user-friendly

About Me

I’m Sreenandan Kavuri, currently pursuing B.Tech in Computer Science at GITAM University. I'm passionate about AI/ML and have been working on projects to gain more hands-on experience. This project helped me apply the concepts I learned in the internship and build something practical.

If you'd like to contact me:
Email – kavurisreenandan97@gmail.com

References

UCI Sonar Dataset

scikit-learn documentation

Python Official Docs

Microsoft Learn AI Fluency modules
