# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)


## Unreleased as of Sprint 92 - 2018-08-13

### Fixed
- Add parent_id to the ActiveRecord select filter [(#80)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/80)
- Fix to use hostname when connect to SCVMM host [(#79)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/79)

## Unreleased as of Sprint 84 - 2018-04-23

### Fixed
- Fix SCVMM Test Connection Method [(#68)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/68)

## Unreleased as of Sprint 82 - 2018-03-26

### Fixed
- Check connection to VMM when verifying credentials [(#66)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/66)
- Handle nil ems inventory from insufficient privileges credential issues [(#65)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/65)
- Migrate model display names from locale/en.yml to plugin [(#60)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/60)

## Gaprindashvili-1 - Released 2018-01-31

### Added
- Add translations [(#47)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/47)
- SCVMM Networking Enhancements [(#19)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/19)
- Validate credentials in raw_connect [(#16)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/16)
- Force array context for VMs vnets and images [(#13)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/13)

### Fixed
- Don't report misleading sockets/cores [(#51)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/51)
- Fix host maintenance mode [(#53)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/53)
- Added supported_catalog_types [(#54)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/54)
- missing VMMServer parameter [(#44)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/44)
- Collect VMHost PhysicalMachine SMBiosGUID [(#46)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/46)
- Move path_to_uri to SCVMM refresh parser [(#22)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/22)
- Move build_connect_params to a class method [(#34)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/34)
- Fix VM Subnet Provisioning [(#39)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/39)
- Fix exception handing for credential validation on raw_connect [(#41)](https://github.com/ManageIQ/manageiq-providers-scvmm/pull/41)

## Initial changelog added
