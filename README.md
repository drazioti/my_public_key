# my_public_key
keyid : EB1185F82713D6DF

in bash use : 

`` $wget -q https://raw.githubusercontent.com/drazioti/my_public_key/main/pk.asc && echo -n "key id:" && gpg --list-packets pk.asc | awk '/keyid:/{ print $2 }' && gpg --import pk.asc
``
