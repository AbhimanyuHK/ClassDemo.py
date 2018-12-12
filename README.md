### ClassDemo.py

## Import libraries

``` import os ```

``` from sys import stdout ```

``` 
try:
    from src.main.python import MyClass1 as test
except ImportError:
    import MyClass1 as test
```
## Class Docs

``` 
class MyClass(object):
    '''
    classdocs : MyClass is demo class for docs
    
    '''
```

## Method Docs

``` 
def method(self, a, b):
        '''
        method : addition operation by a and b.
        
        a : int =>  input to the method.
        b: int => input and output to the method.
        
        Exception : Exception
        return : int, 
        
        '''
 ```
 
### Try - Catch

```
try:
   b = b + a
except Exception as e:
   return e
else:
   return b
```

## List Comprevension

```
sqre = [item*item for item in list]
```
## Demo Class

``` 
'''
Demo Class.

Created on Dec 12, 2018

@author: abhimanyu_h_k
'''

# System Level 
import os
import sys
      
# Third Party Level
import boto3

# Local Level
try:
    from src.main.python import MyClass1 as test
except ImportError:
    import MyClass1 as test
    

class MyClass(object):
    '''
    classdocs : MyClass is demo class for docs
    
    '''

    def __init__(self, param1, param2):
        '''
        Constructor : initializing the MyClass with param1, param2.
        
        param1 : this is string.
        param2 : this is list.  
        
        '''
        self.par1 = param1
        self.par2 = param2
        
    def method(self, a, b):
        '''
        method : addition operation by a and b.
        
        a : int =>  input to the method.
        b: int => input and output to the method.
        
        Exception : Exception
        return : int, 
        
        '''
        
        try:
            b = b + a
        except Exception as e:
            return e
        else:
            return b
    

```
