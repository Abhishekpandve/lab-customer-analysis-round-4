![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Customer Analysis Round 4

In today's lesson we talked about continuous distributions (mainly normal distribution), linear regression and how multicollinearity can impact the model. In this lab, we will test your knowledge on those things using the same data file that you have used in the previous lab (round 3). You can continue using the same Jupyter notebook.

### Get the data 

Use the jupyter file from the last lab (Customer Analysis Round 3) 
- You do NOT need to fork and clone this lab.

### Complete the following task 

- Check the data types of the columns. Get the numeric data into a dataframe called `numerical` and categorical columns in a dataframe called `categorical`.
(You can use np.number and object to select the numerical data types and categorical data types respectively)
- Now we will try to check the normality of the numerical variables visually
  - Use seaborn library to construct distribution plots for the numerical variables
  - Use Matplotlib to construct histograms
  - Do the distributions for different numerical variables look like a normal distribution?
- For the numerical variables, check the multicollinearity between the features. **Please note** that we will use the column `total_claim_amount` later as the target variable. 
- Drop one of the two features that show a high correlation between them (greater than 0.9). Write code for both the correlation matrix and for seaborn heatmap. If there is no pair of features that have a high correlation, then do not drop any features
