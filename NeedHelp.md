1) Stable Sorting - [Merge Overlapping Intervals](https://www.interviewbit.com/problems/merge-overlapping-intervals/)  
   Issue - I have approached the problem by the property of stable sort, however resultant order is not as expected  
   in the given test case I noticed the ending 100(of interval) precedes the starting 100 in the array of events  
   that is why my code fails but can't why the ending 100 comes first at all.
   [Approach and code](https://paste.ubuntu.com/p/YqKYSsbzDG/)  
   Code fails for test case -> 2   100 100   2 99 ,Output is 2 99, Expected output is 2 99 100 100
