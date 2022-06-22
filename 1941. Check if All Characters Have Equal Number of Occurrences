class Solution:
    def areOccurrencesEqual(self, s: str) -> bool:
        s_dict = Counter(s)
        temp = s_dict[s[0]]
        for key in s_dict:
            if s_dict[key] !=temp:
                return False
        return True
        
