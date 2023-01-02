# Password-project

**Project Description:** This was a class project. The prompt was to look for data online that we could use to implement code and create a product that we would need to pitch to our professor(Like Shark Tank). The presentation is the **Final Presentation.pdf** for the product proposal (this explains the idea overall). While the summary of the other files is below:   

**data.csv:** The AI-generated password strength score (scored as 0, 1, 2). I reduced the data as it was too much. https://www.kaggle.com/datasets/bhavikbb/password-strength-classifier-dataset - Source for data used.  

**passcheck.py:**  This file contains a class and an inheritance class. They have functions that check for the strength of a password strength status and determine if it is weak, medium, or strong. 

**password.py:** imports the passcheck.py module to allow the use of class functions and const variables (for encryption). The file opens the data.csv file, reads it, and outputs pass_strength.txt. Then it takes the user input of the password, returns the strength status, and asks if they want to encrypt or not.  

**pass_strength.txt:** is the output file. I created three categories (weak, medium, and strong) instead of the original (0, 1, and 2) to help users understand the strength of their passwords. 
