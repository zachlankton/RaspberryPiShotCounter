# RaspberryPiShotCounter
Raspberry Pi Shot Counter

Install nginx

Copy the shotcounter.service to the /lib/systemd/system folder

Copy the index.html and shot_counter.py files in the /var/www/html folder

Enable and Start the shotcounter.service

systemctl enable shotcounter.service

systemctl start shotcounter.service

