# ChangeLog
AlcoMeasure copyright 2024 All-Systems Electronics PTY LTD

## [1.3052] - 2024-11-18
### Fixed
- No longer fails to send an email if there is no subject.
- Lines in the email body are no longer in danger of going over the RFC limit.

## [1.3051] - 2024-06-19
### Fixed
- Modified configuration of RTC to make it more robust against RF.

## [1.3050] - 2024-05-30
### Fixed
- Bug causing emails to not send.

## [1.3049] - 2024-04-29
### Changed
- SMTP name length increased to 60 characters from 50.
- Added better handling of corrupted logs.
-- Fixes log syncing issue with AMS/AMU.
-- Fixes log mirroring to SD Card.
### Fixed
- Bug causing random network dropout for 18 minutes.
- Bug causing corrupted network packet on retransmission.

## [1.3032] - 2023-08-14
### Fixed
- Bug causing the daily log report download to not display date/time when embedded in email.
- Improved stability of image downloads from camera.

## [1.3030] - 2023-08-09
### Changed
- Modified sample system auto-actuation pause time from 2s to 3.5s.
  - Only relevant during servicing.

## [1.3029] - 2023-07-27
### Fixed
- Fixed user validation bug in IMX units during a formal test.

## [1.3028] - 2023-07-27
### Fixed
- Fixed bug stopping camera from working in K60 units.

## [1.3027] - 2023-07-18
### Fixed
- Fixed bug causing iButton to not work.

## [1.3026] - 2023-07-18
### Fixed
- Fixed bug where PRINT_REPLY_ERROR flag was getting set when printer was disabled.

## [1.3025] - 2023-07-10
### Changed
- Added support for Omni Printer
### Fixed
- Fixed bug where extra button presses were sometimes detected.

## [1.3019] - 2023-05-05
### Changed
- Improved RF robustness of external I2C bus.

## [1.3012] - 2023-04-14
### Fixed
- Fixed bug causing the RTC to sometimes be read incorrectly on startup.
- Fixed bug causing test count to get corrupted.

## [1.3009] - 2023-03-30
### Changed
- Changed distributor and service level passwords.
### Fixed
- Fixed ethernet bug in IMX unit that caused the device to randomly reset.
- Fixed bug causing failure to calibrate in older units.
  - Introduced in 1.3000.
  - Only affects K60 units connected to Series 1 Sample Systems.
- Fixed bug causing RTC compensation to be set incorrectly in K60 units.

## [1.3003] - 2023-03-23
### Fixed
- Fixed bug where 2nd photo wasn't being taken.
- Fixed bug causing USB to not auto-connect if USB cable is connected on startup.

## [1.3000] - 2023-03-22
### Changed
- Added support for IMX processor board.
- "Service Due" message can now be disabled along with the annual service message.

## [1.2001] - 2022-10-10
### Fixed
- Fixed bug causing Series 1 fuel cell/pressure signals to not read properly.
- Fixed bug in Alcohol settings menu where thresholds weren't displayed properly.

## [1.2000] - 2022-09-13
### Changed
- Updated for AlcoMeasure WM1 Series 2.
- Includes changes to communicate with new sample systems that incorporate fuel cell/pressure sensor signals onboard.
- Is backwards compatible with WM1 Series 1 (not including MK60DN512Z marked MCU's)
