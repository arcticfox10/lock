# lock
https://github.com/raferalston/python_basics.git


import module
module.f()

from module import *
f()                     плохой вариант

from module import function as f
f()



with open("nae_file","r") as f:
  read_date=f.read()
  
 f = open("file","w")
 f.write("hello")
 f.close()
