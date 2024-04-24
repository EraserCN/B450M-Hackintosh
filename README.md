# B450M-Hackintosh
AMD B450 Hackintosh  EFI Files based on Opencore. Tested for macOS Monterey 12.1 &amp; Ventura 13&amp;Sonoma 14 

![info2](https://github.com/EraserCN/B450M-Hackintosh/assets/79615365/9e02f739-d2f5-425d-aa7f-1317e2371daa)

![info1](https://github.com/EraserCN/B450M-Hackintosh/assets/79615365/df69f286-eea9-4e2a-8780-813c5a1db347)



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


### **2.** Regenerate the SMBIOS config to fix Apple Service

<img width="974" alt="Regenerate" src="https://github.com/EraserCN/B450M-Hackintosh/assets/79615365/ea8c1bfd-01bc-4b11-bdf3-5ba6bc9f0a3e">
