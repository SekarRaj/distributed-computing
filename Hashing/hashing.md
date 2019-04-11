Used for indexing 
    - based on Hash Functions

Hash Function Types
    - Modulo Reduction (Multiplying by prime and modulo)
    - Multiply-Shift Hashing (https://lemire.me/blog/2016/06/27/a-fast-alternative-to-the-modulo-reduction/)
    - MurmurHash
    - Tabulation Hashing

Collision Handling
    -   Chaining (Storing linked list in each index instead of single item [Lookup is no longer strictly O(1)])
    -   Linear Probing (Store the item in next empty index position [Lookup is no longer strictly O(1)])
    -   Cuckoo Hashing 



Alternatives
 - B-Tree
 - Learned index structures (https://www.arxiv-vanity.com/papers/1712.01208/)





 https://blog.bradfieldcs.com/an-introduction-to-hashing-in-the-era-of-machine-learning-6039394549b0