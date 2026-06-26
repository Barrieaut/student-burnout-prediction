# My School Project: Guessing Student Burnout from AI Hours

This is my homework assignment for class. I am using machine learning to help find out if a student is about to burn out or get too stressed, based on how much they use AI tools every week.

## What This Project Does
Our homework assignment is all about sorting data into groups (classification). I used a free dataset from Kaggle called **"Impact of AI on Students"** which has info on 50,000 different students. 

I split the students into two simple groups:
* **High Burnout Risk (1)**
* **Low Risk (0)**

Then, I tried out the two easiest models from our class slides to see which one does a better job:
* **Logistic Regression** (Got an 80% total score)
* **Decision Tree** (Got an 80% total score)

## Cool Patterns I Found in the Charts
* **Using AI:** Students who spend a lot of hours using AI every week have a big link (**0.47 score**) to high burnout. This means too much AI might be making them stressed!
* **Normal Studying:** Spending hours studying the old-fashioned way actually helps **lower** the risk of burning out (**-0.13 score**).

## How to Open and Run My Code

1. Find the file named `Assignment 8: Supervised Learning Classification.ipynb` here on GitHub and download it to your computer.
2. Go to the [Google Colab website](https://google.com) and upload my file there.
3. Click the play button on the very first code box. A button will pop up asking for the data file.
4. Upload the `ai_student_impact_dataset (1).csv` file from your computer. 
5. Run the rest of the boxes from top to bottom to see my charts and results!
