# Credence-ID-DeviceSDK-Jar

## Version 5.5 Release note
### Change
- Face analyze liveness verification has been deactivated for Neurotech provider

## Version 5.3 Release note
### Fix
- Fix calibrateFingerprintReader() API internal issue.

## Version 5.2 Release note
### New
- Added support for New CredenceECO device using the same APIs
- New calibrateFingerprintReader API has been added.

Allows calibration of the fingerprint reader. Support for CredenceECO only.
New getDeviceHardwareIdentifiers API has been added.
Return the device hardware information if available (deviceSerialNumber, imei, androidID, wifiMacAddress,etc...)

### Change
- OnFingerprintGrabbedListener callback for grabFingerprint has been deprecated.

It is recommanded to use OnFingerprintGrabbedNewListener instead. Change has been made to overcome the Android10 and above constraints on SDcard file access.

- EPassport MRZ Scanner Library has been upgraded

It has been upgraded to support Android 9 Version running on CredenceTAB. N
More algorithms providers for BIOMETRIC APIs enabled

###Neurotechnology fingerprint and face matching algorithms are now available for all devices
- Innovatrics fingerprint and face matching algorithms are now available for all devices
- Vision LAB (Luna Face SDK) is only available for CredenceTAB and CredenceTWO (CredenceECO not yet supported)


## Version 4.2 Release note
### New
- calibrateFingerprintReader API has been added.

Allows to callibrate the fingerprint reader.
Support for CredenceECO only.

- getDeviceHardwareIdentifiers API has been added.

Return the device hadware information if available
(deviceSerialNumber, imei, androidID, wifiMacAddress,etc...)

### Change
- OnFingerprintGrabbedListener callback for grabFingerprint as been deprecated.

It is recommanded to use OnFingerprintGrabbedNewListener instead.
Change has been made to overcome the Android10 and above constraints on SDcard file access.

### Corrections
