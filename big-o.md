# O(n^2) - quadratic

- As our input grows, our operations grow quadratically

- Examples:

  - Traversing a **square** matrix
    - nums = [[1,2,3], [4,5,6],[7,8,9]]
    - for (let row = 0; row< nums.length;row++) {
      for (let col=0; col< nums.length; row++) {
        console.log(nums[row][col])
      }
    }
    - if the matrix is not square then it is not O(n) it is O(m*n)

# O(n*m)

- Just because we have nested loops does not mean O(n^2)!!!
- WE MUST DEFINE OUR VARIABLES
- Example
  - Traversing through a rectangle matrix
    - nums = [[1, 2, 3, 4], [5,6,7,8],[9,10,11,12]]
    - for (let row = 0; row< nums.length;row++) {
      for (let col=0; col< nums.length; row++) {
        console.log(nums[row][col])
      }
    }

    ```
            m
      _____________
      |__|__|__|__|
      |__|__|__|__|  n
      |__|__|__|__|

      ^ O(n * m)
    ```

# O(log(n)) - logrithmic

- As our input size grows, our operations grow logarithmically
- Marginally more efficient than O(1) but much more efficient than O(n)
- Examples:
  - Binary Search

# O(n*log(n))

- Marginally more inefficient than O(n) but much more efficient than O(n^2)
