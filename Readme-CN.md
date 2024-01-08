# Heat-Card
 
## 语言选择:
[English](https://github.com/Knockoi/Heat-Card/blob/main/Readme.md) | [简体中文](https://github.com/Knockoi/Heat-Card/blob/main/Readme-CN.md) | [繁體中文](https://github.com/Knockoi/Heat-Card/blob/main/Readme-TC.md)
  
## 概述
这款迷你加热台尺寸小巧，方便携带，与市面上的MHP30迷你加热台相比，它拥有更大的加热面积，不再受限于小小的加热区域，机身更薄，可轻松放入口袋中。此外，它采用特别设计的PCB和铜柱组合，每一层功能都可以客制化设置，操作界面简洁明了，使用简单的RGB灯显示状态，其他设置可以通过蓝芽连接手机或电脑进行调整，并支持蓝芽和USB进行韧体升级，保证了机器的不断改进和更新。
  ![image](https://github.com/Knockoi/Heat-Card/blob/main/Image/%E8%9E%A2%E5%B9%95%E6%93%B7%E5%8F%96%E7%95%AB%E9%9D%A2%202023-10-22%20183807.png)
  
## 硬件
- MCU使用ESP32 C3
- MOSFET使用NCEP40T11G控制热板温度
- 温度测量使用PT1000 (-50°C~+500°C)
- 支持USB传输资料和UART传输资料(USB)
- 三向按钮来选择模式
- RGB显示模式及系统资讯
   
 ## 功能  
- 仿回流焊接。
- 恒温加热(1) 100~°C。
- 恒温加热(2) 200~°C。
- 恒温加热(3) 300°C。
- 快速回流焊接 时间是仿回流焊接的2/3。
  
 ## 按键功能  
 - 左键 左滑开关选单向左滑。
 - 右键 右滑开关选单向右滑。
 - 中键按住<=3S 确定。
 - 中键按住>=5S 蓝牙重新连接。
 - BOOT键 下载按钮。按住Boot，然后按Reset可启动韧体下载模式，透过序列埠下载韧体。
 - RESET键 按此按钮重新启动系统。
  
 基本按键可以参考ESP32-C3-DevKitM-1的使用方法。
