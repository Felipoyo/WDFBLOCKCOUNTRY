

### WDFBLOCKCOUNTRY

Generate Windows Defender Firewall Blocking Rules by Country 

## Windows Defender Firewall Block by Country 

1 Country 1 Rule





## Usage

Set the blocked country as string array
```powershell
$block = "China","Russia","North Korea"
```
And Run 

```
OUTPUT: 
Count Name  
(Networks) (Country)     
----- ----       
 7469 China      
    1 North Korea
10766 Russia     
China
      {1cb92f4...
North Korea
      {9828925...
Russia
      {c85f440...

```
## Screenshots
### Console:
![alt text](https://github.com/Felipoyo/WDFBLOCKCOUNTRY/blob/main/Captures/WDFirewall.png?raw=true)
### Log pfirewall:

![alt text](https://github.com/Felipoyo/WDFBLOCKCOUNTRY/blob/main/Captures/FirewallLog.png?raw=true)


# Changelog

All notable changes to this project will be documented in this file.


## [1.0] - 2024-04-19

- Initial 
- Bug : (Duplicate Country Validation) prevent duplicate country for prevent duplicate rules

## License

[apache-2.0](https://choosealicense.com/licenses/apache-2.0/)


https://t.me/PowershellSpanish

