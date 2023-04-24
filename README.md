# Hacking
This tool enables you to identify the existing Internet name and information about it 
import string
from random import *
characters = string.ascii_letters + string.punctuation  + string.digits
password =  "".join(choice(characters) for x in range(randint(8, 16)))
print (password)
