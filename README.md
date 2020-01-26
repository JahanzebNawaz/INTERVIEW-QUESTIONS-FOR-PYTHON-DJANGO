# INTERVIEW-QUESTIONS-FOR-PYTHON-DJANGO
INTERVIEW QUESTIONS FOR PYTHON DJANGO


## PYTHON

#### 1 - json.loads()
        json loads parse json data to python dictionary
#### 2 - json.dumps()
        json dumps converts python dict to json object (string ) 
        
#### 3 - RegEx
        regex is a regular expression , a sequence of charactors used for search pattern.
        import re
        txt = 'this is string'
        x = re.search('^The ', txt)
        
        if x:
        print('worked')
        
#### 4 - difference between List and Tuple and  SET, Dict
        list is a collection of data  that is ordered and changeable, dublicates members allowed
        tuple is a  collection of data  that is ordrend and unchangeable, dublicates members allowed
        set is collection of data that is unordered and unindexed, no dublicate members 
        dict is collection of data that is unordered and indexed, changeable, no dublicates members
                
#### 4 - difference between list append and  insert()
        append() adds new data at the end of list
        insert() allows to add data at specified index no. instert(1, 'orange')
        
        
        
        
#### 5 - swappe the values without using 3rd variable
        a = 5
        b = 50
        there are different ways to do this .. through arithmetic operation
        a = a + b 
        b = b - a
        a =  a - b
        so you can use different operations.. 
        but we have another way as well .. Bitwise XOR that plays with binary nos
        a = a ^ b
        b = a ^ b
        a = a ^ b
 
#### 6 - print index wise values
        a = ['jahanzeb', 'nawaz']
        b = ['34', '67']

        c = len(a)
        for x in  range(c):
          print(a[x], b[x])
          
#### 7 - reverse a string
        a = 'You can use index numbers'[::-1]
        or
        b = a[::-1]
        print(b)
        
        ------
        other way, recursive function

        def reverse(a):
          if len(a) == 0:
            return a 
          else:
            return reverse(a[1:]) + a[0] 

        a = 'You can use index numbers'

        print(reverse(a))
        
        
 #### 8 - Fibonacci series       
        n = 20
        a = 0
        b = 1
        while a < n:
          print(a)
          a , b = b, a+b

#### 9 - even no
        def evennum(a):
          for x in range(a):
            if x%2 == 0:
              print(x)

        evennum(20)
        
    
#### 9 - odd no
        def oddnum(a):
          for x in range(a):
            if x%2 != 0:
              print(x)

        oddnum(20) 
        
        
#### 9 - prime no
        no = 30
        for x in range(no):
          if x > 1:
            for i in range(2, x):
              if (x%i) == 0:
                break
            else:
              print(x)
        

 ## SQL
 
#### What is a Cursor?

        A database Cursor is a control which enables traversal over the rows or records in the table. This can be viewed as a           pointer to one row in a set of rows. Cursor is very much useful for traversing such as retrieval, addition and removal of database records. 
        
        
