#Method 1:
class Solution:
    def halvesAreAlike(self, s: str) -> bool:
        half = len(s)/2
        temp = 0
        for i in range(0, len(s)):
            if s[i] in ['a','e','i','o','u','A','E','I','O','U']:
                if i<half:
                    temp+=1
                else:
                    temp -=1
        return temp == 0
                    

#Method 2:
    def halvesAreAlike(self, s: str) -> bool:
        vowels = set('AEIOUaeiou')
        temp = 0
        for i in range(0, len(s)//2):
            if s[i] in vowels:
                temp +=1
            if s[-i-1] in vowels:
                temp -=1
        return temp == 0
            
#Method 3:
       vowels = set('AEIOUaeiou')
       half = len(s) // 2
        return (sum(c in Solution.vowels for c in s[:half]) ==
                sum(c in Solution.vowels for c in s[half:]))
