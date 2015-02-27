# Centralized server functional requirement specifications

## Introduction

This document describes the centralized server functional specifications. The server collect Keylogger's datas and provide a secure access to this data.
For this, the server is composed by two main components, the collector and the consumer. 

## Use case

![Keylogger - use cases](diagrams/UML - Use cases - Server.png)

## Installation management

### Install

Comming Soon

### Collector API

This API is WebService to collect, adjust and store data from a external keylogger.

### Consumer API

This AP is WebService to access a storage data. To get data, you need to be identified and to subcribe on flux of data.
