STM32-ADC-DMA-Timer-UART-Implementation  
Board: STM32 NucleoF446RE  
IDE: STM32CubeMX, STM32CubeIDE  
Language: C (HAL based)

-TIM2 configured to generate 100 Hz  
-TIM2 TRGO used as trigger for ADC1  
-ADC1 configured  
-ADC data transferred using DMA2 (circular mode)  
-ADC values transmitted via UART (USART2)  
-Outputs displayed on serial terminal
