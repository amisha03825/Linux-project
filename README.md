#step1:vi digi_watch.sh
#!/bin/bash

while true
do 
    clear
    echo $Blue $(date +%T)
    sleep 1s
done
#step2:
chmod 777 digi_watch.sh
#step 3:
./digi_watch.sh
