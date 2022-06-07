class Solution:
    def uncommonFromSentences(self, s1: str, s2: str) -> List[str]:
        result = []
        d1 = Counter(s1.split())
        d2 = Counter(s2.split())
        d = d1+d2
        for i in d:
            if d[i] == 1:
                result.append(i)
        return result
