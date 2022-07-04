

#Method 1: Iteratuve
def reverseList(self, head: Optional[ListNode]) -> Optional[ListNode]:
        prev, curr = None, head
        while curr:
            curr.next, prev, curr = prev , curr, curr.next
        return prev
 TC= O(n)
 SC = O(1)
       
#Method 2: Recursion 

class Solution:
    def reverseList(self, head: ListNode) -> ListNode:
        if (not head) or (not head.next):
            return head
        
        prev = self.reverseList(head.next)
        head.next.next = head
        head.next = None
        return prev
        
TC = O(n)
SC = O(n)
