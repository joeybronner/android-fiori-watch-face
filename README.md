
Android SAP Fiori Design like
===================================

### Pre-requisites

 - Android SDK 25
 - Android Build Tools v25.0.2
 - Android Support Repository
 - Phone with developer mode activated
 - Watch with developer mode activated

*If developer mode is note activated, go to settings > about and tape 7 times on build number*

### Run it (debug mode with physical watch)

 - Connect your phone to your computer
 - Open "Android Wear" app on phone, activate Debug via bluetooth *(host and target should appear as disconnected)*
 - Open a new command line as administrator
 - Run "adb forward tcp:4444 localabstract:/adb-hub"
 - Run "adb connect 127.0.0.1:4444"
 - *(host and target should now appear as connected)*
