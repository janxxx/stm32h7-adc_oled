# stm32h7-adc_oled

Program reads voltage on the potentiometer acting as part of a voltage divider. That voltage is then calculated into resistance and displayed on ssd1306 OLED display.

ADC is configured in continous mode with DMA. Display is driven by an SPI interface.
