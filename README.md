# tb6600
TB6600 with stepper motor


-  Start arduino
-  connect with usb
-  start console
-  type:
    *  xon
    *  cdon
    *  s120  // Najbrze sto sam uspio je s80
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
