## 1.0.4

* Allow calls to frame.disconnect() even when connect() did not succeed (e.g. in a finally block)
* Added small delays (200ms) after break signal and reset signal to wait for Frame to be ready

## 1.0.3

* Added workaround for BlueZ backend for Bleak on Linux to force MTU negotiation

## 1.0.2

* Fixed bug in handling escape sequences in file uploads, improved the algorithm for not splitting a chunk in the middle of an escape sequence. Also handles tab sequences

## 1.0.1

* Fixed missing escape sequence for bare backslashes in uploaded files

## 1.0.0

* First PyPI packge published

## 0.1.1

* Updated README.md

## 0.1.0

* Initial version adapted from frame-utilities-for-python