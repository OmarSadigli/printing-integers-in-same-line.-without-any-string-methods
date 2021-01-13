# printing-integers-in-same-line.-without-any-string-methods

from __future__ import print_function

n = int(input())

for i in range(1,n+1):
    print(i,end='')
'''    
By default python’s print() function ends with a newline. A programmer with C/C++ background may 
wonder how to print without newline. Python’s print() function comes with a parameter called ‘end’. 
By default, the value of this parameter is ‘\n’, i.e. the new line character. You can end a print 
statement with any character/string using this parameter.

# This Python program must be run with 
# Python 3 as it won't work with 2.7. 
  
# ends the output with a <space>  
'''
