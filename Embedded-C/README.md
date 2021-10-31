IoT smart weather project:  
Aim:  
- To understand STM32F01RBT6 ARM cortex M4 Microcontroller and understanding of serial communication protocols (UART and I2C) 


WORKING:  
        1) Initialization part  
        2) infinite Loop:  
                           ADC_converstion(every 1 sec)  
                           Get data from RTC and print in display(every 1 sec)  
                           Send data to cloud (every 4-5 sec)   
                           Store and read from EEPROM(every 1 sec)     
        Switch                    
                           SW1 pressed: write the RTC clock  
                           SW2 pressed: EEPROM value displayed  





This Project done in 3-different versions
 1) IoT smart weather project V1 (Without i2c)
 2) IoT smart weather project V2 (With WiFi)
 3) IoT smart weather project V3 (With Wifi and if WiFi connection disconnected then data stored in EEPROM)
