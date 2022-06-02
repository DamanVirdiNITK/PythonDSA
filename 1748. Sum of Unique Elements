#1st Method
class Solution:
    def sumOfUnique(self, nums: List[int]) -> int:
        result = 0
        
        #Create dict of the occurences 
        myDict = Counter(nums)
        
        #If the element has just occurred once, add it
        for i in myDict:
            if myDict[i] == 1:
                result +=i
                
        return result
        
#2nd Method
    l=[i for i in nums if nums.count(i)==1]
    return sum(l)
