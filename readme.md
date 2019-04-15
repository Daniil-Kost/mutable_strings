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

- for change string use slices (!Important - always use slices with two digits 
when you change some symbols (e.g. [0:1]!)
 
 `>>> mut_str[0:1] = "W"`
 
##### _Output: Wello World_

You can use new custom method - rreplace(old, new)

`>>> mut_str.rreplace('W', 'H')`

##### _Output: Wello Horld_

Also you can use all default string methods.