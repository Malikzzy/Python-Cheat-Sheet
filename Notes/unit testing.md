## testing
* you can use ```assert``` thats built in to check if an acition is true/boolen
* example : ```x=10    assert x ==2``` this will give you a ```AssertionError```, which can be use in a try/except

## pytest 
* 3rd party libary that allows you to perform unit testing
* ```pip install pytest```
* run ```pytest``` from the terminal
* ```pytest.raises(TypeError)``` you can change the error value 


## Extra 
* Unit testing is testing fuctions within your program
* best practice to name the fuction your testing test_thenameofthefunction. Exmaple ```def app()  def test_app()``` 
* ```with``` keyword opens files
* Try to avoid not returning a value when testing your code. a print is only to display so when you can if def a function have it set to that it returns a value
* try to back down the function when running pytest (its best practice) 
