## About Dataset

### Introduction

This is a csv file containing related information of 5172 randomly picked email files and their respective labels for spam or not-spam classification.

### About the Dataset

The csv file contains 5172 rows, each row for each email. There are 3002 columns. 
* The first column indicates *Email name*. The name has been set with numbers and not recipients'name to protect privacy. 
* The last column has the labels for prediction : 1 for spam, 0 for not spam. 
* The remaining 3000 columns are the 3000 most common words in all the emails, after excluding the non-alphabetical characters/words. For each row, the count of each word(column) in that email(row) is stored in the respective cells. 

Thus, information regarding all 5172 emails are stored in a compact dataframe rather than as separate text files

![image](https://user-images.githubusercontent.com/61298021/164608910-1b5a94fc-6f54-49b0-9f03-573b4ae65821.png)

![image](https://user-images.githubusercontent.com/61298021/164608851-fbc4564e-3779-4507-ae61-5dc8b54efa4b.png)
