394. Decode String
#Method-1 Regex

The pattern to match an encoded substring of type: number[text] in s is '\d+\[\w+\]'
It can be divided into groups to simplify access to its values, for instance:
pattern '(\d+)\[(\w+)\]' has 2 groups, that can be called directly after matching:
'(\d+)' - number
'(\w+)' - string

import re
class Solution:
    def decodeString(self, s: str) -> str:      
        
        n = s.count('[')      
        for _ in range(n):         
            m = re.search(r'(\d+)\[(\w+)\]', s)
            s = s.replace(m.group(0), m.group(2) * int(m.group(1)))
        return s
        
        
        
        
  #Method-2 Using Recursion
  
##Pending
