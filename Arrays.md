# Arrays

Arrays are stored in memory in a contiguous way

## Types of Arrays
#

### Static Arrays

- have a fixed size

### Dynamic Arrays

- size is not fixed
- Array.push() is O(n)
- read/write nth element is O(1)
- insert/remove end element is O(1)
  - because we do not have to reindex cause it is the end element
- insert middle or beginning is O(n)
  - because have to reindex everything
- remove middle or beginning is O(n)
  - have to reindex everything
