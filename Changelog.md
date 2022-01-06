# changelog

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
