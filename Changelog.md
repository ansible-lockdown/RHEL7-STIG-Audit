# changelog

## STIG version 3 Release 4 - 23 July 2021

- stig.yml
  - stig version update
  - new controls - see below
  - new variables - see below
  - auditd space left var set to 25%
  - linting

- All ruleIDs updated per changed control

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
      - default: rhe7stig_grub_superusers: su_mode_superuser

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
