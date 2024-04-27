# Temperatures-Monitoring-System
A program for displaying sensor data on an LCD, including max, min, and average values. Temperature range is -30°C to +50°C. The first line of the LCD shows: Ag=xxx M=xxx,xxx (average, max, min). Users can select a channel (1-8) to monitor individually by entering the channel number followed by =. The selected channel's value is displayed on the left of the second line as CHx=xxx. By default, channel one is selected. Additionally, the program displays a message on the second line depending on sensor data:

State=1 if average and max are negative
State=2 if average is negative and max is positive
State=3 if average is positive and at least two sensors are negative
State=4 if sensors #1, #3, #5, and #7 are positive and others are negative.
