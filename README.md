  # Image-Encryption

**Encryption** is the process which uses a finite set of instructions called algorithm to convert original message known as plaintext, into _cipher text_ which is its encrypted form.
          The Cryptographic algorithms require a set of characters called _key_ to encrypt or decrypt data. Using this key and the algorithm we can encrypt or decrypt the plain text into cipher text and vice versa.
          **Image encryption** can be defined in such a way that it _is the process of encoding secret image with the help of some encryption algorithm in such a way that unauthorized users can't access it_.Image and video encryption have applications in various fields including internet communication, multimedia systems, medical imaging, Tele-medicine and military communication.   
          There are two types of encryption in widespread use today: **symmetric and asymmetric** **encryption**. The name derives from whether or not the same key is used for encryption and decryption.  
         _**Symmetric encryption**_ is a form of computerized cryptography using a singular encryption key to guise an electronic message. Its data conversion uses a mathematical algorithm along with a secret key, which results in the inability to make sense out of a message.            
        _**Asymmetric Encryption**_, also known as Public-Key Cryptography, is an example of one type. Unlike “normal” (symmetric) encryption, Asymmetric Encryption encrypts and decrypts the data using two separate yet mathematically connected cryptographic keys. These keys are known as a 'Public Key' and a 'Private Key.Asymmetric cryptography offers better security because it uses two different keys -- a public key which only gets used to encrypt messages, making it safe for anyone to have, and a private key to decrypt messages that never needs to be shared. Examples of Asymmetric encryption include Diffie-Hellman Key Exchange(DF), ECC, RSA 

  **RSA (cryptosystem) :** 
RSA (Rivest–Shamir–Adleman) is a public-key cryptosystem that is widely used for secure data transmission.
    In a public-key cryptosystem, the encryption key is public and distinct from the decryption key, which is kept secret (private). An RSA user creates and publishes a public key based on two large prime numbers, along with an auxiliary value. The prime numbers are kept secret. Messages can be encrypted by anyone, via the public key, but can only be decoded by someone who knows the prime numbers.
    

**Algorithm :**
The RSA algorithm holds the following features −
• RSA algorithm is a popular exponentiation in a finite field over integers including prime numbers.
• The integers used by this method are sufficiently large making it difficult to solve.
• There are two sets of keys in this algorithm: private key and public key.

The RSA algorithm involves six steps. They are as follows :    
1)  **Generate the RSA modulus**
    The initial procedure begins with selection of two prime numbers namely p and q, and then calculating     their product N, as N=p*q. Here, let N be the specified large number.
2)  **Derived Number (e)**
    Consider number e as a derived number which should be greater than 1 and less than (p-1) and (q-1).       The primary condition will be that there should be no common factor of (p-1) and (q-1) except 1   
3)  **Public key**    
    The specified pair of numbers n and e forms the RSA public key and it is made public.
4)  **Private Key**
    Private Key d is calculated from the numbers p, q and e. The mathematical relationship between the       numbers is as follows − ed = 1 mod (p-1) (q-1) , The above formula is the basic formula for Extended     Euclidean Algorithm, which takes p and q as the input parameters.
5)  **Encryption Formula**
6)  **Decryption Formula**    
