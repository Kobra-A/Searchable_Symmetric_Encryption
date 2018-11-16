# Searchable_Symmetric_Encryption

##If you have other versions of python make sure they don't conflict

###Program written in python3.6
- to run program type: python3.6 SSE.py

###Packages Installed
- Cryptography. To install type pip3 install cryptography

##Functions so far

###Main
-Welcomes user to progam
-Then ask if already have encrypted data or not.
-if yes enter existing password. We will do the searching in this part.
-elif ask you to choose a password. Then ask for documents that you want encrypted.
-else is a error check for the yes or no.
-Can uncomment print statements to see the keys. Can uncomment the for loop to see the D(w) dictionary.

###Keygen
-Creates three keys from the user entered password
-uses three previously randomly generated salts to alter password for each key.
-returns the three keys base 64 encoded. For neatness.

###Initialization
-Reads in the filenames stores in a list.
-Reads the files data and finds the 5 most common words in each file.
-Makes a masterlist of all the top 5 words in all documents. Removes duplicates.
-Makes a dictionary with the word as the key and the value is a list to document identifiers.
-returns the D(w) dictionary.


