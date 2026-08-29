# Arrays
- Stores items at contiguous locations

## What it's good / bad for
Good:
- Random Access: i-th item can be accessed in O(1)
- Cache Friendliness: load adjacent data quickly

## Time & Space Complexity

| Operation  | Time Complexity | Notes                          |
|------------|:----------------:|---------------------------------|
| Access     | O(1)             | Direct index lookup             |
| Search     | O(n)             | Linear scan, unsorted           |
| Insertion  | O(n)             | Shifting required (mid/start)   |
| Deletion   | O(n)             | Shifting required (mid/start)   |
| Traversal  | O(n)             | Visit every element              |
| Update     | O(1)             | Direct index write              |

## Recognition triggers
- 

## Problems solved
- [two sum, best time to buy and sell stock, contains duplicate, valid anagram] 

