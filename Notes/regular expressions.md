##Regex
* ```re``` libary
* re.search(pattern, string, flags)
  * ```.``` any char
  * ```*``` 0 or more patterns
  * ```+``` 1 or more patterns
  * ```?``` 0 or 1 patterns
  * ```{}``` you set a pattern value example ```{3}```
  * ```{x,y}``` you set a range of patterns
  * <img width="508" alt="image" src="https://github.com/user-attachments/assets/a8820a06-007b-4613-8bb6-d6d3c80ba8f4" />
  * Raw string ```r""``` this will stop python from impertating a string
  * ```\``` can be used to escape from a srtring
  * r string should be used on all regualr expressions
  * ```^``` start of the string and ```$``` end of the string
  * ```[]``` set of characters
  * ```[^]```  you cannot match any of theses characters
  * ```[^]``` can aslo take another varibale that is to say exerthing except [^@] aka everthing extecpt @
  *  you can do take a range ```[a-zA-Z0-9]```
  *   This ```[a-zA-Z0-9]``` can also be done by using a word charcter ```\w```
  *   ![image](https://github.com/user-attachments/assets/4572753b-57da-4028-b30e-04b25b434293)
  *   you can add or's by placing them in a () followed by |, so for example \.(com|edu|gov|net|io|org)$
  *   <img width="282" alt="image" src="https://github.com/user-attachments/assets/38dea3c2-88b2-4b1f-a0fc-369df661fada" />
  *   Can be used in the flag pramater, ```re.search(r"",string,re.IGNORECASE)
  *   <img width="395" alt="image" src="https://github.com/user-attachments/assets/373ccc4b-40f8-4e9a-8d22-abd95a040b7d" />
  *   When allowing a special char like . when you have \w you will need to escape it for example ```(\w|\.)```
  *   Walrus expression ```:=``` allows you to assign a variable and ask a boolen question
  *   .group() .replace() .removeprefix()
  *   re.sub()
  *   <img width="422" alt="image" src="https://github.com/user-attachments/assets/56efa054-00d1-468a-a1ca-c512b7d3227f" />
  *   Take it slow, step by step and test
  *   You can use .group() to call on the groups of the reg string
  *   <img width="568" alt="image" src="https://github.com/user-attachments/assets/be9a1348-99a2-4435-a797-4fea1067ed08" />
  *   Using (:?) in front of the group will have it ingronred thus groping your .group() count value
  *   <img width="569" alt="image" src="https://github.com/user-attachments/assets/d58c46b0-6863-4512-9135-99b31041b1c5" />
  *   re.split(),re.findall()
