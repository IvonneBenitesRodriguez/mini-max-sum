**Hackerrank Challenge: Mini-Max Sum** <br/>
Given five positive integers, find the minimum and maximum values that can be calculated by summing exactly four of the five integers.<br/>
Then print the respective minimum and maximum values as a single line of two space-separated long integers.<br/>

Example:<br/>
arr = [1,3,5,7,9]<br/>
The minimum sum is 1+3+5+7=16<br/>
The maximum sum is 3+5+7+9=24<br/>

The function prints<br/>
16 24 

**Function Description**<br/>
Complete the miniMaxSum function in the editor below:<br/>
miniMaxSum has the following parameter(s):<br/>
arr: an array of 5 integers

**Print**<br/>
Print two space-separated integers on one line: the
minimum sum and the maximum sum of 4 of 5 elements.<br/>

**Input Format**<br/>
A single line of five space-separated integers.<br/>

**Constraints**<br/>
1<= arr[i] <= 10x9

**Output Format**<br/>
Print two space-separated long integers denoting the respective minimum and maximum values that can be calculated by summing exactly four of the five integers. (The output can be greater than a 32 bit integer.)<br/>

**Sample Input**<br/>
1 2 3 4 5

**Sample Output**<br/>
10 14 

**Explanation**<br/>
The numbers are 1, 2, 3, 4, and 5. Calculate the following sums using four of the five integers:<br/>

Sum everything except 1, the sum is 2+3+4+5=14.<br/>
Sum everything except 2, the sum is 1+3+4+5=13.<br/>
Sum everything except 3, the sum is 1+2+4+5=12.<br/>
Sum everything except 4, the sum is 1+2+3+5=11.<br/>
Sum everything except 5, the sum is 1+2+3+4=10.<br/>

**Task**<br/>
Complete the 'miniMaxSum' function below.<br/>
The function accepts INTEGER_ARRAY arr as parameter.<br/>

