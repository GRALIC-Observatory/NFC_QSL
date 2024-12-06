# 不对前端UI的数据格式作任何要求，仅约定json的Key，以保证NFC_QSL卡的兼容性

|Key    |含义    |数据类型    |建议值    |
|:------|:-------|:-----------|:---------|
|cfm    |卡片类型  |str      |'Our QSO'or'Your SWL Report'|
|toradio|Call Sign/呼号|str|  |
|date|日期|str||
|time|时间|str||
|freq|频率|float||
|mode||||
|rst||||
|rig|电台|||
|pwr|功率|||
|ant|天线|||
|qth|||str***网格|
|op|操作员|str||
