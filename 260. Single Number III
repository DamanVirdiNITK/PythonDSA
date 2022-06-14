class Solution:
    def singleNumber(self, nums: List[int]) -> List[int]:
        result = []
        dict_num = Counter(nums)
        for key in dict_num:
            if dict_num[key] == 1:
                result.append(key)
        return result
        
