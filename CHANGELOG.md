# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)


## Unreleased as of Sprint 77 ending 2018-01-15

### Fixed
- Fix Automate State Machine ae_max_retries root object value. [(#137)](https://github.com/ManageIQ/manageiq-automation_engine/pull/137)

## Unreleased as of Sprint 76 ending 2018-01-01

### Added
- Adds better logging to class copy methods [(#120)](https://github.com/ManageIQ/manageiq-automation_engine/pull/120)
- Add vm_reconfigure_request service model. [(#97)](https://github.com/ManageIQ/manageiq-automation_engine/pull/97)

### Fixed
- Add and remove dependent services correctly in hierarchical structures [(#132)](https://github.com/ManageIQ/manageiq-automation_engine/pull/132)

## Unreleased as of Sprint 75 ending 2017-12-11

### Fixed
- Add remove_from_vmdb method to generic object for Service models. [(#130)](https://github.com/ManageIQ/manageiq-automation_engine/pull/130)
- Expose generic objects to the services service model. [(#128)](https://github.com/ManageIQ/manageiq-automation_engine/pull/128)
- Log encryption failures [(#127)](https://github.com/ManageIQ/manageiq-automation_engine/pull/127)

## Unreleased as of Sprint 74 ending 2017-11-27

### Fixed
- Prefer Gem.path over ENV "GEM_PATH" [(#119)](https://github.com/ManageIQ/manageiq-automation_engine/pull/119)
- Changes service name update to raise errors [(#118)](https://github.com/ManageIQ/manageiq-automation_engine/pull/118)
- Allow automate scripts to use gems from GEM_PATH and BUNDLE_PATH [(#116)](https://github.com/ManageIQ/manageiq-automation_engine/pull/116)

## Unreleased as of Sprint 73 ending 2017-11-13

### Added
- Allow for substitution of hosts in Ansible Playbook methods [(#102)](https://github.com/ManageIQ/manageiq-automation_engine/pull/102)
- Add task_href_slug as an extra_var for Ansible Playbook [(#101)](https://github.com/ManageIQ/manageiq-automation_engine/pull/101)

## Unreleased as of Sprint 72 ending 2017-10-30

### Added
- Set state machine retry interval for Ansible playbook method. [(#98)](https://github.com/ManageIQ/manageiq-automation_engine/pull/98)
- Added support for manageiq_connection [(#95)](https://github.com/ManageIQ/manageiq-automation_engine/pull/95)
- Use options instead of data to fetch config info [(#94)](https://github.com/ManageIQ/manageiq-automation_engine/pull/94)
- Add remove_from_vmdb method to Host object for Service models [(#93)](https://github.com/ManageIQ/manageiq-automation_engine/pull/93)
- Automate Workspace encrypt/decrypt support [(#90)](https://github.com/ManageIQ/manageiq-automation_engine/pull/90)
- Get the current user if user context is set. [(#86)](https://github.com/ManageIQ/manageiq-automation_engine/pull/86)

## Gaprindashvili Beta1

### Added
- Expose disks and volumes in the ServiceModel through Hardware. [(#91)](https://github.com/ManageIQ/manageiq-automation_engine/pull/91)
- Pass in the workspace as href_slug [(#82)](https://github.com/ManageIQ/manageiq-automation_engine/pull/82)
- Ansible Playbook Automate Method [(#78)](https://github.com/ManageIQ/manageiq-automation_engine/pull/78)
- Changes for generic object method calls via REST API. [(#74)](https://github.com/ManageIQ/manageiq-automation_engine/pull/74)
- Expose stack refresh method [(#68)](https://github.com/ManageIQ/manageiq-automation_engine/pull/68)
- Use generic object's methods to add to/remove from a service. [(#70)](https://github.com/ManageIQ/manageiq-automation_engine/pull/70)
- Add exposed manager refresh method [(#67)](https://github.com/ManageIQ/manageiq-automation_engine/pull/67)
- Serialize/Deserialize a workspace [(#64)](https://github.com/ManageIQ/manageiq-automation_engine/pull/64)
- Allows expressions to be exported and imported [(#56)](https://github.com/ManageIQ/manageiq-automation_engine/pull/56)
- Support for expression methods [(#49)](https://github.com/ManageIQ/manageiq-automation_engine/pull/49)

### Fixed
- Need to pass the user's group in to automate when the provision starts. [(#61)](https://github.com/ManageIQ/manageiq-automation_engine/pull/61)
