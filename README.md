# Binary-Search

Binary Search is defined as a searching algorithm used in a sorted array by repeatedly dividing the search interval in half. The idea of binary search is to use the information that the array is sorted and reduce the time complexity to O(log N). 

![image](https://user-images.githubusercontent.com/125429608/234450647-b6e0129e-4d92-4cb3-b652-323ea4989424.png)

Conditions for when to apply Binary Search in a Data Structure:
To apply binary search in any data structure, the data structure must maintain the following properties:

The data structure must be sorted.
Access to any element of the data structure takes constant time.

How does Binary Search work?
To understand the working of binary search, consider the following illustration:
First Step: 
Initially the search space is from 0 to 9. 
Let’s denote the boundary by L and H where L = 0 and H = 9 initially. 
Now mid of this search space is M = 4. 
So compare target with arr[M].
Second Step: 
As arr[4] is less than target, switch the search space to the right of 16, i.e., [5, 9]. 
Now L = 5, H = 9 and M becomes 7. 
Compare target with arr[M].
Third Step: 
arr[7] is greater than target. 
Shift the search space to the left of M, i.e., [5, 6]. 
So, now L = 5, H = 6 and M = 6. 
Compare arr[M] with target. 
Here arr[M] and target are the same. 
So, we have found the target.

![image](https://user-images.githubusercontent.com/125429608/234450802-b3426b6c-d749-4856-be8c-7fb35686003c.png)
