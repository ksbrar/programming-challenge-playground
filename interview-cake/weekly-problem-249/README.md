# Find Kth-to-last node
Description: Write a function `kth_to_last_node()` that takes an integer `k` and the `head_node` of a singly-linked list, and returns the `k`th to last node in the list.

Example (python3):
```python
class LinkedListNode(object):

    def __init__(self, value):
        self.value = value
        self.next  = None

a = LinkedListNode('Angel Food')
b = LinkedListNode('Bundt')
c = LinkedListNode('Cheese')
d = LinkedListNode('Devil\'s Food')
e = LinkedListNode('Eccles')

a.next = b
b.next = c
c.next = d
d.next = e

kth_to_last_node(2, a)
```

[Original link](BROKEN).
