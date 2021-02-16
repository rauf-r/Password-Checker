
You should use run the program from the command_prompt/terminal, do not run it in IDE.

Your command shold look like this:

python3  pswdcheck.py  password123

#password123 - example of password you want to check

the password you are checking is not going to be sent fully, program turns it into SHA1 hash and requests the list of identical the first 5 and last 5 characters of the hash and compares them and returns to you the result of match.  

your checking password remains incognito ;-) 