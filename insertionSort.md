# Insertion Sort

## 1) Incertion Sort of [22,27,16,2,18,6] (Step by step.)

```
[22,27,16,2,18,6]
[22,27,16,2,18,6]
[22,16,27,2,18,6]
[16,22,27,2,18,6]  
[16,22,2,27,18,6]  
[16,2,22,27,18,6] 
[2,16,22,27,18,6] 
[2,16,22,18,27,6] 
[2,16,18,22,27,6] 
[2,16,18,22,6,27] 
[2,16,18,6,22,27] 
[2,16,6,18,22,27]
[2,6,16,18,22,27]
Result = [2, 6, 16, 18, 22, 27]
```

## 2) Big-O Notation

```
Worst Case : O(n^2)
Avarage Case : O(n^2)
Best Case : O(n)
```

## 3) Time Complexity

### If we're looking for ''2'' in [22,27,16,2,18,6]

```
Worst Case : [27,22,18,16,6,2]
Avarage Case : [6,2,16,18,22,27]
Best Case : [2,6,16,18,22,27]
```

## 4) Which case is suit for ''18'' after the array is sorted?

```
Average Case is suit for '18' because it is in the middle of the array.
```

## 5) Insertion sort of [7,3,5,8,2,9,4,15,6] only first 4 steps.

```
[7|,3,5,8,2,9,4,15,6]
[3,7|,5,8,2,9,4,15,6]
[3,5,7|,8,2,9,4,15,6]
[3,5,7,8|,2,9,4,15,6]

```

Algorithms and Data Structures with [Patika.dev](www.patika.dev)