# Ex-11---ELLIPTIC-CURVE-CRYPTOGRAPHY-ECC-
##AIM:

To implement the Elliptic curve Cryptography
##ALGORITHM:
STEP-1:
Alice and Bob agree on the elliptic curve equation, base point G, and prime modulus p.
Step 2:
Alice selects a random private key a and computes her public key 𝐴 =𝑎⋅𝐺
Step 3:
Alice sends her public key A to Bob.
Step 4:
Bob selects a random private key b and computes his public key B=b⋅G.
Step 5:
Bob sends his public key B to Alice.
Step 6:
Alice computes the shared secret key as Secret=a⋅B. Bob computes the shared secret key as
Secret=b⋅A
