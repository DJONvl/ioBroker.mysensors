![Logo](admin/mysensors.png)
# ioBroker.mysensors
=================

[![NPM version](http://img.shields.io/npm/v/iobroker.mysensors.svg)](https://www.npmjs.com/package/iobroker.mysensors)
[![Downloads](https://img.shields.io/npm/dm/iobroker.mysensors.svg)](https://www.npmjs.com/package/iobroker.mysensors)
[![Tests](https://travis-ci.org/ioBroker/ioBroker.mysensors.svg?branch=master)](https://travis-ci.org/ioBroker/ioBroker.mysensors)

[![NPM](https://nodei.co/npm/iobroker.mysensors.png?downloads=true)](https://nodei.co/npm/iobroker.mysensors/)

This adapter communicates with [mysensors](http://www.mysensors.org) serial or ethernet gateway (TCP or UDP). 
It ethernet gateway selected in this case ioBroker is server, that expects connections.

## Prerequires
To use serial port on Windows it is VS required to build the binary.
To use serial port on linux it is build-essential an python2.7 required. To install them just write:

```
sudo apt-get update
sudo apt-get install build-essential
sudo apt-get install python2.7
```

## Changelog
### 1.0.0 (2016-06-28)
* (soef) some value corrections and enlargement

### 0.2.6 (2016-06-16)
* (bluefox) do not switch off inclusion mode by stop

### 0.2.5 (2016-06-14)
* (bluefox) remove debug outputs

### 0.2.4 (2016-06-10)
* (bluefox) try/catch parse of messages

### 0.2.3 (2016-04-13)
* fix boolean values

### 0.2.2 (2016-04-10)
* (bluefox) implement inclusion mode

### 0.2.1 (2016-03-21)
* (bluefox) translates
* (bluefox) connection timeout for serial connection

### 0.2.0 (2016-03-21)
* (bluefox) wait till serial port is opened
* (bluefox) configurable baud rate

### 0.1.10 (2016-03-21)
* (bluefox) set role of dimmer as level.dimmer

### 0.1.9 (2016-03-15)
* (bluefox) fix typo

### 0.1.8 (2016-03-02)
* (bluefox) fix connection indicator for serial

### 0.1.7 (2016-03-02)
* (bluefox) do not send any data on disconnect

### 0.1.6 (2016-03-02)
* (bluefox) set UDP as default settings

### 0.1.5 (2016-03-02)
* (bluefox) change tree

