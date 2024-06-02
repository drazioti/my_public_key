## My public pgp key
``keyid : EB1185F82713D6DF``

in bash use : 

`` $wget -q https://raw.githubusercontent.com/drazioti/my_public_key/main/pk.asc && echo -n "key id:" && gpg --list-packets pk.asc | awk '/keyid:/{ print $2 }' && gpg --import pk.asc
``
<br><br>
If you want to send me an encrypted e-mail use the previous public key and then in bash :
`` $gpg -e -a -r drazioti@csd.auth.gr
``
write your message and when you finish press ``ctrl+D``
<br><br>
Finally send the derived encrypted message to me : drazioti at gmail.com
## X509 public keys
Also, I use "Qualified" [electronic signatures](https://www.harica.gr/en/Products/eSignature).<br>
Here are my public keys.<br>
[1] [Expired in 9 Nov. 2022](https://repo.harica.gr/cert_info?recvcode=JAUXQCMAFKDQWWXGDJKDWBSFCOPWNJAXEAITOFNLKJNOGEIJGM) [p7b](https://github.com/drazioti/my_public_key/blob/main/cert_current.p7b) <br>
[2] [Expires in 3 Nov. 2024](https://repo.harica.gr/cert_info?recvcode=LCXTVBOTCLPVQJFBVISRWWCOHOIDATTTXNRTDOVODCQKKPLDRK) [p7b](https://github.com/drazioti/my_public_key/blob/main/cert_current.p7b) [pem](https://github.com/drazioti/my_public_key/blob/main/cert_current.pem) <br><br>
These keys can not be used for encryption, so you can not use them for this purpose. You can use them for verifying digital signatures.
