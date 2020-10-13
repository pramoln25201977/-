# -Serial.begin ( 115200 );     / / set the baud rate to 115200 
Serial.Print ( "# 1P800T1000 \ r \ N" );   / / No. S1 pulse is rotated to the position of the steering gear 800, time 1000ms 
delay (1000);   / / delay 1000ms, servos just finished on a command execution
