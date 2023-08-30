## strangeSums Function

The `strangeSums` function takes in an array of numbers and returns the count of distinct pairs of elements within the array that sum up to zero. It assumes that the input array contains unique elements.

### Function Signature

```javascript
function strangeSums(arr) {
  // Implementation here
}
```

### Parameters

- `arr` (Array): An array of numbers containing unique elements.

### Return Value

- Returns an integer representing the count of distinct pairs of elements that sum up to zero.

### Example Usage

```javascript
const inputArray = [2, -2, 3, -3, 4, -4];
const result = strangeSums(inputArray);
console.log(result); // Output: 3
```

### Example Explanation

In the example usage provided:

- The input array is `[2, -2, 3, -3, 4, -4]`.
- There are three distinct pairs of elements that sum up to zero: (2, -2), (3, -3), and (4, -4).
- Therefore, the function returns `3`.

This README-like explanation should provide a clear understanding of the `strangeSums` function, its purpose, parameters, return value, and how it works algorithmically.
