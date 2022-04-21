# switch-cmake

Extensible CMake toolchain for Switch homebrew development with devkitA64 and libnx.

## Table of Contents

- [Introduction](#introduction)
  * [Why CMake](#why-cmake)
  * [Quick Start](#quick-start)
- [Switch Homebrew](#switch-homebrew)
  * [File Formats](#file-formats)
  * [devkitPro Ecosystem](#devkitpro-ecosystem)
    + [devkitA64](#devkita64)
    + [portlibs](#portlibs)
    + [tools](#tools)
  * [libnx](#libnx)
- [CMake Files](#cmake-files)
  * [FindLibnx.cmake](#findlibnxcmake)
  * [FindLibTwili.cmake](#findlibtwilicmake)
  * [FindMbedTLS.cmake](#findmbedtlscmake)
  * [SwitchTools.cmake](#switchtoolscmake)
- [Templates](#templates)
  * [Application](#application)
  * [Library](#library)
  * [System Module](#system-module)

## Introduction

### Why CMake

### Quick Start

## Switch Homebrew

### File Formats
 **The file formats made for the make file are:**
    + [.ELF] (The one i had most trouble with.)
    + [.NSO] (The intermediate process, it compresses the ELF file with ipv4)
    + [.NRO] (The final product of the makefile process)

### devkitPro Ecosystem

#### devkitA64

#### portlibs

### libnx

## CMake Files

### FindLibnx.cmake

### FindLibTwili.cmake

### FindMbedTLS.cmake

### SwitchTools.cmake

## Templates

### Application

### Library

### System Module
