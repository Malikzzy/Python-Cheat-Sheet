## Libraries
* Libraries aka module
* ```import``` then the package. Then when using the .xxx that is the module.
* example ```random.choice()``` random being the package and choice being the module

# Import/from
* Just import will inport all fuctions
* 

## Random 
* ```random.choice(seq)``` takes a list of stings and outputs one of them randomy
* ```random.randint(a,b)``` takes a range of number and out put a random number
* ```random.shuffle(x)``` random order of a list 
* 

## statistics
* statistics.mean() that a list of number and output the mean

## Extra 
* seq in documentation means a list 

## Sys
* ```import sys```
* ```sys.argv()``` will take a list and be used to send
* Example of sys.argv() ```print(sys.argv[1])```. In terminal ```nameoffile.py hi``` Output ```hi```
* With in ternmali if you use stings like you would in powershell it would include any speration made by spaces 
* ```sys.exit()``` Will exit from the program but can all be pass a string to display a output as well. Example ```sys.exit("wrong input, now closing program")```

## Errors 
* list index out of range use ```IndexError```

## Extra
* Using condintal statesments is aonther way to control errors 
* Slice is a common term to take a pice of a list. To do so use the following syntax ```for _ in list[1:]``` This will start the list at index one and go all they way through. You can also give it a range like so ```for _ in list[1:20]
* Slice can also count backwards with example ```for _ in list[1:-1]```
* Json Language agonstic format that can be used by almost any programing language, maning used to exchange data between computers 


## Packages 
* 3rd party libaries
* Install with ```pip``` example ```pip install flask```

  ## APIs
  * the ```requests``` libary can be use to make internet request as if it was a browser
  * requests can be installed with pip
  * use the ```.get()``` fuction to call to the site 
  * use ```json()``` from the requests libaary to return the data in a jason format. example ```response = API.com/ect/ect
