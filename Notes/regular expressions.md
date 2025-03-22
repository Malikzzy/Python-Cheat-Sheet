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
  *   hjkh
