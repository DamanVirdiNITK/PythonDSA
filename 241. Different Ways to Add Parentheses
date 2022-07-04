241. Different Ways to Add Parentheses


class Solution:
    def diffWaysToCompute(self, expression: str) -> List[int]:
        
        def operations(x,y,op):
            if op=='+':
                return int(x)+int(y)
            if op=='-':
                return int(x)-int(y)
            if op=='*':
                return int(x)*int(y)
        
        def evaluate(exp):
            res=[]
            for i in range(len(exp)):
                if exp[i]=='+' or exp[i]=='-' or exp[i]=='*':
                    left=evaluate(exp[:i])
                    right=evaluate(exp[i+1:])
                    for l in left:
                        for r in right:
                            res.append(operations(l,r,exp[i]))
            if not res:
                res.append(exp)
            
            return res
        
        return evaluate(expression)
    
    
