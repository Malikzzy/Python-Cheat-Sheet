## File I/O

* ```.append()```
* ```sorted()```
* Open() will need the file name, its permission is auto set to read I think but can be adusjested in the 2nd prarmater ```open("filename", "w")```
* ```.write()``` to write to the file
* ```.close()```
* ```open("filename", "a")``` = append the file
* Appenred and write will automake the file
* Example ``` name = input("what's your name") file = open("namefile.txt", "w") file.write(name) file.close()```
* A more pythonic apporach is to use ```with```
* ```with``` is a statment almost like a ```for``` or ```if``` that need a veraible name assigned to it
* ```with open() as file: file.write()```
*  Using this will help close the while as to is auto done for us rather then using file.close(). Not closing the file can lead to error espsyically file curroption
* another method called ```.readlines()```, example ```file.readlines()```


## in
* the ```in``` keywaord is used to check memebership or iterate through intems in a squence.
* ```list =[x,y] if "x" in list:``` Used a boolen
*  ```for file in files```


## Extra
* when assigning a valeriable to a statment the term is call return value
* strip(), rstrip(), lstrip()
* method in Python that removes trailing spaces, tabs, or newline characters aka /n
* .strip()	Both left and right
* .lstrip()	Left side only
* .rstrip()	Right side only
* You can also specify which characters to remove.
* .rstrip("!")
* csv stamds for comma sperated file
* When working with a diconary you can assign a new key value, example ```hi ={}``` ```hi["name"] = 'Bob' hi["age"] = 69
  
  ## Lamda
  * Create a temp function
  * Only used onetime
  * Will always ```return``` data
  * You can use lammba can define multiple variables, example ```lambda x,y,z: x=1,y=2,z=3```
 
    ## CVS Libary
    * import csv
    * csv.reader(file)
    * rows can be called by assining a variable and using a index to to select [0] would be row 1 and [1] would be row 2
    * csv will return in as a list aka why you are using a index to call for the data
    * csv.DictReader can be used when there is a columbn name 
