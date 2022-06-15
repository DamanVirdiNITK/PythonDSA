class Solution:
    def findNumbers(self, nums: List[int]) -> int:
        result = 0
        for num in nums:
            length = 0
            while num>0:
                length += 1
                num = num//10
            if length%2 == 0:
                result +=1
        return result
