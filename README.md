# BruteForceDetection

### Basic bash scripting to detect brute force attempts

file.txt : Initial log file, such as a maillog file. This is the one we will use for this script. It will be cleared as often as you choose.
file2.txt : This is our "archived" log information, and it will contain all log info in case you need to look back at past entries manually.
failed.txt : Created by the script and will contain failed entries
tmp.txt : Created by script to contain only usernames of those who had logon failures

### Usage: 
Run in the form of: while true; do sleep 300; ./brute; done &
I recommend using something like zenity or notify-send to send alerts for when
brute force attempts are found. For simplicity, I just outputted the necessary 
notification to screen

