# tb6600
TB6600 with stepper motor


-  Start arduino
-  connect with usb
-  start console
-  type:
    *  xon
    *  cdon
    *  s120  // Najbrze sto sam uspio je s80 ali na microstep 32
    *  x3000
    *  mx
    *  xoff



it will:
-  start 6600driver
-  start console output
-  set delay between steps to 60ms
-  set 3000 steps
-  move to preset step position
-  stop 6600 driver

For faster motor set to  microstepping (4 miscrosteps, 800 pulse/rev): 
-  SW1 ON
-  SW2 OFF
-  SW3 OFF

For precize set 32 microstepping (32 miscrosteps, 6400 pulse/rev): 
-  SW1 OFF
-  SW2 OFF
-  SW3 OFF

#  NAJ NAJ BRŽE:
For MAX SPEED set 1 microstepping (1 miscrosteps, 200 pulse/rev): 
-  SW1 ON
-  SW2 ON
-  SW3 OFF
 ## POSTAVITI -->  s350      
 
 
Speed=300  <-- Ne radi, motor pišti
NX=50
X=50
Speed=350 <-- OVO JE LUDA BRZINA
X=50
NX=120
X=120
NX=0
X=0
ENAXOFF


