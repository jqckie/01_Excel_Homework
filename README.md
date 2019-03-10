# KickStart My Chart

## Instructions

* Open [StarterBook_Solved_JSC.xlsx](StarterBook_Solved_JSC.xlsx) to view the raw data and summary charts on each tab
* Open [Unit_1_Summary_JSC.docx](Unit_1_Summary_JSC.docx) to view the report summarizing observed trends

## Background

* Organizing and analyzing a database of four thousand past Kickstarter projects to uncover any hidden trends.

## Details

* Modifying and analyzing the data of four thousand past Kickstarter projects to uncover some of the market trends.

* Using conditional formatting to fill each cell in the `state` column with a different color, depending on whether the associated campaign was "successful," "failed," "cancelled," or is currently "live".

* Creating a new column at column O called `percent funded` that uses a formula to uncover how much money a campaign made towards reaching its initial goal.

 * Using conditional formatting to fill each cell in the `percent funded` column using a three-color scale. The scale starts at 0 with a dark shade of red, transitioning to green at 100, and then moving towards blue at 200.

* Creating a new column at column P called `average donation` that uses a formula to uncover how much each backer for the project paid on average.

* Creating two new columns, one called `category` at Q and another called `sub-category` at R, which use formulas to split the `Category and Sub-Category` column into two parts.

  * Creating a new sheet with a pivot table that will analyze your initial worksheet to count how many campaigns were "successful," "failed," "cancelled," or are currently "live" per **category**.

    * Creating a stacked column pivot chart that can be filtered by `country` based on the new table.

  * Createing a new sheet with a pivot table that will analyze your initial sheet to count how many campaigns were "successful," "failed," "cancelled," or are currently "live" per **sub-category**.

    * Creating a stacked column pivot chart that can be filtered by `country` and `parent-category` based on the new table.

* Converting the dates stored within the `deadline` and `launched_at` columns, and creating new columns named `Date Created Conversion` and `Date Ended Conversion`.

  * Creating a new sheet with a pivot table with a column of `state`, rows of `Date Created Conversion`, values based on the count of `state`, and filters based on `parent category` and `Years`.

  * Creating a pivot chart line graph that visualizes this new table.

* Creating a summary report in Microsoft Word to answer the following questions...

1. What are three conclusions we can make about Kickstarter campaigns given the provided data?
2. What are some of the limitations of this dataset?
3. What are some other possible tables/graphs that we could create?

* Creating a new sheet with 8 columns: `Goal`, `Number Successful`, `Number Failed`, `Number Canceled`, `Total Projects`, `Percentage Successful`, `Percentage Failed`, and `Percentage Canceled` with the following headers in the `goal` column:

    * Less Than 1000
    * 1000 to 4999
    * 5000 to 9999
    * 10000 to 14999
    * 15000 to 19999
    * 20000 to 24999
    * 25000 to 29999
    * 30000 to 34999
    * 35000 to 39999
    * 40000 to 44999
    * 45000 to 49999
    * Greater than or equal to 50000

  * Counting how many successful, failed, and canceled projects were created with goals within those ranges listed above and populating the `Number Successful`, `Number Failed`, and `Number Canceled` columns with this data.

  * Adding up each of the values in the `Number Successful`, `Number Failed`, and `Number Canceled` columns to populate the `Total Projects` column then finding the percentage of projects which were successful, failed, or were canceled per goal range.

  * Creating a line chart which graphs the relationship between a goal's amount and its chances at success, failure, or cancellation.
