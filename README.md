# ME6210A33PG borad change from AMS1117-3V3

<img src="./ME6210A33PG_F.png" style="display:block; margin:auto; width:50%;" />  
<img src="./ME6210A33PG_B.png" style="display:block; margin:auto; width:50%;" />  
<img src="./ME6210A33PG-Edge_Cuts.svg" style="display:block; margin:auto; width:50%;" />  

[ME6210A33PG](https://www.jlc-smt.com/lcsc/detail?componentCode=C85233)  
LDO  
VIN 18V  
VOUT 3.3V  
IOUT 500mA  
package SOT-89-3  
IQ 2.5uA  
VD 260mV@200mA  

引脚定义  
1-GND  
2-VIN  
3-VOUT  

## HT7550-1 board = ME6210A33PG  

[HT7550-1](https://www.jlc-smt.com/lcsc/detail?componentCode=C5346140)
LDO  
VIN 28V  
VOUT 5V  
IOUT 150mA  
package SOT-89-3
accuracy 2%
IQ 4uA
VD 520mA@100mA  

引脚定义  
1-GND  
2-IN  
3-VOUT 

## RT9013-33GB

[RT9013-33GB](https://www.jlc-smt.com/lcsc/detail?componentCode=C47773)  
LDO  
VIN 5.5V  
VOUT 3.3V  
IOUT 0.5A  
package SOT-23-5  
accuracy 2%  
IQ 50uA  
VD 250mV@500mA  
ENL 0.6V  
ENH 1.6V  
IEN 0.1uA -> 100K电阻  
  
引脚定义  
1-VIN  
2-GND  
3-EN  
4-NC  
5-VOUT  

## ME6211C33M5G-N board = RT9013-33GB  

[ME6211C33M5G-N](https://www.jlc-smt.com/lcsc/detail?componentCode=C82942)  
LDO  
VIN 6V  
VOUT 3.3V  
IOUT 300mA  
package SOT-23-5  
accuracy 2%  
IQ 60uA  
VD 260mV@200mA  
ENL 0.5V  
ENH 1V  
IEN 应该是uA -> 100K电阻  
Vn 50uVrms  
  
引脚定义  
1-VIN  
2-GND  
3-EN  
4-NC  
5-VOUT  

## ME6206A33XG  borad change from AMS1117-3V3
  
[ME6206A33XG](https://www.jlc-smt.com/lcsc/detail?componentCode=C161345)  
LDO  
VIN 6V  
VOUT 3.3V  
IOUT 300mA  
package SOT-23-3  
IQ 8uA  
VD 400mV@200mA  

引脚定义  
1-GND  
2-VOUT  
3-VIN  

kciad 并无其符号, 根据封装和引脚定义, 选择自MCP1703Ax-330xxTT 这个符号派生  
封装也是取其 Package_TO_SOT_SMD:SOT-23  
输入TVS 改为 SMAJ6.0CA  

## AMS1117-3V3  borad change from HT7333
  
[AMS1117-3V3](https://www.jlc-smt.com/lcsc/detail?componentCode=C5120765)  
LDO  
  
VIN 18V  
VOUT 3.3V  
IOUT 1A  
package SOT-223  
IQ 12mA  
VD 1.4V@1A  
  
引脚引脚定义  
  
1 GND  
2 VOUT  
3 VIN  

输入TVS 改为SMAJ18CA
  
## HT7333  
  
[HT7333](https://item.szlcsc.com/323851.html?fromZone=s_s__%2522HT7333%2522&spm=sc.gb.xh2.zy.n___sc.hm.hd.ss&lcsc_vid=EwQKBQVXRFYIBQVTR1JbVFcAFgRYUl0AFFNZVAEARVQxVlNSQVZWVVFfRVBZXzsOAxUeFF5JWBYZEEoEHg8JSQcJGk4%3D)  
  
LDO  
  
VIN 12V  
VOUT 3.3V  
IOUT 250mA  
package SOT-89-3  
IQ 3uA  
VD 90mV@40mA  
  
引脚定义  
  
1 GND  
2 VIN  
3 VOUT  
  
所以使用kciad 里面的 Regulator_Generic_GND_IN_OUT 生成符号  
  
封装采用PCM_Package_TO_SOT_SMD_AKL:SOT-89-3, 已确认封装焊盘顺序定义无误  
  
## TLV70450DBVR  
  
[TLV70450DBVR](https://www.jlc-smt.com/lcsc/detail?componentCode=C91672)  
VIN 24V  
VOUT 5V  
IOUT 150mA  
IQ 4.5uA  
VD 1.1V@100mA  
package SOT-23-5  
  
1-GND  
2-IN  
3-OUT  
4-NC  
5-NC  
  
这样的封装的引脚定义是很少的,基本上只有TLV70450DBVR,甚至需要自己绘制封装...  
