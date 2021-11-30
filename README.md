# Guessing passwords using brute-force
# Hashing
# Access Control

Lab 1:
1. In this “lab” problem, you will be working on a Linux Server Virtual Machine (VM). An image of this VM is available (attached with the HW). The VM is having an administrator and 5 users, as shown in the figure below. You don’t have access to any of the users of the Server, to be able to access the Server, you will need to perform password cracking! You were given a line of password hash from (/etc/shadow) for the administrator (admin1) of the Server (attached with the HW).
a. Determine the used hash type of the password.
b. Determine the salt value of the password.
c. Crack the passwords of all users using OpenSSL tool.
Hints:
- It would be useful if you search for Linux shadow file password format.
- You must use the latest OpenSSL version 1.1.1x for this problem. It would be helpful to read about creating Linux password hashes using OpenSSL.
- You can use a password list for your cracking. There is a password list of most used 100K passwords, according to NIST attached with the HW.
- You will need to write some code to iterate through the password list (feel free to use any language you prefer).
- After cracking the password, ensure that you can access the Server.
- Start by cracking the Admin password then after accessing the admin account search for the hashes of the other users on the system
