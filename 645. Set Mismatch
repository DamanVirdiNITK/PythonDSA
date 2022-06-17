class Solution:
    def findErrorNums(self, nums: List[int]) -> List[int]:
        nums_dict = Counter(nums)
        result = [0,0]
        for i in range(1, len(nums)+1):
            if nums_dict[i] == 2:
                result[0] = i
            elif nums_dict[i] == 0:
                result[1] = i
        return result
        
