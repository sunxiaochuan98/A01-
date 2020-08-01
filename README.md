# A01
2020年新工科联盟xilinx暑期学校A班电机控制选题

组员：20AO040A麻旺龙、20AO038A王天羽、20AO034A孙啸川

项目概要：
团队选择的项目为—电机测速。即通过编写PWM模块来控制电机转动。在电机转动时，将电机转轴上的码盘，放至U型光电对射开关槽中，开发板对光电对射开关输入进的脉冲进行计数统计，并通过计数器进行计时、通过计算求得电机转速。随后通过UART发送模块，将转速发送至电脑端。电脑端通过串口调试助手查看相应数据。

使用工具：
vivado2018.3、SEA-S7板卡、2路直流电机驱动模块正反转PWM调速、光电对射传感器模块、CP2012下载线USB转串口模块USB转TTL、直流电机、串口调试助手。

仓库结构：
README.md 2020年新⼯科联盟-Xilinx暑期学校（Summer School）项⽬的介绍文件。
images 存放README.md文件中引⽤的照片。   
Sourcecode 存放项⽬源代码(压缩包格式)。  
ExecutableFiles 本⽬录存放可直接下载到板卡使⽤的FPGA 比特流文件。

