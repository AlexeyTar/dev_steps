We need to implement a Least Recently Used (LRU) cache, which has a fixed capacity and removes the least recently used item when full.

Step 1: Understand the Problem Clearly
- Requirements:
    - The cache should store key-value pairs.
    - When the cache reaches its capacity, it should remove the least recently used item.
    - Accessing or adding an item should move it to the most recently used position.

- Constraints:
    - Operations should be efficient: O(1) for get and put.

- Edge Cases:
    - What happens when getting a non-existent key? → Return -1.
    - What if we add a new key when the cache is full? → Evict LRU item.