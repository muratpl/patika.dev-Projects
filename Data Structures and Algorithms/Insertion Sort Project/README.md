# Insertion Sort Project
[22,27,16,2,18,6] --> Insertion Sort

#### 1) Write the stages of the above sequence according to the sort type:

* min=2 --> swap 2 and 22 --> [2, | 27, 16, 22, 18, 6]
* min=6 --> swap 27 and 6 --> [2, 6, | 16, 22, 18, 27]
* min=16 --> no need to swap --> [2, 6, 16, | 22, 18, 27]
* min=18 --> swap 18 and 22 --> [2, 6 16 18 ,22, 27]

#### 2) Write the Big-O notation:

* Step 1 --> n 
* Step 2 --> n-1 
* Step 3 --> n-2 
* .... 
* Step n-1 --> 1

SUM = n+(n-1)+(n-2)+... --> n.(n+1)/2 => (n²+n)/2 => **O(n²)**

#### 3) Time Complexity 
* Average case: The number we are looking for is in the middle, 
* Worst case: The number we are looking for is at the end, 
* Best case: The number we are looking for is at the beginning of the series.

#### 4) What case does the number 18 fall into after the array is sorted? 
[2,6,16,18,22,27] --> Average case

#### 5) Write the first 4 steps of the X array according to the Insertion Sort. X = [7,3,5,8,2,9,4,15,6]

[2,3,5,8,7,9,4,15,6] 

[2,3,5,8,7,9,4,15,6] 

[2,3,4,8,7,9,5,15,6] 

[2,3,4,5,7,9,8,15,6]
