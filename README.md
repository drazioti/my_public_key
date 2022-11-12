# My public pgp key
keyid : EB1185F82713D6DF

in bash use : 

`` $wget -q https://raw.githubusercontent.com/drazioti/my_public_key/main/pk.asc && echo -n "key id:" && gpg --list-packets pk.asc | awk '/keyid:/{ print $2 }' && gpg --import pk.asc
``
<br><br>
Also, I use advanced qualifieid signatures.<br>
Here are my public keys.<br>
[1] [Expired in 9 Nov. 2022](https://repo.harica.gr/cert_info?recvcode=JAUXQCMAFKDQWWXGDJKDWBSFCOPWNJAXEAITOFNLKJNOGEIJGM)<br>
[2] [Expires in 3 Nov. 2024](https://repo.harica.gr/cert_info?recvcode=LCXTVBOTCLPVQJFBVISRWWCOHOIDATTTXNRTDOVODCQKKPLDRK)
