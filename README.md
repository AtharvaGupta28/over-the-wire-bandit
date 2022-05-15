## Level 0
"ssh username@host -p <port>"
Connecting to ssh usiing command "ssh bandit0@bandit.labs.overthewire.org -p 2220"
Password for level 1 was in readme file - "boJ9jbbUNNfktd78OOpsqOltutMc3MY1"

## Level 1
Used command "cat ./-" to view the dashed file(a file with name as "-")
Password for level 2 "CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9"

## Level 2
File name was "spaces in this filename", in this case replace space with "\ " and use cat command
Password for level 3 - "UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK"

## Level 3
Hidden files can be created using '.' in the beginning of name.
For eg. "touch .Poem"
To view- "cat .Poem"
Use "ls -al" to view any hidden files in the directory
Password for level 4 - "pIwrPrtPN36QITSp3EQaw936yaFoFgAB"

## Level 4
Use command "file -- *", this shows what files contain data and what contain ASCII text(human readable)
Use command "cat -- <filename>" to view files with names stariong with dash
Password for level 5 - "koReBOKuIDDepwhWk7jZC0RTdopnAYKh"

## Level 5
Uses of "find" command - https://www.geeksforgeeks.org/find-command-in-linux-with-examples/
Used command "find -size 1033c" ('c' for bytes)
Password for level 6 in ./maybehere07/.file2 -"DXjZPULLxYr17uwoI01bNLQbtFemEgo7"

## Level 6
Use command "find -size 33c -group bandit6 -user bandit7"
Password for level 7 - "HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs"

## Level 7
Use command "grep <word_to_search> <file_name>" , "grep millionth data.txt"
Password for level 8 - "cvX2JJa4CFALtqS87jk27qwqGhBM9plV"

## Level 8
Used command "sort data.txt" and the manually checked for line that occurs once.
Password for level 9 - "UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR"

## Level 9
Searched data.txt file manually.
Password for level 10 - "truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk"

## Level 10
base64 is a method to encode data and is not a method to encrypt(weak encryption) 
Data in file is encoded through base64 so run the command "base64 -d <file_name>" to decode and "base64 -e <file_name>" to encode a file to base64.
Password for level 11- "IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR"

## Level 11
ROT13
Password for level 12 - "5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu"

