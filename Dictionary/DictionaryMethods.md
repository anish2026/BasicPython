### Various dictionary methods 

Python provides us following methods to work upon dictionary object:

## clear()
Just clear all items of dictionary and return an empty dictionary
use as .clear()
## copy()
Make copy of any dictionary 
use as .copy()
## setdefault()

The setdefault() takes maximum of two parameters:

    key - key to be searched in the dictionary
    
    default_value (optional) - key with a value default_value is inserted to the dictionary if key is not in the dictionary.
    If not provided, the default_value will be None.
    
The setdefault() returns:

     value of the key if it is in the dictionary

     None if key is not in the dictionary and default_value is not specified

     default_value if key is not in the dictionary and default_value is specified


## get()
Just search if the given element is present or not, takes at least one argument

## items()
Iterate for items present in the dictionary in key: value pair

## keys()
Iterate for keys in dictionary 

## pop()
Pop out the given key's value, it also takes at least one argument 

## popitem()
Pop out the last key:value pair of the dictionary and takes no argument

## update()
Just join two dicts by updating and overwriting one another 

## values()
Iterate for values in the dictioanry
