# Formative Test 1

## Instructions

Please follow the directions below and submit your answers by 5pm EST, Thursday 5th of October

1. Download the [MITx/Harvardx MOOC dataset](https://dataverse.harvard.edu/file.xhtml?fileId=2468954&version=RELEASED&version=.0).

2. Fork and clone this repository to your computer and open it as a new project in RStudio

3. Open a new R Markdown file and save it to the repository with the filename `formative.rmd`. Inlcude all your code in the markdown document.

4. Upload the MITx/Harvardx dataset to R as a dataframe named `D1`(Please inlcude your code in your markdown document)

5. What does the `DI` suffix that is appeneded to two of the variable names mean?

6. How many people enrolled in HarvardX/CS50x recieved certification in 2012? (Please inlcude your code in your markdown document)

7. How many people registered for HarvardX/CS50x from Colombia on October 15, 2012? (Please inlcude your code in your markdown document)

8. Create a new data frame (`D2`) that includes student ID and registration date for all students from a country of your choice (Please inlcude your code in your markdown document)

9. Create a new data frame (`D3`) in which the column names are the registration dates, with one column containing the student ids and all other cells indicating a `1` if the student registered on that date or an `NA` if they did not (hint: you will need to create a new variable before you change the structure of your data frame)

10. Now make the row names of `D3` the student ids on your new data frame and remove the user id column from your data frame

11. Convert your data frame to a matrix (`M1`)

12. Create a new matrix which is the transposed version of your matrix (`M2`)

13. Create a third matrix (`M3`) that is a student by student matrix where the cells in the matrix represent if two studentes registered on the same day (This will take a lot of processing power, you may not be able to complete it if you have a large number of students)

14. Convert the diagonal of your matrix into `NA`s


