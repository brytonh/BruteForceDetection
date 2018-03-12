# BruteForceDetection

### Basic bash scripting to detect brute force attempts

_brute_ : Our bash script

_file.txt_ : Initial log file, such as a maillog file. This is the one we will use for this script. It will be cleared as often as you choose.

_file2.txt_ : This is our "archived" log information, and it will contain all log info in case you need to look back at past entries manually.

_failed.txt_ : Created by the script and will contain failed entries

_tmp.txt_ : Created by script to contain only usernames of those who had logon failures

### Usage: 
For my test, put brute and file.txt in the same directory after you've cloned them 
from here.

Run in the form of: while true; do sleep 300; ./brute; done & 
*OR use your own while loop and put it in the script*.

I recommend using something like zenity or notify-send to send alerts for when
brute force attempts are found. For simplicity, I just outputted the necessary 
notification to screen

