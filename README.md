# The Fisher-Yates Shuffle
###### I found this week to be more understanding then the last, and I felt like I was starting to get a better grasp on the expectaion of algoritms. 

###### For Fisher-Yates specifically I found positives and negatives to both of the reviewed versions:

###### Though I don't love the for loop conditions of this one, formating it in such a way makes the rest of the coding process smooth. Not setting int i = 0, and instead utilizing the lenth of the array, makes the swap very smooth

```
-- To shuffle an array a of n elements (indices 0..n-1):
for i from n−1 downto 1 do
     j ← random integer such that 0 ≤ j ≤ i
     exchange a[j] and a[i]
```

###### While for this one, though I love working with int i = 0 in my for loops it makes the rest of the code less then ideal.
```
-- To shuffle an array a of n elements (indices 0..n-1):
for i from 0 to n−2 do
     j ← random integer such that i ≤ j < n
     exchange a[i] and a[j]
```
