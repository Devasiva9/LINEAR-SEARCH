# LINEAR-SEARCH IN PYTHON
def linearsearch(list,n,key):
    for i in range(0,n):
        if(list[i] == key):
            return i
    return -1
list = [5,6,7,8,9,9]
key = 7
n = len(list)
res = linearsearch(list,n,key)
if(res == -1):
    print("element not found")
else:
    print("element found",res)

            
            
