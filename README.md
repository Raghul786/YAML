# YAML
YAML Tutorials
data structures are identified by line separation and indentations
![image](https://github.com/user-attachments/assets/73c5b149-ea32-4026-bfdb-a86259aa036f)

Syntax of YAML
Basic syntax
Key value pairs

#example 1: Key value pairs  
app: user-authentication
port: 9000
version: 1.7

#example 2: Objects
microservice:
 app: user-authentication
 port: 9000
 version: 1.7

#example 3: Lists
 microservices:
  - app: user-authentication
    port: 9000
    version: 1.7
  - app: shopping-cart
    port: 9001
    version: 1.-

#example 4: Booleans
microservices:
 - app: user-authentication
   port: 9000
   version: 1.7
   deployed: false
