143. Reorder List

#Method 1: Reverse the Second Part of the List and Merge Two Sorted Lists

# Definition for singly-linked list.
# class ListNode:
#     def __init__(self, val=0, next=None):
#         self.val = val
#         self.next = next
class Solution:
    def reorderList(self, head: Optional[ListNode]) -> None:
        """
        Do not return anything, modify head in-place instead.
        """
        if not head:
            return
        
        #find middle element
        slow = fast = head
        while fast and fast.next:
            slow = slow.next
            fast = fast.next.next
            
            
            
            
        #reverse of second part of list
        prev, curr = None, slow
        while curr:
            curr.next, prev, curr = prev , curr, curr.next
            
        
        #merge two sorted linked list
        first, second = head, prev
        while second.next:
            first.next, first = second, first.next
            second.next, second = first, second.next
        
        
 TC - O(N)
 SC - O(1)
