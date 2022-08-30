# MIFlash
For Disable Camera Notification

Commands:
adb devices

Disable notification camera_mic_icons:

Code:
adb shell cmd device_config put privacy camera_mic_icons_enabled false

Disable notification location_indicators :
Code:
adb shell cmd device_config put privacy location_indicators_enabled false 

Re-enable, replace "false" with "true"
