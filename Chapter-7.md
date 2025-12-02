## Networking Concepts

#### Chapter 7
##### 1. What are SSL and TLS? 
##### 2. What is an SSL certificate? 
##### 3. What is the difference between HTTP and HTTPS? 
##### 4. How does SSL/TLS work? 

#### 1. SSL (Secure Sockets Layer)- 
Secure Sockets Layer is an older security protocol designed to encrypt data sent between a client (like a website) and a server. 

It helps protect information such as passwords and personal data from being intercepted. 

SSL is outdated and no longer considered secure.

#### TLS (Transport Layer Security) - 
Transport Layer Security provides secure communication by encrypting data and ensuring the authenticity and integrity of information over the internet. 

TLS is the modern, more secure version of SSL.

TLS is the protocol currently used in HTTPS connections.

#### 2. SSL certificate - An 
SSL certificate is a digital certificate installed on a web server that: 

Authenticates the website’s identity.

Encrypts data between the user and server.

Shows trust indicators (like the 🔒 lock icon).

It ensures that sensitive information (passwords, credit card numbers, etc.) is protected from attackers.

#### 3. What is the difference between HTTP and HTTPS?

| Feature           | HTTP                                   | HTTPS                                              |
| ----------------- | -------------------------------------- | -------------------------------------------------- |
| Full Form         | HyperText Transfer Protocol            | HyperText Transfer Protocol **Secure**             |
| Security          | ❌ No encryption                        | ✅ Data is encrypted using SSL/TLS                  |
| Data Safety       | Data can be intercepted or modified    | Data is protected from hackers and tampering       |
| URL Prefix        | `http://`                              | `https://`                                         |
| Browser Indicator | No lock icon                           | 🔒 Lock icon in address bar                        |
| Common Use        | Public websites with no sensitive data | Banking, login pages, e-commerce, anything private |

#### 4. How do SSL and TLS work? 

SSL/TLS secures communication between a client (like a browser) and a server (like a website) using encryption and authentication.



