# console-finance

 Psedueo code to complete help comple the challenge:

/// The total number of months included in the dataset.
//find out length of finances array 

///  The net total amount of Profit/Losses over the entire period.
//  loop through the finances array and get the value of the profit/losses by accessing it manually
//  var total = 0
//  for i in finances
//  total = total + finances[i][1]

/// The average of the changes in Profit/Losses over the entire period.
// create new array called it financeChanges to store changes for each months
// loop finances array and calculate the changes
// for i in finances
//   var profitLosses = finances[i][1]
//   financeChanges.push(finances[i+1][1] - finances[i][1])
// Be careful on the last month finances[i+1] will not exist!
// find out the length of financeChanges array
// Calculate the total changes using the same method as the previous question
// Calculate the average

/// The greatest increase in profits (date and amount) over the entire period.
// var highestEarning = 0
// for i in financeChanges
//   compare financeChanges[i] with highestEarning
//   if financeChanges[i] > highestEarning then replace highestEarning with financeChanges[i]
// Or use Math.max() for the amount, or sort from highest to lowest and get the value of the first index
// how about the date?
// Find the index of the maximum element in financeChanges array
// get the month from finance array with the same index that we have found

/// The greatest decrease in losses (date and amount) over the entire period.
// Google "how to find minimum value of an array in javascript"