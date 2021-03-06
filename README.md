# BLE Peripheral Simulator

The BLE Peripheral Simulator is an Android app that allows developers to try
out new features of Web Bluetooth without the need for a BLE Peripheral Device.

You can build it from source or install it from the [Google Play Store](https://play.google.com/store/apps/details?id=io.github.webbluetoothcg.bletestperipheral).

A developer can use the app to simulate a BLE Peripheral with one of two services:

* Battery Service
* Heart Rate Service

The developer can use the new Web Bluetooth features to connect to the app to Read and Write Characteristics, and Subscribe to Notifications for when the Characteristics change.

From the app a developer can set the characteristics' values and send notifications.

![Battery Service](Battery Service.png) ![Heart Rate Service](Heart Rate Service.png)

### Caveats

BLE peripheral mode was introduced in Android 5.0 Lollipop. Due to hardware chipset dependency, some devices don't have access to this feature. Here's a non-exhaustive list of devices that support BLE peripheral mode at the time of writing: Nexus 6, Nexus 9, Moto E 4G LTE, LG G4, Galaxy S6.

Source: http://stackoverflow.com/questions/26482611/chipsets-devices-supporting-android-5-ble-peripheral-mode

