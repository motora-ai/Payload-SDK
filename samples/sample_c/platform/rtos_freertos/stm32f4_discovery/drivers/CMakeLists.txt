#include_directories(BPS)
#include_directories(STM32F4xx_HAL_Driver/Inc)
#include_directories(STM32F4xx_HAL_Driver/Src)
#
#add_library(psdk_bsp
#            BSP/pps.c
#            BSP/stm32f4xx_hal_conf.h
#            BSP/pps.h
#            STM32F4xx_HAL_Driver/Inc/stm32f4xx_hal.h
#            STM32F4xx_HAL_Driver/Src/stm32f4xx_hal.c
#)
#target_link_libraries(psdk_bsp m)

#add_library(psdk_hal
#            STM32F4xx_HAL_Driver/Inc/stm32f4xx_hal.h
#            BSP/stm32f4xx_hal_conf.h
#            STM32F4xx_HAL_Driver/Src/stm32f4xx_hal.c
#)   
#target_link_libraries(psdk_hal m)