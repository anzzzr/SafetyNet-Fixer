# Universal SafetyNet Fix

Magisk module to work around Google's SafetyNet attestation.

This module works around hardware attestation and recent updates to SafetyNet CTS profile checks. You must already be able to pass basic CTS profile attestation, which requires a valid combination of device and model names, build fingerprints, and security patch levels.

If you still have trouble passing SafetyNet with this module, use [MagiskHide Props Config](https://github.com/Magisk-Modules-Repo/MagiskHidePropsConf) to spoof a certified device profile. This is a common issue on old devices, custom ROMs, and stock ROMs without GMS certification (e.g. Chinese ROMs).

Android versions up to 13 Developer Preview 1 are supported, including OEM skins such as Samsung One UI and MIUI.