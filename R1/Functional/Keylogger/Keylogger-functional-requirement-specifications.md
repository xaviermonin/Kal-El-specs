# Keylogger functional requirement specifications

## Introduction

This document describes the keylogger fonctionnal specifications.

## Use case

![Keylogge - use cases](UML - Use cases.png)

## Installation management

### Install

The *Computer's owner* get a delegated identity from the account manager (Centralized Server) then installs the keylogger on his computer with this identity and URL of the centralized server. During installation, the computer owner must confirm that he is the owner of the computer.

After installation, the keylogger must be hidden : no window should be visible.

### Uninstall

The *Computer's owner* can uninstall the keylogger by running the configuration manager (see *Configuration* use case) and selecting "Uninstall".
The keylogger stop its collect operation and self uninstall.

### Configuration

The *Computer's owner* run the keylogger from the original binary or installation path, the keylogger configuration window appears.

## Data collector

### Collect

### Send collected data

### Collect pressed keys
