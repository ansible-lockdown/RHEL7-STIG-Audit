# changelog

## Stig v3r13 25th Oct 2023

- RHEL_07_010310 - ruleid updated and INACTIVE var created
- RHEL_07_020020 - ruleid
- RHEL_07_020021 - ruleid
- RHEL_07_020023 - ruleid
- RHEL_07_020230 - ruleid
- RHEL_07_021700 - ruleid

## Stig V3R12 26th July 2023 - Sept23

updated run_audit script, enhanced and allowed testing of goss version
adding missing variables

## Stig V3R12 26th July 2023

- RHEL-07-010199 - pamd password and system auth rewrite and ruleid updated
- RHEL-07-010200 - ruleid update
- RHEL_07-010270 - rewritten to align to new settings and ruleid updated
- RHEL_07_020700 - ruleid updated
- RHEL_07_020710 - ruleid updated fixed rule
- RHEL_07_031000 - updated test and ruleid updated
- RHEL_07_040300 - ruleid updated
- RHEL_07_040310 - ruleid updated
- RHEL_07_040320 - ruleid updated
- RHEL_07_040340 - ruleid updated

- some test improvements
- basic linting

## Stig Version 3 release 11 - 27 April 2023

works with oraclelinux

- New controls
  - RHEL-07-010019
  - RHEL-07-010063
  - RHEL-07-020028

- rule id updates and changes
  - RHEL-07-010119
  - RHEL-07-010199
  - RHEL-07-010271
  - RHEL-07-020028
  - RHEL-07-020030

## Stig Version 3 release 10 - 26 Jan 2023

Rule_id updates for all listed

- Cat1
  - 010010
  - 101290

- Cat2
  - 010060
  - 010062
  - 010070
  - 010081
  - 010082
  - 010090 - new control
  - 010199 - new control
  - 010200
  - 010270
  - 010320
  - 010330
  - 010342
  - 020029
  - 020030
  - 020040
  - 020650
  - 021620
  - 040201
  - 040420
  - 040470 - added comment only pre7.4
  - 040610
  - 040611
  - 040612
  - 040620
  - 040630
  - 040640
  - 040641
  - 040650
  - 040660
  - 040712 - ssh KEX
  - 040740
  - 040830

- Cat3
  - 010375 new control
  - 021600
  - 021610

## STIG version 3 Release 9 - 27 Oct 2022

Linting
Rule_id Updated for all listed

- Cat 2
  - RHEL-07-101271 - New control
  - RHEL-07-010341
  - RHEL-07-010343
  - RHEL-07-020023
  - RHEL-07-021040
  - RHEL-07-021700
  - RHEL-07-030201
  - RHEL-07-030840
  - RHEL-07-040160
  - RHEL-07-040310
  - RHEL-07-040360

- Cat 3
  - RHEL-07-040530

run_audit.sh

- output path now default /opt
- filename output file name include Benchmark details

## STIG version 3 Release 8 - 27 Jul 2022

Linting

Rule_id changed plus comments

- Cat 1
  - RHEL-07-020230 - added mask check

- Cat 2
  - RHEL-07-010339 - tidy up rule
  - RHEL-07-010340 - added recurse
  - RHEL-07-010342 - added recurse
  - RHEL-07-010343 - added recurse
  - RHEL-07-010483
  - RHEL-07-010492
  - RHEL-07-020023 - added recurse
  - RHEL-07-020029
  - RHEL-07-030560
  - RHEL-07-030570
  - RHEL-07-030580
  - RHEL-07-030590
  - RHEL-07-030630
  - RHEL-07-030640
  - RHEL-07-030650
  - RHEL-07-030660
  - RHEL-07-030670
  - RHEL-07-030680
  - RHEL-07-030690
  - RHEL-07-030710
  - RHEL-07-030720
  - RHEL-07-030740
  - RHEL-07-030750
  - RHEL-07-030760
  - RHEL-07-030770
  - RHEL-07-030780
  - RHEL-07-030800
  - RHEL-07-030810
  - RHEL-07-030819
  - RHEL-07-030820
  - RHEL-07-030830

## test improvement

Many tests now updated to improve reporting

## STIG version 3 Release 7 - 27 Apr 2022

RHEL-07-010291 - control ID update

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
