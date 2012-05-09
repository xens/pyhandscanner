# pyhandscanner

## About
pyhandscanner connects to serial hand-held barecode scanner and print the barcode to stdout.

## History
I have a Metrologic MS9535 Bluetooth hand-held scanner, the scanner connects to a base-station 
via Bluetooth, the base station is then connected via USB to the computer. Recently the base-station
failed and the scanner was useless. I deceided to connect the scanner directly to the computer via
Bluetooth and bypass the base-station. I wrote this script to read the output of the scanner and
display it to the focused windows (console, libreoffice, ...). This should also work with serial
scanners.

## Requirements 
- Bluetooth or serial scanner
- Bluetooth dongle
- crikey software installed (used to display the barcode to the selected windows)


