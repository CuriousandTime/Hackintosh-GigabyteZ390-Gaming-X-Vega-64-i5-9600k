
<img width="1134" alt="关于本机" src="https://user-images.githubusercontent.com/15880196/103450221-05e8c380-4cee-11eb-9c74-4cd85cc5ae1d.png">

<img width="1134" alt="网卡蓝牙WIFI" src="https://user-images.githubusercontent.com/15880196/103450218-f9646b00-4ced-11eb-9d19-4e71f3744f69.png">

<img width="1134" alt="声卡正常" src="https://user-images.githubusercontent.com/15880196/103450223-0f722b80-4cee-11eb-9eb4-a7fa5d650e50.png">

<img width="1134" alt="核显" src="https://user-images.githubusercontent.com/15880196/103450225-16993980-4cee-11eb-8ad0-4b7a5c2cb6eb.png">

<img width="1134" alt="节能" src="https://user-images.githubusercontent.com/15880196/103450228-1f8a0b00-4cee-11eb-9095-f0f26f3c791d.png">

<img width="1134" alt="默认配置OpenCore0 6 5" src="https://user-images.githubusercontent.com/15880196/103450311-9ecc0e80-4cef-11eb-948c-da15514b399e.png">

<img width="1134" alt="安装最新自编译驱动" src="https://user-images.githubusercontent.com/15880196/103450313-a390c280-4cef-11eb-9c1c-2b6b873e2626.png">


## OenCore版本：  
0.6.5  
  
## 功能完善情况：
|功能      | 完善情况  | 
| ---------- | :-----------:  | :-----------: |
|睡眠唤醒     | 正常      |
|  |   | 
|蓝牙    | 正常      |
|  |   | 
|有线网卡    | 正常      |
|  |   | 
|无线网卡     | 正常      |
|  |   | 
|USB     | 正常      |
|  |   | 
|核显加速    | 正常      |
| ---------- | :-----------:  | :-----------: |


睡眠唤醒：正常  
蓝牙：正常  
WiFi：正常  
网卡：正常  
声卡：我用的蓝牙音箱，理论正常  
USB：因为我使用了USB改线，所以我的定制不适合大家「EFI中已替换USBInjectAll.kext，大家自行定制」  
核显加速：正常  
变频：不是超频玩家没有配置  

## Vega 64显卡优化：  
我使用的tonymacx86论坛中  [@mattystonnie优化方案](https://www.tonymacx86.com/threads/amd-radeon-performance-enhanced-ssdt.296555/  "悬停显示文字")

@mattystonnie推荐使用SSDT-RX Vega 64-Version 2.3.aml搭配DAGPM.kext使用，  
但我个人实际使用中  会出现风扇跳动加速的情况，  
所以我使用了SSDT-RX Vega 64-Version 2.3.aml+RadeonVega56AirCoolingFansFix.kext使用，现在所有情况正常，  
所以EFI中默认配置的是RadeonVega56AirCoolingFansFix.kext，大家自行测试使用。  


