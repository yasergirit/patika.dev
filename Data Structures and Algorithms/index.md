## Project 1

[22,27,16,2,18,6] -> Insertion Sort

### 1. Steps of Insertion Sort

``` 
[22|,27,16,2,18,6]
[22,27|,16,2,18,6]
[16,22,27|,2,18,6]
[2,16,22,27|,18,6]
[2,16,18,22,27|,6]
[2,6,16,18,22,27]
``` 
### 2. Big-O Notation

```
Worst Case : O(n^2)
Avarage Case : O(n^2)
Best Case : O(n)
```

### 3. Time Complexity

```
Best Case : [2,6,16,18,22,27]
Worst Case : [27,22,18,16,6,2]
```

It becomes like [2,6,16,18,22,27] after the array is sorted. So this is **Average Case**.

### 4. First 4 Steps Depending on Inserion Case

```
[7|,3,5,8,2,9,4,15,6]
[3,7|,5,8,2,9,4,15,6]
[3,5,7|,8,2,9,4,15,6]
[3,5,7,8|,2,9,4,15,6]
```
