# Secure-File-Storage-Using-Hybrid-Cryptography
In Cloud Computing, we share data among many clients, servers and people. The security of information present in the cloud is not guaranteed as it is susceptible to data breaches. As computational power is increasing, older encryption methods are becoming easy to bruteforce. So, there is a requirement to do cross breed encryption to protect the data.

Recent innovations in the internet and the network applications and the wide spread use of the technology, it is now completely possible to conduct electronic commerce on the internet or through the local area networks. This promotes many users to transfer files and sensitive information through the network .It requires a special deal to store the sensitive data on cloud as well. How can we provide better security to file transfer?

We combine Blowfish algorithm and SRNN to perform half breed encryption. The encrypted files, encrypted blowfish keys, and public SRNN keys are sent and received. When the receiver wants to decrypt, we will provide the SRNN private key. The SRNN private keywill
be decrypted to get the blowfish key. By using this blowfish key the encrypted file will bedecrypted.





# Modules

### 1.Encryption Phase
1. Blowfish key is generated and files are encrypted using that. 

2. The generated Blowfish key is encrypted using SRNN encryption. 

3. SRNN private key is stored safely and encrypted files, encrypted blowfish key, SRNN public key is sent. 

### 2.Decryption Phase
1. SRNN private and public keys are used to decrypt Blowfish keys. 

2. The Blowfish key is used to decrypt the files.

# Algorithms
### 1. Blowfish

➢ Blowfish is a secret keyed, symmetric cryptographic block cipher. 

➢ There are 16 rounds of iterative encryption and decryption functional design. 

➢ It consists of two phases: Key Expansion phase and Data Encryption phase.

### 2. SRNN: Short Range Natural Numbers

➢ The SRNN is a public keyed, asymmetric cryptography calculation. 

➢ In addition to two prime numbers, two more short natural numbers are generatedandused in the encryption function. 

➢ Security is equivalent to 2 key pair RSA

➢ Faster encryption than RSA.
