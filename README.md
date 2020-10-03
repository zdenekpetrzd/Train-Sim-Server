# Train-Sim-Server
Server application written in Python for communication with Train Simulator 2020, also called RailWorks. 

#### Commands for communinication with Train Simulator:
```
  GetCV(NumberOrNameOfControlValue,wantedState)::  Possible wanted states are 0=actual, 1=minimum, 2=maximal.
  SetCV(NumberOrNameOfControlValue,ValueToWrite)::
  GetControlList()::
  GetTime()::
  GetLocoName()::
  ```
  
  
Communication with server is possible on port 8888 and IP address of the computer it is running on.

Created for project Loco simulator 362/363, which you can see here https://www.youtube.com/watch?v=p-Ftj1BDMz8.

Made possible thanks to https://github.com/piotrkilczuk/py-raildriver.
