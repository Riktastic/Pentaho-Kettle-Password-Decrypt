# Pentaho Data Integration password decrypter #
## Decrypts passwords that have been stored in a Kettle/Spoon job. ##

Tested with:
- Pentaho Data Integration CE 7.1.0.0-12

Instructions:
1. Open the job/transformation that contains the password in a text editor,

2. Look for an encrypted string that is similar to: 2be98afc86TESTbd63c99dbdde,

3 Open this file in Pentaho Data Integration Spoon,

4 Open the "Input"-step,

5 Navigate to the "Data"-tab,

6 Enter the encrypted password in the "encrypted_password"-field.

7 Execute the job,

8 Check the data of the "Output"-step for the decrypted password.
