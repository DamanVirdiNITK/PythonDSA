class Solution:
    def reverseVowels(self, s: str) -> str:
        vowelList = []
        for word in s:
            if word in ['a' , 'e' , 'i' ,'o' , 'u','A', 'E','I','O','U']:
                vowelList.append(word)
        s1 = ''
        for word in s:
            if word in ['a' , 'e' , 'i' ,'o' , 'u','A', 'E','I','O','U']:
                s1 = s1 + vowelList[-1]
                vowelList = vowelList[:-1]
                s = s[1:]
            else:
                s1 = s1 +s[0]
                s = s[1:]
        return s1
                
            
        
        
