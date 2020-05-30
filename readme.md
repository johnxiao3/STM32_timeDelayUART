
---------------
Test MCU: STM32F103C6
crystal : 8MHz

HAL_Delay(5); 		turns out to have 6 ms delay
__NOP();			turns out to have 2.5 us delay
7 __NOP();			turns out to be 3 us delay
14 __NOP();			turns out to be 4.5 us delay
