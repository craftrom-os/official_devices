### Changelog 3/03/2024
1. **Audio Policy:**
   - Anonymized Bluetooth MAC addresses.
   - Updated MTP packet buffer.
   - TunerService now prevents Null Pointer Exception.

2. **Framework and System:**
   - VoNR enabled by default.
   - Implemented Live Volume Steps.
   - Color optimization in SystemUI for charging animations.

3. **Settings:**
   - Enabled copying content for IMEI2.
   - Improved user profile sorting in Settings.
   - Added options for additional volume steps.
   - Long-press feature to copy Wi-Fi passwords.
   - Updated security string to 2024-02-05.

4. **Vendor and Kernel Enhancements:**
   - Vendor AOSP now uses release-keys for any build status.
   - Updated Pixel charger animation.
   - Kernel now allows custom user and host strings.

5. **Common Module Optimization:**
   - Enabled R8 optimizations for system_server and SystemUI.

6. **Reverted Changes:**
   - **System Stability Fixes:**
     - Several previous modifications were reverted due to issues causing rom instability and crashes.

---

### Changelog 25/02/2024
1. **Camera:**
   - Added support for various camera formats.
   - Resolved issue of overwriting camera settings.
   - Enabled retrieval of preview frames for enhanced preview.
   - Allowed privileged camera apps to create raw data streams.

2. **Audio:**
   - Restricted suspension of certain audio effects.
   - Introduced support for new audio file and format.

3. **Frameworks/System:**
   - Optimized media data processing for improved performance.
   - Addressed memory and code optimization issues.
   - Enhanced user interface and interaction, including animations and colors.
   - Introduced new standards and technologies, such as VoNR.
   - Resolved security and stability issues, including preventing app crashes.

4. **Additional Changes:**
   - Introduced immersive navigation feature.
   - Removed unused or redundant elements.
   - Allowed customization of user and host strings.
   - Removed duplicate Pixel Launcher category.
   - Enabled circle-to-search feature.
   - Provided inheritance of certification repository.
   - Enabled monochromatic "monet" style.
   - Disabled AiAi translation service usage.

5. **Settings:**
   - Added black background overlay feature.
   - Enabled content copying for IMEI2.
   - Fixed user profile sorting, now sorted alphabetically.
   - Added options for real-time volume step adjustments.
   - Removed duplicated volume step declarations.
   - Added toggle for AOSP/Google battery graphs.
   - Added long-press functionality to copy Wi-Fi password.
   - Added toggle for 60Hz refresh rate on battery saver mode.
