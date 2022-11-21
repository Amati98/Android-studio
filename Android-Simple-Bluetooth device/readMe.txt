# Android-Simple-Bluetooth-Example

A simple Android bluetooth example to turn on/off the radio and to view and connect with other devices. It has associated embedded firmware code to connect to an Arduino to test the bi-directional data stream.



## Introduction

This is a simple demo app that creates buttons to toggle ON/OFF the bluetooth radio, view connected devices, and to discover new bluetooth enabled devices. A checkbox and status strings provide functionality to communicate with an embedded microcontroller such as an Arduino. You don't necessarily need to connect an Arduino to still have a functioning phone application. The connected device MUST abide by the Serial Port Profile (SPP). Other complex profiles are not supported with this example and will fail to connect. 

## Required Tools

1. [Android Studio IDE and SDK](http://developer.android.com/sdk/index.html)
2. [HC-06 bluetooth module](https://www.olimex.com/Products/Components/RF/BLUETOOTH-SERIAL-HC-06/resources/hc06.pdf)
3. Arudino Uno 
4. A few breadboard wires to connect the HC-06 to the Arduino


BUILT BY
EMMANUEL AMATI - 00330120
DANIEL WALE - ILGSPE200026
OFORI BRIGHT - ILGSPE200029