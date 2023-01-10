# Console-Finances

# Unit 4 Challenge: Console Finances

## Overview

In this challenge, you'll be using the concepts you've learned to complete the required activity. This activity presents a real-world situation in which your newfound JavaScript skills will come in handy. You are tasked with creating code for analyzing the financial records of a company. You have been provided with a financial dataset in the `starter/index.js` file.

## Instructions

1. Create a new GitHub repo called `Console-Finances`. Then, clone it to your computer.

2. Copy the starter files in your local git repository.
   
You have been given a dataset composed of arrays with two fields, Date and Profit/Losses.

Your task is to write JavaScript code that analyzes the records to calculate each of the following:

* The total number of months included in the dataset.

   // TODO
   //count up how many things are in the array
   //array.length
   //Need a variable to store the value of array.length


* The net total amount of Profit/Losses over the entire period.

  //TODO
  //Adding up the money
  //keep a rolling total
  //Need a variable to store the rolling total
  //for loop to iterate over the array
  //Inside that for loop,access position 1 of each array element to get the numbers


* The average of the **changes** in Profit/Losses over the entire period.
* (`Total/Number of months`)

  //TODO
  //Total up the differences between each pair of adjoining months & divide by number of array elements
  //For loop starting with 1 = 1
  //Each iteration, subtract the data at position [1] of the previous element from the data at position[1] of the current element
  //Put that data into a new array variable 
  //So, we need to arr.push() each new 'change' value to the new array

  //Add up the total in the new 'changes' array
  //Need a variable to store the rolling total for this array that's different that the rolling total of profits
  //for loop to iterate over the changes array
  //add each element in turn to the rolling total
  //Take that 'total changes amount' variable and divide it by the number of elements in the array
  //Look up how to limit the answer to two decimal points
  * You will need to track what the total change in profits are from month to month and then find the average.
  

* The greatest increase in profits (date and amount) over the entire period.

* The greatest decrease in losses (date and amount) over the entire period.

When you open your code in the browser your resulting analysis should look similar to the following:

  ```text
  Financial Analysis
  ----------------------------
  Total Months: 25
  Total: $2561231
  Average  Change: $-2315.12
  Greatest Increase in Profits: Feb-2012 ($1926159)
  Greatest Decrease in Profits: Sep-2013 ($-2196167)
  ```

Your final code should print the analysis to the console.

**Hints:**

* You will need to do some research on your own for this project!

* Remember, in order to combine strings and variables in the console you will need to use **concatenation**.

* How do you only print to the nearest 100th in JavaScript?

## Grading Requirements

This homework is graded based on the following criteria: 

### Technical Acceptance Criteria: 40%

* Satisfies all of the above acceptance criteria.

### Deployment: 32%

* Application deployed at live URL.

* Application loads with no errors.

* Application GitHub URL submitted.

* GitHub repository contains application code.

### Repository Quality: 12%

* Repository has a unique name.

* Repository follows best practices for file structure and naming conventions.

* Repository follows best practices for variable naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages.

* Repository contains quality readme with description, screenshot, link to deployed application.

## Review

You are required to submit BOTH of the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository that contains your code. Give the repository a unique name and include a README file that describes the project.

---

## Copyright

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.

## Description

## Screenshots

## Link to deployed app
https://github.com/sumbal28/Console-Finances
