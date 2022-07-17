# Challenge-16-_Amazon_Vine_Analysis

<p align="center">
  <img src="https://github.com/LindsayTeeters/Challenge-16-_Amazon_Vine_Analysis/blob/main/Resources/amazon%20vine%20program.jpg">
</p>

## Overview of Analysis

The Amazon Vine program is a service that allows manufactures dn publishers to receieve reviews for their products. Sellby requested our help on analyzing Amazon reviews written by the members of the Amazon Vine program. These reviewers are paid to review products and publish their reviews to Amazon. These reviews are then displayed in the review section of each of the products on Amazon. Sellby asked us to pick one of the categories to analysize. Tools we utilized within this challenge was: googlecolab, AWS RDS, PySpark, and SQL. We used these to extract, transform, and analyize our dataset to provide a summary to Sellby Stakeholders. 

-----------------------------------------------------------------

## Results (For the Pet Supply Review Dataset) 

![PetSupplyReviewDF](https://github.com/LindsayTeeters/Challenge-16-_Amazon_Vine_Analysis/blob/main/Resources/PetSupplyReviewWhole%20Table.png)

The first thing that was need was to read the dataset and show the dataframe within a table. This was the starting to point to gather the needed data for the analysis. Once this was complete we could look at start to change and filter the table for the questions that we needed to anwser. Sellby Stakeholders wanted to know:
  - Question 1: How many Vine reviews and non-Vine reviews were there?
  - Question 2: How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - Question 3: What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?


<b>Question 1</b> <i> How many Vine reviews and non-Vine reviews were there? </i>

![Vine Review Sum](https://github.com/LindsayTeeters/Challenge-16-_Amazon_Vine_Analysis/blob/main/Resources/Vine%20Reviewed%20Summary.png)
The image above shows us the summary dataframe for vine reviews. Their were 170 vine reviews for the selected petsupply dataset.
