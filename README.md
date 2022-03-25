# OOP.python
**I am making this repository to learn and practice Object Oriented Programming in Python Language**

**Where am I learning from?**
[Python OOP](https://www.youtube.com/playlist?list=PLOkVupluCIjvfzQFgjiSQIccKiC-BJXwi)

**Who is the instructor?**
[JimShapedCoding - Instagram](https://www.instagram.com/jimshapedcoding/)

## Let's Begin...

> We will be understanding the concepts of Object Oriented Programming in Python by developing a store management system from scratch.

### What problems does OOP solve?
- You can directly open the code from above, or you can [click here](./Video_1.ipynb).

**In video_1.ipynb**, we can see that all the variables are having prefix for variable description as item1. But for python, those are just variables.
- When we print the types of those variables, we will get the type of the variables with no surprise.
- Please note here, we can also see the keywords 'class' in the output. This implies that the variables that we declared and initiated are nothing but the instances of the class *'str' and 'int'*.
- In python programming language, each data types is an object that has been instantiated earlier by some class. Here, for **'item1'** variable, string type of class is instantiated and for **'item1_price', 'item1_quantity' and 'item1_price_total'** variables, integer type of class was instantiated.
---

### Let's create a class!
```python
class Item:
  pass
item1 = Item()
item1.name = 'Phone'
item1.price = 100
item1.quantity = 5
```

- So, here you can see that we created a class Item which at present doesn't have any attributes or methods as of now. And then we create item1 of type Item (so basically, Item is sort of a new data type we created).
- Then we initialised its attributes with values. Now again when we try to get the type of each object, we will see that the *'item1'* is now of type **'__main__.Item'**
