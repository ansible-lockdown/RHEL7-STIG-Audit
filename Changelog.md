# changelog

## STIG version 3 Release 6 - 24 Jan 2022

- CAT 1
    - RHEL-07-010290 - Updated rule title
    - RHEL-07-010291 - New rule
- CAT 2
  - RHEL-07-010190 - Updated check content
  - RHEL-07-010310 - Updated and check content
  - RHEL-07-010339 - New rule - Added requirement to specify the default "include" directory for the /etc/sudoers file.
  - RHEL-07-010342 - Updated find statement
  - RHEL-07-010343 - Updated find statement
  - RHEL-07-020023 - updated find statement
  - RHEL-07-010344 - New rule - Added requirement to explicitly prevent the bypass of password requirements for privilege escalation.
  - RHEL-07-020029 - New rule - Added requirement for file integrity tool to be installed.
  - RHEL-07-030370 - Grouped like syscalls into this requirement.
  - RHEL-07-030410 - Grouped like syscalls into this requirement.
  - RHEL-07-030440 - Grouped like syscalls into this requirement.
  - RHEL-07-030510 - Grouped like syscalls into this requirement.
  - RHEL-07-030820 - Grouped like syscalls into this requirement.
  - RHEL-07-030910 - Grouped like syscalls into this requirement.
  - RHEL-07-030380 - Combined requirement with RHEL-07-030370.
  - RHEL-07-030390 - Combined requirement with RHEL-07-030370.
  - RHEL-07-030400 - Combined requirement with RHEL-07-030370.
  - RHEL-07-030420 - Combined requirement with RHEL-07-030410.
  - RHEL-07-030430 - Combined requirement with RHEL-07-030410.
  - RHEL-07-030450 - Combined requirement with RHEL-07-030440.
  - RHEL-07-030460 - Combined requirement with RHEL-07-030440.
  - RHEL-07-030470 - Combined requirement with RHEL-07-030440.
  - RHEL-07-030480 - Combined requirement with RHEL-07-030440.
  - RHEL-07-030490 - Combined requirement with RHEL-07-030440.
  - RHEL-07-030500 - Combined requirement with RHEL-07-030510.
  - RHEL-07-030520 - Combined requirement with RHEL-07-030510.
  - RHEL-07-030530 - Combined requirement with RHEL-07-030510.
  - RHEL-07-030540 - Combined requirement with RHEL-07-030510.
  - RHEL-07-030550 - Combined requirement with RHEL-07-030510.
  - RHEL-07-030821 - Combined requirement with RHEL-07-030820.
  - RHEL-07-030880 - Combined requirement with RHEL-07-030910.
  - RHEL-07-030890 - Combined requirement with RHEL-07-030910.
  - RHEL-07-030900 - Combined requirement with RHEL-07-030910.
  - RHEL-07-030920 - Combined requirement with RHEL-07-030910.
  - RHEL-07-040500 - Updated check and fix content.

## STIG version 3 Release 4 - 22 Oct 2021

- Addition of audit script and documentation
  - readme update

- STIG.yml now uppercase
  - stig version update
  - new controls

- CAT 1
  - RHEL-07-101480 - removed old control
- CAT 2
  - RHEL-07-010320 - seperate control
  - RHEL-07-010330 - seperate control and updated - RuleID
  - RHEL-07-010343 - RuleID
  - RHEL_07_010483 - RuleID
  - RHEL_07_010492 - RuleID
  - RHEL_07_010500 - RuleID
  - RHEL-07-021620 - added sha512 uncommented line check - RuleID
  - RHEL-07-020020 - #** To be defined with remediation #**
  - RHEL-07-020021 - #** To be defined with remediation #**
  - RHEL-07-020022 - New Rule
  - RHEL-07-020023 - #** New Rule To be defined with remediation #**
  - RHEL-07-020720 - RuleID
  - RHEL-07-040420 - RuleID - made heavy check whole filesystem

## STIG version 3 Release 4 - 23 July 2021

- All ruleIDs updated for changed controls
- firewall checks will error to check manually

- stig.yml
  - stig version update
  - new controls - see below
  - new variables - see below
  - auditd space left var set to 25%
  - linting

- CAT 1
  - RHEL-07-010482
    - updated logic
  - RHEL-07-010491
    - updated logic
    - part control moved to 010492
- CAT 2
  - RHEL-07-010483
    - new control
    - new variable
      - default: rhel7stig_grub_superusers: su_mode_superuser

  - RHEL-07-010492
    - new control
    - new variable
      - default: rhe7stig_grub_superusers: su_mode_superuser

  - RHEL-07-020019
    - added pkg and proc id to stig.yml

  - RHEL-07-020020
    - logic

  - RHEL-07-020650

  - RHEL-07-030330
    - extra test

  - RHEL-07-030874
    - title

  - RHEL-07-040110

  - RHEL-07-040400
