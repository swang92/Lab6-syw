###Lab 6###

**Question 1**

We have to create an explicit constructor because we need to set our capacity. Without a constructor, Java implements a no parameter constructor and our capacity would not be defined. 

**Question 2**

In our offer method, we define that if size equals capacity, return false. Since offer is a boolean method, it would not allow us to add an additional item to a full queue. 

**Question 3**

In our poll method, if the size is 0 then it would return null.

**Question 4**
All our methods are O(1) because we are only accessing the rear data of the array. With our poll method that is access the front of the array, we aren't shifting data (so space complexity isn't dependent on n) we are just shifting the value of front. The asList method is O(n) because we are copying the values from the queue into the array and therefore traversing through the ArrayList is dependent on n (the number of elements). 