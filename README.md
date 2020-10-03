# Train-Sim-Server
Server application written in Python for communication with Train Simulator 2020, also called RailWorks. 

#### Commands for communinication with Train Simulator:
```
  GetCV(NumberOrNameOfControlValue,wantedState)::  
  SetCV(NumberOrNameOfControlValue,ValueToWrite)::
  GetControlList()::
  GetTime()::
  GetLocoName()::
  ```
  Possible wanted states are 0=actual, 1=minimum, 2=maximal.
  
 Communication with server is possible on port 8888 and IP address of the computer it is running on.
