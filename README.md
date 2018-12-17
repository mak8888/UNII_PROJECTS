# UNII_PROJECTS #Line_following_Robot
This code is self-explanatory and the internal working of IR module (LM358) is explained blow

The IR LED on getting proper biasing emits Infra-red light. This IR light is reflected in case of a white surface and the reflected IR light is incident on the photodiode. The resistance of the photodiode decreases, which leads to an increase in current through it and thus the voltage drop across it. The photodiode is connected to the base of the transistor and as a result of increased voltage across the photodiode, the transistor starts conducting and thus the motor connected to the collector of the transistor gets enough supply to start rotating. In case of a black color on the path encountered by one of the sensor arrangement, the IR light is not reflected and the photodiode offers more resistance, causing the transistor to stop conduction and eventually the motor stops rotating.
NOTE: LM358 module consist a IR LED and photodiode pair
