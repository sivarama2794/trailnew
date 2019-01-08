# HTS Help File
This is intended as a quick reference on how to work with the Howell Test Software and also to showcase different features of HTS.

TESTER
======
> Below are the steps and general syntax on how to run the Howell Test Software. 


MSG command
------
msg command is to Give instructions to the user on how to proceed with the test Procedure

> msg Syntax
```
msg,Window Caption,Message to be shown in the Pop up window
```
>msg sample
```
msg,Power,Power Off the Unit
```
ACK command
------
> ack command is to get the acknowledgement from the Tester and record a value
```
ack,,Power OFF
```
