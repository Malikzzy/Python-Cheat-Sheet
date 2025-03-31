## Tuples 
* Tuple is a collection of values
* Try to colse it in () so that it read better that it is a tuple
* Still can index into it [0], [1] ect
* A tuple can be passed along to a single varibale
* Example ```return (x,y) Z=get_return() print (z[0] z[1])```
* Tuples can't be be changes once assigned
* Tuples are inmutable meaning cant be changed, list are muntable meaning they can be changed

## Classes
* Classes have aributes
* Sytax is ```Class Name_X:```
* You can use ```...``` as a place holder
* This is were you start to use the . for example   ````Class Example      example.test example.test2````
* can delcare a value inside of a class with ```.``` so ```` class example: ...    example.test````
* can call it without () , meaning can be called as so ```print(example.test)```
* Classes creates objests
* objest is when you use the fuctionalilty of the object
* abother word for an object is an instance
* you can store attubies by using the ```.``` notation
* methos are functions that can be created within the class

## Definding a medthod aka a fucntion within a cslass
* ```class Give_Name:```
* ```def__init__ (self,somepar1,somepar2=None):```
* ```self.Variable_1 = input("say something")```
* ```self.Variable_2 = "some action"```
* This then can be called with``` Give_Name.Variable_1``` and ```Give_Name.Variable_2```
 
## __str__
* used for passing your fuction as a string
* str is used with the class to when called or run is a string is needed to be passed like when using print() when the print() looks through the block of code its this and reutrn whatever pice of string you want to pass
* it too needs (self) and can only take this 1 pramarter
* example ```def __str__ (self) retrun f"here is your reutn along with {self.somevalue}```



## Methods 
* When ever you make your own fuction aka a method you must always call the its first pramater as its self
* example ```def something_new (self):``` even if you dont use it you still need
* self made methods a work a bit differnt in that thy can return when called
* example ```class new_ class: def__init___(self,par1, par2)  def something_new (self): return "hi"```
* example ```print(new_class.something_new())```

## Properties 
* A way of hardening your class's object to make them less change able
* Using the @properties
* Also knowm as decorators
* Getter = get some value, Setter = set some value
* To set a Getter use ```@property``` ontop of your fuction.
* Example ```@property def some_method(self): return self.some_method```
* Then for the setter you'll use the . notation wih setter. It needs the name of the medthod you are setting the . notation setter
* Example ```@some_method.setter def some_medthod(self,parm1): self.some_method = xxxxxx```
* So when using setter think you are settings a varaible
* And for getter you are getting some variable
* 1 arg for getter and 2 arg for setter  

# @ Class Method
* Its use case is when having __method Varaibles__ within a class
* You have a variable that is set to be within the class
* You then use a decorator to make your fuction or method a class method
* Start with ```@classmethod``` at the top
* Set your function, then very important __!!!__ instead of using ```self``` use ```cls```
*  Example 
     ![image](https://github.com/user-attachments/assets/4ba68ab3-549e-4f8f-9d5a-5a5108bb390a)

## Inheritance 

## Operator overloadding
* you can onverride what a operator does within a call
* For add you can use ```def __add__ (self,other)```


## Extra
* You can use ```if not some_var``` just like if it was ```if some_var == ""``` (this is the same thing)
* You can use ```raise``` to output your own error along with a reason why
* Example ```raise ValueError("your missing a key")``` "ValueError" can you what ever you what it to be but best case say to raise on a error that is native.
*  **Match case** aka a (which case) you use ```match``` to intiate a ```case``` a set of cases to "match" followed by identation
*  Used ```_``` as a nothing aka like a ```else``` statment 
*  Usecase  ```Below 👇🏽``` 
*  ![image](https://github.com/user-attachments/assets/6db4295c-2622-456a-963e-8575153be169)
* A variable instead of the class __init__ is called an instance variavle
* Captitlize your Class name
  
  
