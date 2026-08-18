# Changelog

All changes to mDOS are tracked in this file, per version.

**Release schedule:** \
newly manufactured detectors always ship with the latest build, but we only push a public software update to existing customers once per quarter. Builds marked **Public Release** are available to all customers; builds marked **Internal Build** are on newly built detectors only and will be folded into the next public release. 

#### **Latest public release:** v4.0 - build 7

---

## [v4.0 - build 10] - 2026-08-18
**Internal build**

### Added
- Added support for external gps (NMEA) strings through RS232.

## [v4.0 - build 9] - 2026-08-10
**Internal Build**

### Fixed
- Resolved an issue where the detector always prioritized the Ethernet connection, even when it did not have internet access. The detector now uses Wi-Fi when it has internet access and the Ethernet connection does not.

## [v4.0 - build 8] - 2026-07-29
**Internal Build**

### Changed
- Improved overall system performance.

## [v4.0 - build 7] - 2026-07-23
**Public Release**

### Fixed
- Corrected default device configuration.
- Improved handling of invalid MCF files to prevent loading errors.

## [v4.0 - build 6] - 2026-07-20
**Internal Build**

### Added
- Added support for the Medusa Lidar sensor.

## [v4.0 - build 5] - 2026-07-14
**Internal Build**

### Added
- Initial release of mDOS V4.0. See the [mDOS V4.0 Manual](https://links.medusa-radiometrics.com/mdos-manual) for full documentation.
