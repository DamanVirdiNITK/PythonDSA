1207. Unique Number of Occurrences
    def uniqueOccurrences(self, arr: List[int]) -> bool:
        
        #Dict to count the occurrences of each element
        countdict = {}
        for i in arr:
            if i in countdict:
                countdict[i] +=1
            else:
                countdict[i] =1
                
                
        #List to store the occurrences of each element        
        freqlist = []
        for i in countdict:
            freqlist.append(countdict[i])
            
            
        #If length of set and list is equal, then all the occurrences are unique
        return len(set(freqlist)) == len(freqlist)
                
            
        
#SECOND WAY
        myDict = Counter(arr)
        return len(myDict.values()) == len(set(myDict.values()))     

#THIRD WAY
        #list to check values
        valuecheck = []
        
        #iterate through distinct values
        for item in set(arr):
            valuecheck.append(arr.count(item))
        
        return(len(valuecheck) == len(set(valuecheck)))
