# W.H.A.T.
Wireless
  Home 
    Automation
      and
        Telemetry
        
Most people consider "Home automation" as just remote control.
While remote control is certianly a piece of any smart home, it is one
of the smaller pieces.

In the WHAT system, pieces are designed in a clever way.  While there is a 
common structure for the messages, each device is unique.  And when it is 
created, each device knows WHAT it is, and should be designed to help the 
rest of the home.  For instance, if ANY device has a clock interface, why 
should it not tell the rest of the network when its time is changed?
Most light switches are near a door.  How hard would it be to add a single
input for an alarm system?  The light switch does not have to be the entire 
alarm, but just dumbly give the state of its alarm input when asked or when 
it changes.

The coffee pot controller should respond to a "Good Morning" command and turn on, 
but it should also monitor if the bedside alarm clock is currently alarming and (if filled)
turn on.  

The garage door should respond to a nighttime "goodnight" message by closing 
if it is open, and reporting back if it is unable (a toy in the way).  It should
also be aware that if the car is remote started (via the network), that it should 
open.

Start by cloning the project:
  Make a directory on your local machine to hold the files.
  use a command prompt to "pull" down the source code:
    git clone https://github.com/MisterE000/W.H.A.T..git --recurse-submodules
