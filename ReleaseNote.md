# Credence-ID-DeviceSDK-Jar
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
