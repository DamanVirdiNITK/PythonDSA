439. Ternary Expression Parser

class Solution:
    def parseTernary(self, expression: str) -> str:
        if expression.isnumeric() or expression in ('T', 'F'):
            return expression
        
        question_marks = 1
        is_true = expression[0] == 'T'
        
        for i in range(2, len(expression)):
            char = expression[i]
            if char == '?':
                question_marks += 1
            elif char == ':':
                question_marks -= 1
            if question_marks == 0:
                inner_expression = expression[2:i] if is_true else expression[i + 1:]
                return self.parseTernary(inner_expression)
        
        raise ValueError('Invalid Ternary Expression')
