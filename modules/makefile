#!/usr/lib/modules/ python

import os

filname = raw_input("what would you like to call it? ")
fildirectory = raw_input("where? ~/")

if fildirectory.endswith("/"):
	fildirectory = fildirectory
else:
	fildirectory = fildirectory+"/"

file = open(os.path.expanduser(os.path.join('~', fildirectory))+filname, 'w')
file.write('')
file.close()
