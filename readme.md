# **Python mutable strings**

Python mutable strings define bytearray based class - MutStr with object of mutable strings and all
 methods from default string

## **Installation**

To install this package run command: `$ pip install mutable_strings`

## **Usage**

- import MutStr class from mutable_strings module: 

`>>> from mutable_strings import MutStr`

- define object of mutable string: 

`>>> mut_str = MutStr("Hello World")`

##### _Output: Hello World_

- for change string use index or slices:

 `>>> mut_str[0] = "R"`
 
##### _Output: Rello World_
 
 `>>> mut_str[:] = "Wello Horld"`
 
##### _Output: Wello Horld_

You can use new custom method - rreplace(old, new)

`>>> mut_str.rreplace('W', 'H')`

##### _Output: Wello Horld_

Also you can use all default string methods.