# Python-Cheat-Sheet

## F-String
* "f{}" with in the string. example: ```greeting = f"hello {name}"```

## List, Tuples, and Sets
* **List** is set up with ```[]``` and **can be added to and removed**
* **Tuples** are setup with ```()``` and **cannot be added to or removed**
* **Sets** are setup with ```{}```  and **can be added and removed, but cannot have duplicate information**
* You can add to a end of a **list** with ```.append()```
* You can remove a object from a list with ```.remove()```
* You can compare 2 **sets** with the ```.difference()```. ***The output will be the difference between the two sets***
* You can use ```union.()``` to join two **set** together
* Use ```intersection.()``` to get the output of the what is the same in two sets

## Booleans
* Comparisons: ==, !=, >, ,< ,>= ,<=
* * Use ```is``` is used to check if elements is the same ***(memory information are the same)***

## Conditional statements
* if, elif, and else
* Use ```in``` as a boolean statement for a value within a value, ***typically used check is a value is in a list***

## Dictionaries 
* Setup dictionaries pairs with in sets ```{}```
* Keys and values are setup with ```:```. Example:``` Player_Level = {"Player_1": 30, "Player_2: 58, "Player_3: 2"} ```
* Getting the output of the value can be done by calling the variable then its key,  ``` Variable["key"]``` ***The output will be the key's value***
* To add or change the a existing key called the existing variable and set a key to equal a value. Example ```Player_level["Player_4"] = 20```
* List can be used to store more sets and can be accessible through calling the list index then the key. ```Variable[index][key]``` ***The output will be that index's pair value***
* Example: ```Players = [ {"Name": "Alex", "Level": 32 } {"Name": "La-a", "Level": 12 } {"Name": "AAron", "Level": 20 } ]``` ```print(players[2]["level"])``` ***Output will be 30***

## Default parameter (Return to this)

## Return with Functions
* use the ```return``` command to return data from the function 
* Return will also end and exit the function 
* Try not to mix the data type it is returning. So if its num and you mixes it by 5 vs if its a string and you times it by 5 

## lambda function
* Written with by calling it then with ```:``` 
* Think of it as pipe ```|```, take input and return output
* Example ```lambda x,y: x+y```
