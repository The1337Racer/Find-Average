With this repository it shows how you can find the three
averages of test score from three tests by using the python programming lanaguage. 
The code shows how the three test scores get added together
and then divided by three which then gives the user the 
avaerage score over the three tests.



# Find-Average
#Finding an average
# test1 , test2 and test3 variables.
test1 = float(input('Enter the first test score: '))
test2 = float(input('Enter the second test score: '))
test3 = float(input('Enter the third test score: '))

#calculate the average of the three scores
#and assign the result to the average variable
average = (test1 + test2 + test3) / 3.0

# display the average
print('the average score is', average)
