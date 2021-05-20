# UsernameGenerator
Simple username generator based on a list of name and surname

## Usage: 
python3 UsernameGenerator.py [input file] [output file]

The input file must be formatted with one name and one surname per line separated by a space.
If you want to test this script, you can use user-example.txt for the input file.
You can also download output-example.txt which is the output of the user-example.txt file.

## Why do I need this script?
This script is useful if you get a name and the surname without knowing the username.
With the output file you can do, for example, the enumeration of kerberos usernames (with the nmap script krb5-enum-users).
You can also enumerate usernames in many versions of OpenSSH (CVE-2018-15473).
