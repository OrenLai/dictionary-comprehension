dictionary-comprehension practice 

the key word method for it is :
  new_dict = {new_key:new_value for (key,value) in dictionary.items()}

use the items method to get hold of all the key:value pair in the dictionary and loop throught it.
then we can create the new_key and new_value using the key:value pair.
