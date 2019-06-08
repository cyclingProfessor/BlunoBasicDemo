BlunoBasicDemo
=======================

# _Brief_

_Description: This basic Bluno M3 communictor is updated for Post version 23 security.  It also now uses buttons to send strings to the Bluno.

## BLE Details

*DF Robot Service:*
Id: 0000dfb0-0000-1000-8000-00805f9b34fb

*DF Robot Characteristics:*
Name: Serial Port
Id: 0000dfb1-0000-1000-8000-00805f9b34fb
  
Name: Command
Id: 0000dfb2-0000-1000-8000-00805f9b34fb

*DF Robot Descriptors:*
(**same for both characteristics**)
Name: Read
Name: WriteWithoutResponse
Name: Write
Name: Notify

## Project Setup

## License

_GPLv3_

## To DO
Fix the code so that it is a bit (a lot!) prettier.
Move the Scan function to a Menu/Status with auto connect (first Bluno M3).