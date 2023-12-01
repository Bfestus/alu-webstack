# alu-webstack
# Let's have some understanding on HTTPS AND SSL

# HTTPS and SSH

## HTTPS (Hypertext Transfer Protocol Secure)

HTTPS is an extension of HTTP (Hypertext Transfer Protocol) designed for secure communication over the internet. It adds a layer of encryption using SSL (Secure Sockets Layer) or its successor, TLS (Transport Layer Security).

### How HTTPS Works

1. **Handshake:** A secure connection is initiated between the client (e.g., web browser) and the server through a handshake process.

2. **Certificate Verification:** The server presents an SSL/TLS certificate to the client, which is verified for authenticity and validity.

3. **Key Exchange:** A session key is generated through a key exchange process, establishing a secure connection.

4. **Encrypted Data Transfer:** Data exchanged between the client and server is encrypted using the established session key, ensuring privacy and security.

5. **Data Integrity:** HTTPS ensures that the transferred data remains unchanged from the original, maintaining data integrity.

## SSH (Secure Shell)

SSH is a cryptographic network protocol for secure communication over an unsecured network. It is commonly used for remote access to systems and secure file transfers.

### Key Features of SSH

1. **Authentication:** SSH uses cryptographic keys for user authentication, providing a secure alternative to traditional password-based logins.

2. **Encryption:** All communication between the client and server is encrypted, preventing unauthorized access to sensitive information.

3. **Tunneling:** SSH supports tunneling, allowing the secure transfer of other network protocols over its encrypted connection.

4. **Secure File Transfer:** SCP (Secure Copy Protocol) and SFTP (SSH File Transfer Protocol) are commonly used with SSH for secure file transfers.

### How SSH Works

1. **Key Pair Generation:** Users generate a key pair consisting of a private key (kept secret) and a public key (shared).

2. **Key Exchange:** The public key is placed on the server, and during connection, the server verifies the user's identity using the private key.

3. **Encrypted Communication:** Once authenticated, all communication between the client and server is encrypted, ensuring confidentiality.

### Conclusion

Both HTTPS and SSH play critical roles in securing online communication. HTTPS is vital for secure web browsing, protecting sensitive data during transactions. SSH, on the other hand, provides a secure means of accessing and managing remote systems.

These protocols are fundamental in creating a safer and more private online and networked environment.

written by: Festus
