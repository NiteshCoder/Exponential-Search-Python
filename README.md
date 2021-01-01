# Exponential-Search-Python

- Basically it is also use binary search.
- Doing work as per given name Exponential.
- Exponential means to find exponent of number. // exponent of 2 is 2,4,8,16,32.

Prerequisite :

- Data must be sorted.


Why Exponential search over Binary Searh ?

- So basically binary search is useful when data is bounded. 
	// Bounded means Small amount of data.
	
- And Exponential search used when data is Unbounded. 
	// Unbounded means Infinite.
	
Example. 
	
	Data is :
	5 10 15 20 25 30 35 40 45 50 55 60
	0  1  2  3  4  5  6  7  8  9 10 11   // ARRAY INDEX.
	
	- Search for 55.
Step 1 :
- Check first element Directly.
	 5 != 55 // False

Step 2 :
- Assign index=1.
	 data[1] = 10. // 10 <= 55 TRUE.

Step 3 :
- Find Exponent of 2.
	 // index = index * 2
	 // Now index is 2.
	 // data[2] = 15 
	 // 15 <= 55  TRUE.
	 
	 Again.
	 // index = index * 2
	 // Now index is 4
	 // data[4] = 25.
	 // 25 <= 55 TRUE
	 
	 Again.
	 // index = index * 2
	 // Now index is 8
	 // data[8] = 45.
	 // 45 <= 55 TRUE.
	 
	 Again.
	 // index = index * 20
	 // Now index is 16.
	 Here total length of data is 12.
	 // So 16 > 12   // FALSE.
	 
Step 4 : 
- Now send data from index 8 to 12 For Binary Search.

Step 5 :
- END.

#THANK YOU.
