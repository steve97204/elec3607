command: make
record from the sound card and use sox to transfer it to 12000HZ mono, then decode mono file

command: make pulse 
connect to the pulseaudio and read from pulseaudio, here we used the raw data sample, we can also use other generated files and decode them by simply replace the filename after paplay in wsprwait1
