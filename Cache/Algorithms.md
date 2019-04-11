LRU - Least Recently Used
    The most recent entries will be moved to the start of the queue. The older entries are removed during eviction.
    -Last accesses item has high priority
    -One approach is to use a popularity sketch (http://highscalability.com/blog/2016/1/25/design-of-a-modern-cache.html)

LFU - Least Frequently Used
    Counter is maintained for each entry and the entry with the least value for counter will be evicted.

ARC - Adaptive Replacement Cache 
    Combination of LRU and LFU and the evicted entries.

MRU - Most recently used
    The most recently used item will be removed from cache

