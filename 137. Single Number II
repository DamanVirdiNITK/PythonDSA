class Solution:
    def singleNumber(self, nums: List[int]) -> int:
        num_dict = Counter(nums)
        for key in num_dict:
            if num_dict[key] == 1:
                return key
        
