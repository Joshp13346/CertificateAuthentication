# CertificateAuthentication
Utilizes a manually generated rootCA.crt to then create and exchange a session key to establish secure communication

# Requirements
cryptography<br>
socket<br>

# Instructions
Start by running Alice.py in CMD 'python Alice.py'<br>
This will listen for a connection on port 65432<br>
Run Bob.py in another CMD 'python Bob.py'<br>
Then, the program will establish connection, create keys, and produce a session key 'rootCA.key'<br>
