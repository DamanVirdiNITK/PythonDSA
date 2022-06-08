class Solution:
    def findWords(self, words: List[str]) -> List[str]:
        s1 = set('q w e r t y u i o p'.split())
        s2 = set('a s d f g h j k l'.split())
        s3 = set('z x c v b n m'.split())
        result = []
        for word in words:
            sword = set(word.lower())
            if sword.issubset(s1) or sword.issubset(s2) or sword.issubset(s3):
                result.append(word)
                
        return result
    
        
