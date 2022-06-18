class Solution:
    def checkString(self, s: str) -> bool:
        flag = 0
        for word in s:
            if word == 'b':
                flag = 1
            if flag == 1 and word == 'a':
                return False
        return True

#Second Approach
        return (''.join(sorted(list(s))))==s

#Third Approach
def checkString(self, s: str) -> bool:
        return "ba" not in s
