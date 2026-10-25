# IS362 Week 8 Assignment on Vehicles 

**Precious Brown** 

IS362 Data Acquisition and Management 

## About My Assignment

For this assignment, I worked with the Auto MPG dataset. I cleaned up the missing horsepower values and made three charts to look at things such as cylinders, horsepower, weight, and MPG. I utilized purple within my visuals to help with distinction. 

## Files 

*`PBrownIS362Week8.ipynb`: this Python notebook contains my code, charts, and explanations.

* `PBrownIS362Week8.docx`: this file contains my written report and screenshots. 

## Working With the Data 

I replaced the question marks within the horsepower column with NaN instead of zero. In my opinion, zero would not make sense here because the horsepower measurement was missing but not actually zero. By including values of 0, it would throw off the actual data. I also converted the column to numeric values. 

I also changed the origin numbers to labels as directed within the assignment objective. 

## What I Noticed
Cars with 4, 6, and 8 cylinders appeared more often than those with 3 or 5 cylinders. 4 cylinder vehicles held the highest count.

For the horsepower and weight chart, I used different shades of purple to show the cylinder counts. ounce. The eight cylinder vehicles were mostly located in the upper right area of the graph.

My last chart looked at whether heavier cars had lower MPG. There was a downward trend, although the cars did not all follow the same pattern. While these graphs show relationships, they do not prove that one thing causes the other. 

## Running the Notebook
Open the notebook in Google Colab, or Jupyter Notebook and run the cells from the tp to bottom.

The code uses pandas, matplotlib, and seaborn. **YOU WILL NEED AN INTERNET CONNECTION** because the dataset loads from the UCI website. 

## Source 
Auto MPG dataset
UCI Machine Learning Repository 

https://doi.org/10.24432/C5859H
