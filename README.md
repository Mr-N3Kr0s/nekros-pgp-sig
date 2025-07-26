# nekros-pgp-sig

Nekros Azoth --------- PGP Verification

Welcome to the official PGP signature verification repo for the freelance alias Nekros Azoth

Who I am:
I'm a cybersecurity freelancer and privacy consultant operating under this alias. All official deliverables, reports, and statements made through this alias are cryptographically signed using my GPG key. 

What's included:

- nekros_identity.txt: Message of Authorship

- nekros_identity.txt.asc: Detached ASCII Signature 

- nekros_public.asc: My Public GPG Key (for verifying signed data) 

How to Verify:

1. Import the public key

    'gpg --import nekros_public.asc'
    
2. Verify the Signature

    ' gpg --verify nekros_identity.txt.asc nekros_identity.txt'
    
If the output says "Good signature from 'Nekros Azoth'", you've verified me

My Fingerprint:

    C78B 0AD9 F83A 5FCB 4495  D79B 6986 6D9E 153C 5A83
    
______________________________________________________________________________________________________________________________________________________________________________________________
                       EXTERNAL USE
                       
 I link this repo on freelance platforms (Latium, LaborX, etc.) so clients and partners can confirm I am who I say I am.
 
