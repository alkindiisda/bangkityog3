# Email Spam Classification
## bangkityog3

Assignment #05-W05-First Machine Learning Project - MLCC Project

Project Members:

*   Al Kindi Isda - alkindiisda@gmail.com
*   Bayu Dwi P - mr.ilhamtohari@gmail.com
*   Ilham Tohari - bayud40@gmail.com

![gaze](http://dontkry.com/images/repos/gaze.png)


#### Introduction

This is a csv file containing related information of 5172 randomly picked email files and their respective labels for spam or not-spam classification.

#### About the Dataset

The csv file contains 5172 rows, each row for each email. There are 3002 columns. The first column indicates Email name. The name has been set with numbers and not recipients' name to protect privacy. The last column has the labels for prediction : 1 for spam, 0 for not spam. The remaining 3000 columns are the 3000 most common words in all the emails, after excluding the non-alphabetical characters/words. For each row, the count of each word(column) in that email(row) is stored in the respective cells. Thus, information regarding all 5172 emails are stored in a compact dataframe rather than as separate text files.
