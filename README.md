# EcoA10 Library for Android
The EcoA10 library for Android projects.

## Introduction
EcoA10 Library (EcoA10) permits the intercomunication between the applications and the payment terminal served by Ecopaynet. Fast, easy and powerful.

The developer of the Android application only needs to worry about the amount of the transaction, the rest of the work is made by the EcoA10.

EcoA10 communicates with Bluetooth and Serial Port payment terminals. This terminals are robust and secure, certified to make card payments using the following input methodes: contactless, NFC, chip, magnetic stripe and manual input.

Integrated on the Android project, the EcoA10 generates this most important entry points:
 - Initialization of EcoA10
 - Sale transaction
 - Refund transaction
 - Ticket generation (PDF, Image, Text)

## Prerequisites
EcoA10 needs the next prerequisites to work:
 - Android minimum SDK version 15 (4.0.3 Ice Cream Sandwich).
 - Internet connectivity (GPRS, Wifi, Ethernet...).
 - Bluetooth capabilities (if communicate with bluetooth terminals is needed).
 - USB Host port (if communicate with serial port terminals is needed). USB OTG dongle also can be used.

## Installation
EcoA10 come's in an Android Java Library (AAR) format. This format can integrated on the Android project. We recommend the use of the Android Studio IDE.

Steps to integrate the EcoA10 library on your Android Studio project:
 1. Open your Android Studio project	
 2. Once it's opened, go to menu "File" -> "New" -> "New Module..."	
 3. Select "Import .JAR/.AAR Package" and click "Next"	
 4. On the "File Name:" option select the EcoA10 AAR Library file. You can find it in the "com.ecopaynet.ecoa10" folder of the 	"Getting Started" project. Then click "Finish".	
 5. When the EcoA10 is integrated on your Android Studio, the next step is to make the reference on your project. To make this, go to "File" -> "Project Structure..."	
 6. Select your application project, click the "+" button and select the "Module dependency" option.	
 7. Choose the "com.ecopaynet.ecoa10" module and click "OK".	
 8. Click "OK" on the opened "Project Structure" window.

Once this steps are done and Gradle Sync has finished integrating EcoA10 on your project, you will be able to call any method of the EcoA10 Library.
	
## Getting Started
See our [Android EcoA10 Getting Started](https://github.com/ecopaynet/Android-EcoA10-Getting-Started) project.
 
## License
EcoA10 is copyright of Ecopaynet SL
