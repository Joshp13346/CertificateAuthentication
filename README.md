# CertificateAuthentication
Utilizes a manually generated rootCA.crt to then create and exchange a session key to establish secure communication

# Requirements
cryptography
socket

# Instructions
Start by running Alice.py in CMD 'python Alice.py'
This will listen for a connection on port 65432
Run Bob.py in another CMD 'python Bob.py'
Then, the program will establish connection, create keys, and produce a session key 'rootCA.key'
