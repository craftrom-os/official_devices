# CraftRom OS

## Official devices application

Before you apply to add your device into our list of official devices, you should know a few things:

### 1. How to apply?

You must fulfill the following requirements before applying:

- [Maintainers requirements](https://github.com/craftrom-os/docs/blob/master/maintainers_requirements.md)

- [Device requirements](https://github.com/craftrom-os/docs/blob/master/device_requirements.md)

- [Maintainers' code of conduct](https://github.com/craftrom-os/docs/blob/master/maintainers_code_of_conduct.md)

You must be aware that just fulfilling these requirements doesn't necessarily mean that you're going to be accepted. We will also consider some other points if necessary, like experience or how your behavior is towards other people (users or otherwise), and even with some technical stuff.

### 2. JSON params

##### devices.json

| Param        | Description                                                                 | Required |
| ------------ | --------------------------------------------------------------------------- | -------- |
| name         | Device name                                                                 | Yes      |
| brand        | Device manufacturer                                                         | Yes      |
| codename     | Device codename, eg: falcon                                                 | Yes      |
| version_code | Version code (ten or ten_plus)                                              | Yes      |
| repositories | Array containing needed repositories by your device                         | Yes      |
| stable       | Set to false if the version is beta (true by default)                       | No       |
| deprecated   | Set to true if the device is no longer maintained (false by default)        | No       |
| xda_url      | Url to thread in xda-developers forum                                       | No       |
| telegram_url | Telegram related group/channel url (full url that starts with https://t.me) | No       |

##### team/maintainers.json

| Param           | Description                                                                                                         | Required |
| --------------- | ------------------------------------------------------------------------------------------------------------------- | -------- |
| name            | Your name (or nickname)                                                                                             | Yes      |
| country         | ISO-3166 Alpha 2 code of your country (2 digits, you can get from https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) | Yes      |
| ci_username     | Alphanumeric username, to be used in our CI                                                                         | Yes      |
| github_username | Your GitHub username (eg: https://github.com/melles1991/)                                                           | Yes      |
| devices         | Array with the device and the respective version that you maintain                                                  | Yes      |
| xda_url         | Direct url of your XDA profile (eg: https://forum.xda-developers.com/member.php?u=6519039)                          | No       |
| telegram_url    | Direct url of your Telegram profile                                                                                 | No       |

### 3. Device Image

We need a .png image with transparent background with sane quality with at least the device front being shown for our website. Those will go to the images folder with the filename being called as <device_codename>.png.

If you agree with everything, please [fill this form](https://github.com/craftrom-os/official_devices/issues/new/choose)
