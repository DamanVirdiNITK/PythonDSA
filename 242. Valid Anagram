#Method 1: Counters
class Solution(object):
    def isAnagram(self, s, t):
        """
        :type s: str
        :type t: str
        :rtype: bool
        """
        counter = Counter(s)
        
        for i in t:
            if i in s:
                counter[i] -=1
            else:
                return False
        for i in counter:
            if counter[i]>0:
                return False
        
        return True
            
  
