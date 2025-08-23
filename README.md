PKI (Public Key Infrastructure): 

 This script demonstrates a complete Public Key Infrastructure (PKI) workflow in Python:
•	Certificate Authority (CA) Creation
•	Generates a CA private key and a self-signed X.509 root certificate.
•	User Key Pair & Certificate
•	Generates a user RSA key pair.
•	Creates a user certificate signed by the CA, establishing trust.
•	Message Signing
•	Signs a message with the user’s private key to ensure authenticity and integrity.
•	Signature Verification
•	Uses the user’s public key from the certificate to verify the signature.


