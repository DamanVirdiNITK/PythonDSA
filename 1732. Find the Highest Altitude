class Solution:
    def largestAltitude(self, gain: List[int]) -> int:
        heightList = [0]
        for  i in gain:
            heightList.append(i+heightList[-1])
            
        return max(heightList)
            
        
