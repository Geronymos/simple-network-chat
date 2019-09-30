# simple-network-chat
A simple network chat with a self-build protocol

## Goal
The goal of this project is a small chat-program, which shall work without a connection to the internet but to a network and that without a main server. 
The program shall have a **G**raphical **U**ser **I**nterface (_GUI_) on which you can type in your targets IP/PC-name, your username and of cause a message. 

## How it should work
For the `GUI` I want to have a look at **Tk** (_Tkinter_). 

The communication in the network shall be solved with an own `socket-protocol`. 

To have a server that can handle _multiple requests_ at the same time and to run the _server_ at the same time as the _GUI_, all the modules should run indepandantly in its own thread thanks to a `threading-library`. 

![Concept for this project](/docs/concept.png)