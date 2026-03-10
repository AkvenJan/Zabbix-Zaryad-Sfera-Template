# Zabbix Zaryad Sfera Template
SNMP Template for Zaryd Sfera Series of UPS  
https://zarad-ups.ru/

Was tested on Zaryad Sfera M33-600, but must be usable on any Zaryad devices with similar SNMP module

Based on UPS-MIB.mib and INMATICS-MIB.mib

## Discovery rules
|Name|Description|Type|Key and additional info|
|----|-----------|----|----|
|Strings|<p>Discovery of Strings</p>|`SNMP agent`|string.discovery<p>Update: 2h</p>|
|Batteries|<p>Discovery of all the Batteries in all the strings</p>|`SNMP agent`|battery.discovery<p>Update: 12h</p>|
