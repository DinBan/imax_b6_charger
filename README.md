# iMax B6 Charger stuff

This includes a couple of very basic examples of getting serial data from the imax B6 charger.
There is a lot of room for improvement, but I don't really use my B6 anymore.

**imax_b6_wifi.ino:**   
 * Designed for use with an ESP8266
 * Connects to your wifi
 * Runs a web server that will output status while you are charging
 * Standalone

 
**imax_b6_charger.ino**
 * Use with just about any Arduino, outputs to Serial terminal

**imax_charger.ps1**
 * Sample PowerShell script
 * Use with the imax_b6_charger.ino sketch
 * Set the variables and then start this after charging begins.  It should output information as it come in... when the response stops, it will attempt to send an email.

In action:
https://youtu.be/cKINBt144Qs