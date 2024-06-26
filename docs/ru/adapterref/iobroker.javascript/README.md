---
BADGE-Number of Installations: http://iobroker.live/badges/javascript-stable.svg
BADGE-NPM version: http://img.shields.io/npm/v/iobroker.javascript.svg
BADGE-Downloads: https://img.shields.io/npm/dm/iobroker.javascript.svg
chapters: {"pages":{"ru/adapterref/iobroker.javascript/README.md":{"title":{"ru":"ioBroker.javascript"},"content":"ru/adapterref/iobroker.javascript/README.md"},"ru/adapterref/iobroker.javascript/blockly.md":{"title":{"ru":"Содержание"},"content":"ru/adapterref/iobroker.javascript/blockly.md"}}}
---
![Logo](../../admin/javascript.png)

# ioBroker.javascript

## Содержание

- [Blockly](blockly.md)

## Changelog
<!--
	### **WORK IN PROGRESS**
-->
### **WORK IN PROGRESS**
* (klein0r) Escape all field inputs correctly when using single quotes
* (klein0r) Added sandbox function to subscribe to all enum members
* (klein0r) Added Blockly block to subscribe to all enum members
* (klein0r) Added sandbox functions to start/restart/stop an instance
* (klein0r) Added Blockly block to start/restart/stop an instance
* (klein0r) Added Blockly block to start/stop a script
* (klein0r) Added Blockly result blocks for script messages
* (klein0r) Fixed onLog / onLogUnregister return types
* (foxriver76) fixed issue in importing additional node modules for packages which do not provide a default export (e.g. `mathjs`)

### 8.6.0 (2024-06-14)

* (foxriver76) fixed issue with additional node modules which are installed from GitHub (controller v6)
* (klein0r) Added new Blockly block to save http response into temp file
* (klein0r) Escape single quotes in all object Blockly blocks
* (klein0r) Grouped Blockly blocks / changed order of blocks
* (klein0r) Allow multi line comments

### 8.5.2 (2024-06-11)

* (foxriver76) fixed issue with additional node modules when using js-controller version 6
* (klein0r) Added Blockly block to check if text includes another text
* (klein0r) Fixed onFile error when file has been deleted

### 8.5.1 (2024-06-10)

* (klein0r) Added Blockly dark theme
* (klein0r) Fixed sendTo custom parameters with special chars

### 8.5.0 (2024-06-07)

* (klein0r) Ack flag on state object has priorty (in setState/setStateDelayed)
* (klein0r) Fixed all blockly declarations (to avoid warnings in logs)
* (klein0r) Updated Blockly Core to 10.4.3

### 8.4.3 (2024-06-04)

* (klein0r) Added response time to httpGet and httpPost result
* (klein0r) Added trigger block to ack new values
* (bluefox) Allowed selecting different ChatGPT models for AI code generator

## License
The MIT License (MIT)

Copyright (c) 2014-2024 bluefox <dogafox@gmail.com>,

Copyright (c) 2014      hobbyquaker

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.