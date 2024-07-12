# aspsp-phone-app
This repository contains the ionic phone executable for the Nuapay Test ASPSP
- This application is intended to be used on our sandbox environment. https://sandbox.nuapay.com
- The executable is called **universal.apk** for Android
- The executable is called **App.ipa** for IOS
  
    
# Purpose
This application simulates a banking application, this will allow you to test
- making payments
- denying payments
- deeplinking activation of the banking app

# How to install this apk for Android
- Browse to the apk file.
- Select the file to start the installation.
- You’ll receive a warning at the bottom of the phone letting you know that you must give that app permission to install the file.
    - Tap the Settings button to proceed.
    - On the next page agree to allow the app to make APK installs.
    - You will be prompted to Install the app. Go ahead and follow the instructions to install.

# How to install this ipa for IOS via an Apple Computer
- Connect your iOS device via USB, then open Xcode
- From the Window menu, select "Devices and Simulators"
- Select your device from the list of devices, then use the "+" sign to install the .ipa.
- Thats it!

# How to install this ipa for IOS Using iTunes (Legacy Method)
This method works with older versions of iTunes (12.7 or earlier), where app management is still available.
- Install an Older Version of iTunes: Download and install iTunes 12.7 or earlier from Apple's iTunes download page.
- Connect Your iPhone: Connect your iPhone to your Windows computer using a USB cable.
- Add IPA to iTunes:
    - Open iTunes and go to the "Apps" section.
    - Drag and drop your IPA file into iTunes.
 - Sync Your iPhone:
    - Select your device in iTunes.
    - Go to the "Apps" tab and ensure your app is checked.
    - Click "Sync" to install the app.

# Logging in
The application will only be invoked via deeplinking, you should never need to start the application yourself.
See the developer docs at https://developer.nuapay.com for more test bank details
 - https://developer.nuapay.com/ob_sandbox.html

# Credentials
 - Username: psu
 - Password: psu

