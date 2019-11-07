Project: Unscramble Computer Science Problems
Review date: 11/07/2019

Task 0:

Good work! correctly prints the first row of the texts and last row of the calls.
Note:
You can also use format() as follows

print('First record of texts, {0} texts {1} at time {2}'.format(*texts[0])) and
print('Last record of calls, {0} calls {1} at time {2}, lasting {3} seconds'.format(*calls[-1]))

Task 1:
Great! Correct use of set for getting all unique value and len() to count total values.

Task 2:
Correctly fetches the phone number with the longest time spent on a phone.

Note:
Appreciate the use of max() built-in function to get the longest/maximum time spent.

Task 3:
All the area codes are fetched properly but we have to display them in sorted order.
You can use the sorted built-in function to sort the resultant set like print(\*sorted(phoneNumberCodes), sep='\n')

Task 4:
All the possible telemarketer numbers are fetched properly but we have to display them in sorted order.
You can used python built-in sorting function to do so like print(\*sorted(telemarketersCallslist), sep='\n')

Analysis.txt:

Unfortunately, we are not allowed to accept just the Big O as shown here. You should mention how you arrived at it by referring to critical parts of your implementation.
For Tasks 3 and 4, some fixes are required which affect the time complexity. Kindly analyzing it after fixing all the issues.
