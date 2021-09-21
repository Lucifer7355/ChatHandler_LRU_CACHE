# ChatList
A demonstration of how whatsapp chat message list appears and behaves.
The data structure used for demonstration purpose efficiently is LRU cache.

# We use two data structures to implement an LRU Cache.  

-Queue which is implemented using a doubly linked list. The maximum size of the queue will be equal to the total number of frames available (cache size). The most recently used pages will be near front end and least recently pages will be near the rear end.

-A Hash with page number as key and address of the corresponding queue node as value.