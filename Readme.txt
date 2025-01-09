版本V1.1
智能垃圾桶
主控芯片：F103C8T6
实现通过呼叫语音助手控制垃圾桶的开关

接线：
ASRPOR   --------- STM32 
PB6(RX)	          	PA9(TX)
PB5(TX)		          PA10(RX)

SR90 ----------------STM32
DATA		              PB9

SR04 ----------------STM32
Trig                  PA1
ECHO                  PA0

OLED -----------------STM32
SCL		                PB10
SDA		                PB11
