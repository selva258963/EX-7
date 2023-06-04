# EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND
## DATE : 20.04.2023
## AIM :
To write the python program for simulating Traceroute command
## ALGORITHM :
1. Start the program.
2.Get the frame size from the user.
3.To create the frame based on the user request.
4.To send frames to server from the client side.
5.If your frames reach the server, it will send ACK signal to client otherwise it will sendNACK signal to client.
6.Stop the program
## PROGRAM :
```
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```
## OUTPUT :
![241626143-98a825e4-5c07-49fa-81b1-e2a40722c95a](https://github.com/Amruthavarshnibs/EX-7/assets/119103704/016f2bb6-1e05-49b0-920f-2d7bb152af05)
## RESULT:
Thus, the python program for simulating Traceroute command was successfully executed.
