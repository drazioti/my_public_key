# my_public_key
keyid : EB1185F82713D6DF

in bash use : 

`` $wget https://raw.githubusercontent.com/drazioti/my_public_key/main/pk.asc && gpg --list-packets pk.asc | awk '/keyid :/{ print $2 }' ``
