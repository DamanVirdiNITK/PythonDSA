class Solution:
    def capitalizeTitle(self, title: str) -> str:
        title_list = title.split(' ')
        result = []
        for word in title_list:
            if len(word) == 1 or len(word) == 2:
                result.append(word.lower())
            else:
                result.append(word.title())
        return (' '.join(result))
        
        
        
 #2nd Method
         return ' '.join([word.lower() if len(word)<3 else word.title() for word in title.split()])

            
        
