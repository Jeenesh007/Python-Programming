>>> def isPalindrome(string):
     left,right=iter(string),iter(string[::-1])
     i=0
     while i<len(string)/2:
            if next(left)!=next(right):
                     return False
            i+=1
            return True

