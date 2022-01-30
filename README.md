# QuTech Challenges @ MIT iQuHACK 2022

<p align="left">
  <a href="https://qutech.nl" target="_blank"><img src="https://user-images.githubusercontent.com/10100490/151484481-7cedb7da-603e-43cc-890c-979fb66aeb60.png" width="25%" style="padding-right: 0%"/></a>
  <a href="https://iquhack.mit.edu/" target="_blank"><img src="https://user-images.githubusercontent.com/10100490/151647370-d161d5b5-119c-4db9-898e-cfb1745a8310.png" width="10%" style="padding-left: 0%"/> </a>
</p>


## Description 

Why is encryption necessary ? 
Current Encryption algorithms assume that the breacher or eavesdropper does not has enough Computational Resources or Time to break the Encryption.

But the elegant part about QED is that is based on assumption of the inability of the breacher/hacker to break the fundamental laws of physics.

This is a Demonstration of a Online Chat Application using the BB84 Protocol


### BB84 Protocol
This Protocal utilizes the Heisenbergs Uncertainty Principle for its encryption.


## Description Of the Chat Application

This is a Web Application made on Flask Library as the UI for the Application. 


Flow of the Application:
*The Proposal is that every users has access to a Qunatum Computer or a Quantum Channel which allows transfer of Photons which we will be using as our Qubits

Imagien two Users Alice and Bob, now imagine you are Alice.
-First head on to https://qkd.herokuapp.com/ and login with a Nickname, The Server will provide you a username accordingly, 
Now you can share your username to anyone you would like to talk to, 

- On  https://qkd.herokuapp.com/client you can add someone friend through their user_name. (ofc)

- Lets say you addded Bob#0007 as your Friend
- Once you sent the Friend Req, You are generating in the backend a random string of 500 qubits and measuring them in a random bias and sending the qubits to Bob through the Quantum Channle ( Optical Fibe. new breakthroughs here) to Bob$0007 he recives this as a Friend Request 

If he accepts your Friend Request, he will generate his own random bias ans measure the qubits , Then both the biases of Alice and Bob are shared and the identical indexes are noted the corresponding qubits of these identical Indices will be the key. 


Once both of the parties have the key they can use it to encrypt their messages and talk freely. (antman in the quantum realm might be able to tresspass, no gurantee)

IF EVE- 
NOISE - QUNATUM ERROR CORRECTION

## Actual Workings

The Program can be run locally by acquiring the requiremnets in requirements.txt and running python run.py

^^
The Application currently remains incomplete as of now.

The Encryption and Quantum Inspire and the circuit is useable and works its just the webserver we couldnt finish.
The vision was of a cool website accessible to everyone but it remains incomplete as of now


It was intended to be polished and deployed on heroku or aws but time didnt allow us.





## Team NoSleep

