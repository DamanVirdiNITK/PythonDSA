21. Merge Two Sorted Lists

#Method 1 : Recursion
    def mergeTwoLists(self, list1, list2):
        """
        :type list1: Optional[ListNode]
        :type list2: Optional[ListNode]
        :rtype: Optional[ListNode]
        """
        
        if list1 is None:
            return list2
        if list2 is None:
            return list1
        if list1.val < list2.val:
            list1.next = self.mergeTwoLists(list1.next , list2)
            return list1
        else:
            list2.next = self.mergeTwoLists(list1, list2.next)
            return list2
                    

TC = O(m+n)
SC = O(m+n)
