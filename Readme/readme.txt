
/*-------------------------------------------------------------------------------------------------------*/

STM32后备域复位:
1. 软件复位(设置备份域控制寄存器RCC_BDCR中的BDRST位产生)
2. 在VDD和VBAT两者都掉电的前提下，VDD或VBAT上电将引发备份域复位.

/*-------------------------------------------------------------------------------------------------------*/




