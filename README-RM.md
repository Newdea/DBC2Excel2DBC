# DBC2Excel
Convert DBC to Excel by VBA

>password:6lm3crlZu!RLFubaCiSt

![IMAGE](https://s2.ax1x.com/2019/06/21/Vzu8Zn.png)

## Feature

* Add auto filter and merge cells
* Auto group by message
* Highlight transmitter and receiver
* Sort by message name and startbit
* Support both windows and unix file

## To do

## Performance

|File|ECU Nodes|Messages|Signals|Elapsed time(s)|
|--|--|--|--|--|
|1|8|25|244|22|
|2|9|72|754|60|
|3|9|76|1126|67|

SG_ signal_name multiplexer_indicator : start_bit | signal_size @ byte_order value_type ( factor , offset ) [ minimum | maximum ] unit receiver {, receiver}
其中byte_order分为motorola和intel两种格式，motorola对应0，intel对应1。这两种格式是区别如下：
如果在同一个字节内，则没有区别，如果跨越多个字节则有区别，motorola格式是高位(msb)在低字节（说明：CAN消息的字节排列Byte0 Byte1 … Byte7，Byte0是低字节），intel格式是高位（msb）在高字节。


MultiGrp
TxMethod

file,
compare,diff
show-file1,show2,conflict,new
    startbit,len
munal,

seting不同，只是显示不同，实际文件内容还是一样的
Msb,优先高位，
Lsb,优先低位

moto,sequential
BO_ 723 GW_BCM_EBS_2_P: 8 GWM
 SG_ New_Signal_2 : 15|13@0+ (1,0) [0|0] "" Vector__XXX
 SG_ EBS_SOC : 7|8@0+ (1,0) [0|100] "%"  TEL,EMS




