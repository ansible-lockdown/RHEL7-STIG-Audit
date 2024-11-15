# RHEL/CentOS 7 Goss config for STIG

## Overview

based on STIG Version 3 Release 15 - 24th Jul 2024

bility to audit a system using a lightweight binary to check the current state.

This is:

- very small < 14MB
- lightweight
- self contained

It works using a set of configuration files and directories to audit STIG of RHEL/CentOS 8 servers. These files/directories correlate to the STIG Level and STIG_ID

Tested on

- RHEL7
- CentOS7

feedback on any differences between OSs please raise an issue

## Requirements

You must have [goss](https://github.com/goss-org/goss/) available to your host you would like to test.

You must have sudo/root access to the system as some commands require privilege information.

Assuming you have already clone this repository you can run goss from where you wish.

Please refer to the audit documentation for usage.

- [readthedocs](https://ansible-lockdown.readthedocs.io/en/latest/)

This also works alongside the [Ansible Lockdown RHEL7-STIG role](https://github.com/ansible-lockdown/RHEL7-STIG)

Which will:

- install
- audit
- remediate
- audit

## Join us

On our [Discord Server](https://www.lockdownenterprise.com/discord) to ask questions, discuss features, or just chat with other Ansible-Lockdown users

Set of configuration files and directories to run the first stages of STIG RHEL7 based servers

This is configured in a directory structure level.

Goss is run based on the goss.yml file in the top level directory. This specifies the configuration.

## further information

- [goss documentation](https://github.com/aelsabbahy/goss/blob/master/docs/manual.md#patterns)
- [STIG standards](https://public.cyber.mil/stigs/)
