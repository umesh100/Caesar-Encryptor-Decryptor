## Overview

An approach to encrypt/decrypt words using ceasar cipher.If no key is given, bruteforce method is applied and compared to dictionary

## CaesarEngine
-Takes user input, and stores it in string array using buffer reader
-Takes asks key from user
-Pass each element through encryptor or decryptor method

## Encryptor
-Takes parameter (string,key) and shifts each char from string with   key. if Char>26,Char=A+Key;

## Decryptor
-decrypts by shifting Char=Char-Key. 
-If no key provided , Key =1--26 is assigned and each value is compared  to dictionary

## ToDo
-Make GUI version

## Issues
-Bruteforce not working if a word is substring  of another word from dictionary

-While word is compared to dictionary,likely to find more than one match. In that case, returns all values.



