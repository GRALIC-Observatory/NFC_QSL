# 不对前端UI的数据格式作任何要求，仅约定json的Key，以保证NFC_QSL卡的兼容性

|Key      |含义                    |数据类型    |建议值    |备注|
|:------|:-------|:-----------|:---------||
|myradio  |My Call Sign/寄卡方呼号  |str     |||
|toradio  |To Call Sign/收卡方呼号  |str      |||
|cfm      |Confirm/卡片类型         |str      |'Our QSO'or'Your SWL Report'||
|date     |Date/日期                |str    |'2055-05-05'|yyyy-mm-dd, UTC|
|time     |Time/时间                |str    |'14:22'|hh:mm, UTC|
|freq     |Frequency/频率           |float  |7.05|以MHz为单位|
|mode     |模式                     |str    |'FM', 'AM', 'SSB', ...||
|rst      |信号报告                 |str    |||
|rig      |电台                     |srt    |||
|pwr      |Power/功率               |float  |100|以Watt为单位|
|ant      |Antenna/天线             |str    |'长线加天调'||
|qth      |本台地址                 |str    |'ON80'|***网格|
|op       |operator/操作员签名      |str    |||
|rmks     |remarks/备注             |str    |||
