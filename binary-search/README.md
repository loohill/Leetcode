# Binary Search

Binary Search: [https://www.khanacademy.org/computing/computer-science/algorithms/binary-search/a/binary-search](https://www.khanacademy.org/computing/computer-science/algorithms/binary-search/a/binary-search)

```go
for start + 1 < end {
    mid := (end-start)/2+start
    
    if nums[mid] > target {
        end = mid
    } else {
        start = mid
    }
}
```

