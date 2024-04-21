# B450M-Hackintosh
AMD B450 Hackintosh  EFI Files based on Opencore. Tested for macOS Monterey 12.1 &amp; Ventura 13&amp;Sonoma 14 
# Important Notice, Read before You Download the EFI Files⚠️⚠️⚠️

### **1.** Make sure the config matches your installed CPU cores
- Default config files are made for six core Processors such as my R5-5500, if you're on a CPU with different cores, plase change the value of 'Replace' in  'Force cpuid_cores_per_package' into the table listed below.
- 
| Cores | Value|
|-|-|
|   4 Core  | `uAQAAAAA` `ugQAAAAA` `ugQAAACQ` `ugQAAAA=`|
|   6 Core  | `uAYAAAAA` `ugYAAAAA` `ugYAAACQ` `ugYAAAA=` (Default)|
|   8 Core  | `uAgAAAAA` `uggAAAAA` `uggAAACQ` `uggAAAA=`|
|   12 Core | `uAwAAAAA` `ugwAAAAA` `ugwAAACQ` `ugwAAAA=`|
|   16 Core | `uBAAAAAA` `uhAAAAAA` `uhAAAACQ` `uhAAAAA=`|


