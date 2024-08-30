# DBA Plugins Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!---## [Unreleased]

### Added



### Changed



### Removed

--->

<!--- ## [2.0.1] - 2023-03-05   

### Fixed                
- Some bug fix           --->
## [0.9.12-test] - 2024-08-30

### Changed
- IMAC: now outputs all modes as schedule files with high and limits

## [0.9.11-test] - 2024-08-26

### Fixed
- Container: display of updates amended with additional message
- Installer: location of version check file in installer fixed


## [0.9.10-test] - 2024-08-26

### Added
- *new plugin added*: IMAC Plugin for generating report on neutral operative temperature and 90% acceptance range for 4 building operating modes as defined in he tIMAC model.  

## [2.0.0-test] - 2024-06-01

### Added
- The DBA Plugins 'container application' adds the DBA Plugins menu to DesignBuilder and manages installed plugins, the menu, licences and online version checks.
- Plugin licences are managed through the DBA Plugins menu - licences are updated using 'update licence files' provided by DesignBuilder Software Australia
- There is a single local licence file which contains licences for all plugins (licences remain even if plugins are uninstalled)
- The container application automatically checks for new versions.  If there is a new version of the plugin container application or any _installed_ plugin, a notification will appear in the menu
- The latest installer can be downloaded and run from the plugin menu - the user is prompted to close DesignBuilder to complete the install
- The installer provides ALL plugins - it allows for selecting individual plugins to install
- The *Thermal Comfort and Temperature Check Plugin* (see [Legacy]) has been migrated and is now available through DBA Plugins
- The *HVAC Sizing Plugin* is a new plugin available through DBA Plugins which prepares a report showing data related to HVAC sizing from cooling design run results

### Fixed
- If the location template for the building model was not set, the Thermal Comfort and Temperature Check plugin would fail to produce a report

### Changed
n/a

### Removed
n/a 

## [Legacy] - 2021-03-30

### Stand-alone Thermal Comfort and Temperature Check Plugin
The Thermal Comfort and Temperature Check Plugin was a stand-alone plugin for DesignBuilder.
This plugin produces a report to help with the mandatory thermal comfort and temperature checks required in NCC 2019/2022.
The most recent version (0.5.9) of the stand-alone plugin was released in 2021. 

The thermal comfort plugin is now provided as one part of the DBA Plugins installer, along with additional plugins.
You will need to upgrade to the DBA Plugins application in order to renew your licence, even if you
do not want to install additional plugins.
You can upgrade by running the DBA Plugins installer - no need to uninstall the stand-alone plugin (this will be done automatically).
Your licence for the plugin will be migrated to the DBA Plugins application during this process.



[unreleased]: https://github.com/RebeccaPowles/DBAPlugins
<!--- [2.0.1]: https://github.com/RebeccaPowles/DBAPlugins/compare/v2.0.0-test...v2.0.1  --->
[0.9.12-test]:https://github.com/RebeccaPowles/DBAPlugins/releases/tag/v0.9.12-test
[0.9.11-test]:https://github.com/RebeccaPowles/DBAPlugins/releases/tag/v0.9.11-test
[0.9.10-test]:https://github.com/RebeccaPowles/DBAPlugins/releases/tag/v0.9.10-test
[2.0.0-test]:https://github.com/RebeccaPowles/DBAPlugins/releases/tag/v2.0.0-test
[Legacy]:https://designbuilder.com.au/ncc-2019-temperature-range-check-and-thermal-comfort-plugin