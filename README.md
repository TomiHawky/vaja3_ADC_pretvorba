# vaja3_ADC_pretvorba

Cilj naloge: S pomočjo programskega okolja STM32CubeIDE in HAL knjižnicami sprogramirajte mikroprocesor tako, da bo izvajal ADC pretvorbe sprožene s časovnimi prekinitvami (interrupt).

2. Postopek inicializacije periferije.  
  - Uporabljena razvojna plošča je *STM32F401C-DISCO*
  - Izbran pin je *PA1*
  - Poleg pina se izpiše *ADC_IN1*
  - Ko spremenimo APB1 Timmer na 16 MHz se prilagodijo ostale nastavitve.
  - Če želimo frekvenco nastaviti na *1 kHz* moramo nastaviti Prescaler na *16 000*
  - Za spreminjanje stanje LED je uporabljena komanda *HAL_GPIO_TogglePin(GPIOD, GPIO_PIN_12);*
