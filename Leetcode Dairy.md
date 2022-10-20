# Leet code
## 22.OCT.20
876. Middle of the Linked List
fast slow pointer
but mine is faster?
```
length = 1;
        count = head
        res = head
        while count.next:
            count = count.next
            length += 1
        for i in range(length//2):
            res = res.next
        return res
```

383. Ransom Note
```
for i in set(ransomNote):
            if ransomNote.count(i) > magazine.count(i):
                return False
        return True
```
### why:
    convert string to set
    set(), count(), are both implemented in c.
    collections.Counter is written in python. -QJZ

977. Squares of a Sorted Array

```
https://leetcode.com/problems/squares-of-a-sorted-array/discuss/310865/Python%3A-A-comparison-of-lots-of-approaches!-Sorting-two-pointers-deque-iterator-generator
```