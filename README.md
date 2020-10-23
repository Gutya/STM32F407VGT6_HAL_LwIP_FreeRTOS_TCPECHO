Основные изменение при конфигурации CubeMX

1. Sys->Timebase Source->TIM
2. ETH->PHY->1 (заввисит от того, на что притянута ножка PHY на самом контроллере ethernet)
3. ETH->RxMode->Interrupt Mode
4. NVIC->Ethernet global interrupt->5
5. FreeRTOS->Config parameters->MINIMAL_STACK_SIZE->256