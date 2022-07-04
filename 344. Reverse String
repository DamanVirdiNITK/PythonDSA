344. Reverse String

########Method 1:
return s.reverse()



########Method 2: Recursion
In first swap :First n last 
In second swap : Second n last second
In third swap : Third n last third

    def reverseString(self, s):
        def helper(left, right):
            if left < right:
                s[left], s[right] = s[right], s[left]
                helper(left + 1, right - 1)

        helper(0, len(s) - 1)

T(C) = O(n)  n/2 swaps
S(c) = O(n)

###########Method 3: Two Pointer Approach
def reverseString(self, s: List[str]) -> None:
        """
        Do not return anything, modify s in-place instead.
        """
        left, right = 0, len(s)-1
        while left< right:
            s[left], s[right] = s[right], s[left]
            left , right = left+1 , right -1
            
TC = O(n)   for n/2 swaps
SC = O(1)    no extra space required
