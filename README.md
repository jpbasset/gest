gest
====

python heating and home domotics manager based on raspberry pi

Aim is to creat a simple python script to manage my home heating system. As big domotics system does exist, they are too big to me.

The raspbeery pi is the protype board, first it runs with a piface digital I/O board. It will have no display, as there are enough displays in a house and will be commanded by http on phone, tablet, pc etc 

I will programm in following steps:

1) simple event logger (log HC Heure Creuse time where electricity is cheaper in France)
    1.1 as a script, write log to a file
    1.2 as a daemon, write log to a file
    1.3 .., write to sql DBase
    1.4 .., optional mail send
    
2) simple acuator manager (will start dishwasher when HC)
    2.1 time mangement, as NTP implement (no real time clock on the rapsberry)
    2.2 if required, start dishwasher when HC
    2.3 if the loundry wash machine last standard for 1h, start 1h befoire HC ends
    
3) heating control and manage
    3.1 for electrical heating with 1 pilot wire

4) html interface to command all that
    4.1 choose framework

Please feel free to contribute, this project will be very very slow as I'm busy with quite a lot of other works.
