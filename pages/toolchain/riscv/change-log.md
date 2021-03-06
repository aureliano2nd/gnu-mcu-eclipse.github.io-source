---
layout: page
title: The 2017 RISC-V GCC Change Log
permalink: /toolchain/riscv/change-log/

date: 2017-07-07 16:34:00 +0300

---

Entries in this file are in reverse chronological order.

## 2017

### 2018-05-06

- v7.2.0-3-20180506 released
- update to latest SiFive commits from the following branches:
  - riscv-binutils-2.29
  - riscv-gcc-7.2.0
  - riscv-newlib-2.5.0
- update the build scripts to follow the ARM XBB structure 

### 2018-01-10

- v7.2.0-2-20180110 released
- update to latest SiFive commits from 2018-01-10
- dismiss the `data-list-register-names` patch, no longer needed

### 2017-11-09

- v7.2.0-1-20171109 released
- update to latest SiFive 2017-11-07 released, except newlib, where the reference was too old, and a recent commit was used
- in GDB, the list of registers returned by `data-list-register-names` no longer include the 4096 CSRs
- the tuple was renamed to `riscv-none-embed-`

### 2017-09-12

- v7.1.1-2-20170912-2255 released
- add multilib support for rv32imaf/ilp32f
- remove mandatory link of libgloss

### 2017-07-02

- v7.1.1-1-20170702-0625 released

### 2017-06-27

- add support for `--specs=nano.specs`; this translates into a separate build for `newlib` with specific configuration options and a separate build of the C++ standard libraries with `-Os`.
