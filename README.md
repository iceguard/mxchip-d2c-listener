# MXChip D2C Listener

Reads device-to-cloud messages coming in as default events. Note that for this to work fallback events have to enabled in the routinge settings on Azure.

## Usage

Set `connectionString` in `ReadDeviceToCloudMessages.js` to the connection string for iot owner policy with all access.


Install project

	npm install

Run listener

	node ReadDeviceToCloudMessages.js 
