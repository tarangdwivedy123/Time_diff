PROBLEM STATEMENT:

When we set alarms on our phones we see a small message showing the time left for the alarm to ring. If you sleep around 11PM, then you get a  message saying "Alarm set for 7 hours and 30 minutes from now." 

This problem is just like that message.

Given two alarm times (in 24-hour clock system) at any two points of a day, you need to find the difference between these points.

Input Format

The first line contains a single integer,t, denoting the number of test cases.
Each of the following test cases contains 2 lines with one time in each line
Constraints

Time is not guaranteed to be valid, in which case the output should be Invalid Input.
Both times are considered on the same day. So, 14:30 and 13:01 have a difference of 1 hour, 29 minutes only, and not 22 hours, 31 minutes.
Output Format

Time Difference in hours:minutes format, or Invalid Input.

Sample Input 0

2
22:20
23:60
23:15
15:45
Sample Output 0

Invalid Input
07:30
Explanation 0
For the first test case, 23:60 is invalid so we print Invalid Input.
For the second test case, 15:45 to 23:15 takes 7 hours and 30 minutes, so we print 07:30
