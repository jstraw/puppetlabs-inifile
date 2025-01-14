# Change log

All notable changes to this project will be documented in this file. The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](http://semver.org).

## [v6.0.0](https://github.com/puppetlabs/puppetlabs-inifile/tree/v6.0.0) (2023-04-11)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/v5.4.1...v6.0.0)

### Changed

- \(CONT-783\) - Add puppet 8 support/Drop puppet 6 support [\#505](https://github.com/puppetlabs/puppetlabs-inifile/pull/505) ([jordanbreen28](https://github.com/jordanbreen28))

## [v5.4.1](https://github.com/puppetlabs/puppetlabs-inifile/tree/v5.4.1) (2023-04-06)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/v5.4.0...v5.4.1)

### Fixed

- pdksync - \(CONT-189\) Remove support for RedHat6 / OracleLinux6 / Scientific6 [\#492](https://github.com/puppetlabs/puppetlabs-inifile/pull/492) ([david22swan](https://github.com/david22swan))
- pdksync - \(CONT-130\) - Dropping Support for Debian 9 [\#489](https://github.com/puppetlabs/puppetlabs-inifile/pull/489) ([jordanbreen28](https://github.com/jordanbreen28))

## [v5.4.0](https://github.com/puppetlabs/puppetlabs-inifile/tree/v5.4.0) (2022-10-03)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/v5.3.0...v5.4.0)

### Added

- pdksync - \(GH-cat-11\) Certify Support for Ubuntu 22.04 [\#484](https://github.com/puppetlabs/puppetlabs-inifile/pull/484) ([david22swan](https://github.com/david22swan))
- pdksync - \(GH-cat-12\) Add Support for Redhat 9 [\#480](https://github.com/puppetlabs/puppetlabs-inifile/pull/480) ([david22swan](https://github.com/david22swan))

### Fixed

- \(MAINT\) Drop support for Solaris 10, Windows Server 2008 R2, and AIX 5.3 and 6.1 [\#485](https://github.com/puppetlabs/puppetlabs-inifile/pull/485) ([jordanbreen28](https://github.com/jordanbreen28))
- Fix broken idempotency with empty sections [\#483](https://github.com/puppetlabs/puppetlabs-inifile/pull/483) ([kajinamit](https://github.com/kajinamit))

## [v5.3.0](https://github.com/puppetlabs/puppetlabs-inifile/tree/v5.3.0) (2022-05-23)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/v5.2.0...v5.3.0)

### Added

- pdksync - \(FM-8922\) - Add Support for Windows 2022 [\#468](https://github.com/puppetlabs/puppetlabs-inifile/pull/468) ([david22swan](https://github.com/david22swan))
- pdksync - \(IAC-1753\) - Add Support for AlmaLinux 8 [\#463](https://github.com/puppetlabs/puppetlabs-inifile/pull/463) ([david22swan](https://github.com/david22swan))
- pdksync - \(IAC-1751\) - Add Support for Rocky 8 [\#462](https://github.com/puppetlabs/puppetlabs-inifile/pull/462) ([david22swan](https://github.com/david22swan))
- match section names containing prefix character \(normally \[\) [\#457](https://github.com/puppetlabs/puppetlabs-inifile/pull/457) ([tja523](https://github.com/tja523))

### Fixed

- pdksync - \(GH-iac-334\) Remove Support for Ubuntu 14.04/16.04 [\#471](https://github.com/puppetlabs/puppetlabs-inifile/pull/471) ([david22swan](https://github.com/david22swan))
- pdksync - \(IAC-1787\) Remove Support for CentOS 6 [\#466](https://github.com/puppetlabs/puppetlabs-inifile/pull/466) ([david22swan](https://github.com/david22swan))
- pdksync - \(IAC-1598\) - Remove Support for Debian 8 [\#461](https://github.com/puppetlabs/puppetlabs-inifile/pull/461) ([david22swan](https://github.com/david22swan))

## [v5.2.0](https://github.com/puppetlabs/puppetlabs-inifile/tree/v5.2.0) (2021-08-26)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/v5.1.0...v5.2.0)

### Added

- pdksync - \(IAC-1709\) - Add Support for Debian 11 [\#458](https://github.com/puppetlabs/puppetlabs-inifile/pull/458) ([david22swan](https://github.com/david22swan))

### Fixed

- \(IAC-1741\) Allow stdlib v8.0.0 [\#459](https://github.com/puppetlabs/puppetlabs-inifile/pull/459) ([david22swan](https://github.com/david22swan))

## [v5.1.0](https://github.com/puppetlabs/puppetlabs-inifile/tree/v5.1.0) (2021-06-28)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/v5.0.1...v5.1.0)

### Added

- Accept Datatype Sensitive [\#454](https://github.com/puppetlabs/puppetlabs-inifile/pull/454) ([cocker-cc](https://github.com/cocker-cc))

## [v5.0.1](https://github.com/puppetlabs/puppetlabs-inifile/tree/v5.0.1) (2021-03-29)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/v5.0.0...v5.0.1)

### Fixed

- \(IAC-149\) - Removal of Unsupported Translate Module [\#442](https://github.com/puppetlabs/puppetlabs-inifile/pull/442) ([david22swan](https://github.com/david22swan))

## [v5.0.0](https://github.com/puppetlabs/puppetlabs-inifile/tree/v5.0.0) (2021-03-02)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/v4.4.0...v5.0.0)

### Changed

- pdksync - Remove Puppet 5 from testing and bump minimal version to 6.0.0 [\#432](https://github.com/puppetlabs/puppetlabs-inifile/pull/432) ([carabasdaniel](https://github.com/carabasdaniel))

## [v4.4.0](https://github.com/puppetlabs/puppetlabs-inifile/tree/v4.4.0) (2020-12-08)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/v4.3.1...v4.4.0)

### Added

- \(feat\) - Add Puppet 7 support [\#422](https://github.com/puppetlabs/puppetlabs-inifile/pull/422) ([daianamezdrea](https://github.com/daianamezdrea))

## [v4.3.1](https://github.com/puppetlabs/puppetlabs-inifile/tree/v4.3.1) (2020-11-09)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/v4.3.0...v4.3.1)

### Fixed

- \(IAC-992\) - Removal of inappropriate terminology [\#415](https://github.com/puppetlabs/puppetlabs-inifile/pull/415) ([david22swan](https://github.com/david22swan))

## [v4.3.0](https://github.com/puppetlabs/puppetlabs-inifile/tree/v4.3.0) (2020-09-10)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/v4.2.0...v4.3.0)

### Added

- pdksync - \(IAC-973\) - Update travis/appveyor to run on new default branch `main` [\#407](https://github.com/puppetlabs/puppetlabs-inifile/pull/407) ([david22swan](https://github.com/david22swan))
- Add delete\_if\_empty parameter to the ini\_subsetting type/provider [\#405](https://github.com/puppetlabs/puppetlabs-inifile/pull/405) ([mmarod](https://github.com/mmarod))
- \(IAC-746\) - Add ubuntu 20.04 support [\#396](https://github.com/puppetlabs/puppetlabs-inifile/pull/396) ([david22swan](https://github.com/david22swan))

## [v4.2.0](https://github.com/puppetlabs/puppetlabs-inifile/tree/v4.2.0) (2020-04-27)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/v4.1.0...v4.2.0)

### Added

- Finish API conversion of `create\_ini\_settings` [\#387](https://github.com/puppetlabs/puppetlabs-inifile/pull/387) ([alexjfisher](https://github.com/alexjfisher))

## [v4.1.0](https://github.com/puppetlabs/puppetlabs-inifile/tree/v4.1.0) (2020-01-15)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/v4.0.0...v4.1.0)

### Added

- pdksync - \(FM-8581\) - Debian 10 added to travis and provision file refactored [\#374](https://github.com/puppetlabs/puppetlabs-inifile/pull/374) ([david22swan](https://github.com/david22swan))
- Puppet 4 functions [\#373](https://github.com/puppetlabs/puppetlabs-inifile/pull/373) ([binford2k](https://github.com/binford2k))
- pdksync - "MODULES-10242 Add ubuntu14 support back to the modules" [\#368](https://github.com/puppetlabs/puppetlabs-inifile/pull/368) ([sheenaajay](https://github.com/sheenaajay))
- \(FM-8689\) - Addition of Support for CentOS 8 [\#366](https://github.com/puppetlabs/puppetlabs-inifile/pull/366) ([david22swan](https://github.com/david22swan))

## [v4.0.0](https://github.com/puppetlabs/puppetlabs-inifile/tree/v4.0.0) (2019-11-11)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/v3.1.0...v4.0.0)

### Changed

- pdksync - FM-8499 - remove ubuntu14 support [\#363](https://github.com/puppetlabs/puppetlabs-inifile/pull/363) ([lionce](https://github.com/lionce))

### Added

- FM-8402 add debian 10 support [\#352](https://github.com/puppetlabs/puppetlabs-inifile/pull/352) ([lionce](https://github.com/lionce))

## [v3.1.0](https://github.com/puppetlabs/puppetlabs-inifile/tree/v3.1.0) (2019-07-31)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/v3.0.0...v3.1.0)

### Added

- FM-8222 - Port Module inifile to Litmus [\#344](https://github.com/puppetlabs/puppetlabs-inifile/pull/344) ([lionce](https://github.com/lionce))
- \(FM-8154\) Add Windows Server 2019 support [\#340](https://github.com/puppetlabs/puppetlabs-inifile/pull/340) ([eimlav](https://github.com/eimlav))
- \(FM-8041\) Add RedHat 8 support [\#339](https://github.com/puppetlabs/puppetlabs-inifile/pull/339) ([eimlav](https://github.com/eimlav))

## [v3.0.0](https://github.com/puppetlabs/puppetlabs-inifile/tree/v3.0.0) (2019-04-22)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/2.5.0...v3.0.0)

### Changed

- pdksync - \(MODULES-8444\) - Raise lower Puppet bound [\#335](https://github.com/puppetlabs/puppetlabs-inifile/pull/335) ([david22swan](https://github.com/david22swan))

### Fixed

- FM-7779 - Cleanup Inifile [\#328](https://github.com/puppetlabs/puppetlabs-inifile/pull/328) ([lionce](https://github.com/lionce))

## [2.5.0](https://github.com/puppetlabs/puppetlabs-inifile/tree/2.5.0) (2018-12-28)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/2.4.0...2.5.0)

### Added

- \(MODULES-8142\) - Addition of support for SLES 15 [\#315](https://github.com/puppetlabs/puppetlabs-inifile/pull/315) ([david22swan](https://github.com/david22swan))
- \(MODULES-7560\) - removed spaces from the beginning or from the end of the value [\#311](https://github.com/puppetlabs/puppetlabs-inifile/pull/311) ([lionce](https://github.com/lionce))

### Fixed

- pdksync - \(FM-7655\) Fix rubygems-update for ruby \< 2.3 [\#320](https://github.com/puppetlabs/puppetlabs-inifile/pull/320) ([tphoney](https://github.com/tphoney))
- \(MODULES-6714\) - inifile: ensure absent not working with refreshonly = true [\#313](https://github.com/puppetlabs/puppetlabs-inifile/pull/313) ([Lavinia-Dan](https://github.com/Lavinia-Dan))
- \(FM-7483\) - update module to the latest version [\#310](https://github.com/puppetlabs/puppetlabs-inifile/pull/310) ([lionce](https://github.com/lionce))
- \(FM-7331\)-Fix japanese test [\#308](https://github.com/puppetlabs/puppetlabs-inifile/pull/308) ([lionce](https://github.com/lionce))

## [2.4.0](https://github.com/puppetlabs/puppetlabs-inifile/tree/2.4.0) (2018-09-27)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-inifile/compare/2.3.0...2.4.0)

### Added

- pdksync - \(FM-7392\) - Puppet 6 Testing Changes [\#300](https://github.com/puppetlabs/puppetlabs-inifile/pull/300) ([pmcmaw](https://github.com/pmcmaw))
- pdksync - \(MODULES-7658\) use beaker4 in puppet-module-gems [\#296](https://github.com/puppetlabs/puppetlabs-inifile/pull/296) ([tphoney](https://github.com/tphoney))
- \(MODULES-7552\) - Addition of support for Ubuntu 18.04 to inifile [\#292](https://github.com/puppetlabs/puppetlabs-inifile/pull/292) ([david22swan](https://github.com/david22swan))

### Fixed

- \(MODULES-7625\) - Update README Limitations section [\#293](https://github.com/puppetlabs/puppetlabs-inifile/pull/293) ([eimlav](https://github.com/eimlav))

## 2.3.0
### Summary
This release uses the PDK convert functionality which in return makes the module PDK compliant. It also includes a feature for `force_new_section_creation` and a roll up of maintenance changes.

### Added
- Added `force_new_section_creation` parameter.
- PDK convert and update to use pdk 1.5.0 (MODULES-6326).

### Removed
- Support for Scientific Linux 5
- Support for Debian 7

## Supported Release [2.2.2]
### Summary
This is a bug fix release that corrects type autoloading.

### Fixed
- Correct type autoload ([FM-6932](https://tickets.puppet.com/browse/FM-6932)).

## Supported Release [2.2.1]
### Summary
This is a bug fix release for a problem with managing existing lines in Puppet > 5.4.0

### Fixed
- issue with ini_setting's :refreshonly parameter validation ([MODULES-6687](https://tickets.puppet.com/browse/MODULES-6687))

## Supported Release [2.2.0]
### Summary
This release uses the PDK convert functionality which in return makes the module PDK compliant. It also includes a roll up of maintenance changes.

### Added
- PDK convert inifile ([MODULES-6453](https://tickets.puppet.com/browse/MODULES-6453)).
- Modulesync updates.

### Fixed
- Changes to address additional Rubocop failures.
- Addressing puppet-lint doc warnings.

### Removed
- `gem update bundler` command in .travis.yml due to ([MODULES-6339](https://tickets.puppet.com/browse/MODULES-6339)).

## Supported Release 2.1.1
### Summary
This release is in order to implement Rubocop within the module and includes a wide array of formatting changes throughout the code and the enabling of rubocop checks to be run against all pull requests against the module.

### Changed
- Rubocop checks will now be run against any PRs made towards the module.
- The module has undergone a substantial reformatting in order to comply with the designated standards.

## Supported Release 2.1.0
### Summary
This is a clean release prior to the implementation of rubocop within the module.

### Added
- Several Modulesync updates have been made.
- Indent Character can now be set.
- Support for Debian 9 has been added.

### Removed
- Support for Ubuntu 1004 and 1204 has been removed.
- Support for SLES 10 SP4 has been removed.
- Support for Debian 6 has been removed.
- Support for Solaris 12 has been removed.
- Support for Windows Server 2003 R2 has been removed.

## Supported Release 2.0.0
### Summary
This is a major release that includes a few bugfixes as well as some general module updates.

**This release drops Puppet 3 support**

### Changed
- Moved lower Puppet version requirement to 4.7.0, MODULES-4830

### Fixed
- Fix path validation on windows MODULES-4170
- Fix headings in README
- Fix for mimicking commented settings MODULES-4932
- Fix for Backwards compatible ini_file.set_value MODULES-5172

## Supported Release 1.6.0
### Summary
This release expands functionality around sub-settings and adds the `refreshonly` parameter so the user can specify whether a resource should or should not respond to a refresh event.

### Features
- `refreshonly` decide whether or not a value should be updated as part of a refresh
- `insert_type` choose where the sub-setting is placed in the final string
- `subsetting_key_val_separator` specify a key/value separator for sub-settings

### Bugfixes
- MODULES-3145 Cast values to strings before passing to provider


## Supported Release 1.5.0
### Summary
This release adds the long-awaited `show_diff` parameter for diffing the complete file on changes (or can also just show the md5 sums).

### Features
- Added `show_diff` parameter to show diffs on changes.
- Remove empty ini sections when the last line in the section is removed.

### Bugfixes
- Workaround `create_ini_settings()` duplicate resources puppet bug PUP-4709

## Supported Release 1.4.3
###Summary

Small release for support of newer PE versions. This increments the version of PE in the metadata.json file.

## 2015-09-01 - Supported Release 1.4.2
### Summary
This release adds some bugfixes.

####Bugfixes
- MODULES-2212 Add use_exact_match parameter for subsettings
- MODULES-1908 Munge the setting to ensure we always strip the whitespace
- MODULES-2369 Support a space as a key_val_separator

## 2015-07-15 - Supported Release 1.4.1
### Summary
This release bumps the metadata for PE up.

##2015-07-07 - Supported Releases 1.4.0
###Summary

This is primarily a release which includes acceptance tests updates, but also includes some minor bug fixes and improvements

####Features
- Solaris 12 Support
- Acceptance testing improvements

####Bugfixes
- MODULES-1599 Match only on space and tab whitespace after k/v separator

##2015-06-09 - Supported Releases 1.3.0
###Summary

This is primarily a feature release, but also includes test fixes, documentation updates and synchronization of files with modulesync.

####Features
- Synchronized files using modulesync
- Improved documentation
- Allow changing key value separator beyond indentation
- Adding the ability to change regex match for $section in inifile

####Bugfixes
- pin beaker-rspec for windows testing
- pin rspec gems for testing
- Adds default values for section
- Fixed names containing spaces

##2014-11-11 - Supported Releases 1.2.0
###Summary

This is primarily a bugfix release, but also includes documentation updates and synchronization of files with modulesync.

####Features
- Synchronized files using modulesync
- Improved documentation with a warning about old, manually installed inifile with PE3.3+

####Bugfixes
- Fix issue where single character settings were not being saved

##2014-09-30 - Supported Releases 1.1.4
###Summary

This release includes documentation and test updates.

##2014-07-15 - Supported Release 1.1.3
###Summary

This release merely updates metadata.json so the module can be uninstalled and
upgraded via the puppet module command.

##2014-07-10 - Supported Release 1.1.2
###Summary

This is a re-packaging release.

##2014-07-07 - Release 1.1.1
###Summary

This supported bugfix release corrects the inifile section header detection
regex (so you can use more characters in your section titles).

####Bugfixes
- Correct section regex to allow anything other than ]
- Correct `exists?` to return a boolean
- Lots of test updates
- Add missing CONTRIBUTING.md

##2014-06-04 - Release 1.1.0
###Summary

This is a compatibility and feature release.  This release adds one new
feature, the ability to control the quote character used.  This allows you to
do things like:

```
ini_subsetting { '-Xms':
    ensure     => present,
    path       => '/some/config/file',
    section    => '',
    setting    => 'JAVA_ARGS',
    quote_char => '"',
    subsetting => '-Xms'
    value      => '256m',
  }
```

Which builds:

```
JAVA_ARGS="-Xmx256m -Xms256m"
```

####Features
- Add quote_char parameter to the ini_subsetting resource type

####Bugfixes

####Known Bugs
* No known bugs

##2014-03-04 - Supported Release 1.0.3
###Summary

This is a supported release.  It has only test changes.

####Features

####Bugfixes

####Known Bugs
* No known bugs


##2014-02-26 - Version 1.0.2
###Summary
This release adds supported platforms to metadata.json and contains spec fixes


##2014-02-12 - Version 1.0.1
###Summary
This release is a bugfix for handling whitespace/[]'s better, and adding a
bunch of tests.

####Bugfixes
- Handle whitespace in sections
- Handle square brances in values
- Add metadata.json
- Update some travis testing
- Tons of beaker-rspec tests


##2013-07-16 - Version 1.0.0
####Features
- Handle empty values.
- Handle whitespace in settings names (aka: server role = something)
- Add mechanism for allowing ini_setting subclasses to override the
formation of the namevar during .instances, to allow for ini_setting
derived types that manage flat ini-file-like files and still purge
them.

---
##2013-05-28 - Chris Price <chris@puppetlabs.com> - 0.10.3
 * Fix bug in subsetting handling for new settings (cbea5dc)

##2013-05-22 - Chris Price <chris@puppetlabs.com> - 0.10.2
 * Better handling of quotes for subsettings (1aa7e60)

##2013-05-21 - Chris Price <chris@puppetlabs.com> - 0.10.1
 * Change constants to class variables to avoid ruby warnings (6b19864)

##2013-04-10 - Erik Dalén <dalen@spotify.com> - 0.10.1
 * Style fixes (c4af8c3)

##2013-04-02 - Dan Bode <dan@puppetlabs.com> - 0.10.1
 * Add travisfile and Gemfile (c2052b3)

##2013-04-02 - Chris Price <chris@puppetlabs.com> - 0.10.1
 * Update README.markdown (ad38a08)

##2013-02-15 - Karel Brezina <karel.brezina@gmail.com> - 0.10.0
 * Added 'ini_subsetting' custom resource type (4351d8b)

##2013-03-11 - Dan Bode <dan@puppetlabs.com> - 0.10.0
 * guard against nil indentation values (5f71d7f)

##2013-01-07 - Dan Bode <dan@puppetlabs.com> - 0.10.0
 * Add purging support to ini file (2f22483)

##2013-02-05 - James Sweeny <james.sweeny@puppetlabs.com> - 0.10.0
 * Fix test to use correct key_val_parameter (b1aff63)

##2012-11-06 - Chris Price <chris@puppetlabs.com> - 0.10.0
 * Added license file w/Apache 2.0 license (5e1d203)

##2012-11-02 - Chris Price <chris@puppetlabs.com> - 0.9.0
 * Version 0.9.0 released

##2012-10-26 - Chris Price <chris@puppetlabs.com> - 0.9.0
 * Add detection for commented versions of settings (a45ab65)

##2012-10-20 - Chris Price <chris@puppetlabs.com> - 0.9.0
 * Refactor to clarify implementation of `save` (f0d443f)

##2012-10-20 - Chris Price <chris@puppetlabs.com> - 0.9.0
 * Add example for `ensure=absent` (e517148)

##2012-10-20 - Chris Price <chris@puppetlabs.com> - 0.9.0
 * Better handling of whitespace lines at ends of sections (845fa70)

##2012-10-20 - Chris Price <chris@puppetlabs.com> - 0.9.0
 * Respect indentation / spacing for existing sections and settings (c2c26de)

##2012-10-17 - Chris Price <chris@puppetlabs.com> - 0.9.0
 * Minor tweaks to handling of removing settings (cda30a6)

##2012-10-10 - Dan Bode <dan@puppetlabs.com> - 0.9.0
 * Add support for removing lines (1106d70)

##2012-10-02 - Dan Bode <dan@puppetlabs.com> - 0.9.0
 * Make value a property (cbc90d3)

##2012-10-02 - Dan Bode <dan@puppetlabs.com> - 0.9.0
 * Make ruby provider a better parent. (1564c47)

##2012-09-29 - Reid Vandewiele <reid@puppetlabs.com> - 0.9.0
 * Allow values with spaces to be parsed and set (3829e20)

##2012-09-24 - Chris Price <chris@pupppetlabs.com> - 0.0.3
 * Version 0.0.3 released

##2012-09-20 - Chris Price <chris@puppetlabs.com> - 0.0.3
 * Add validation for key_val_separator (e527908)

##2012-09-19 - Chris Price <chris@puppetlabs.com> - 0.0.3
 * Allow overriding separator string between key/val pairs (8d1fdc5)

##2012-08-20 - Chris Price <chris@pupppetlabs.com> - 0.0.2
 * Version 0.0.2 released

##2012-08-17 - Chris Price <chris@pupppetlabs.com> - 0.0.2
 * Add support for "global" section at beginning of file (c57dab4)

[2.3.0]:https://github.com/puppetlabs/puppetlabs-apt/compare/2.2.2...2.3.0
[2.2.2]:https://github.com/puppetlabs/puppetlabs-apt/compare/2.2.1...2.2.2
[2.2.1]:https://github.com/puppetlabs/puppetlabs-apt/compare/2.2.0...2.2.1
[2.2.0]:https://github.com/puppetlabs/puppetlabs-apt/compare/2.1.1...2.2.0


\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
