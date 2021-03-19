Pin PE9 omogoča aktiviranje prvega kanala kot PWM Generation CH1.
Poleg pina se izpiše TIM1_CH1.
Perscaler vrednost je 16.
Ko se parameter Period nastavimo na 100 se vrednost spremeni na 10 kHz
Pri spremebi paramentra Pulse na 50 in 25 se v kodi izpiše
sConfigOC.Pulse = 50.
sConfigOC.Pulse = 25 .
1. vrstica: Nastavi spremenljivko dutyCycle za duty cycle.
2. vrstica: Spremenljivki dutyCycle prišteje 10.
3. vrstica: Če spremenljivka dutyCycle preseže 90, jo ponastavi na 10

Komentar: S pomočjo kode je mozno spreminjati obnasanje osiloskopa. Pomembno je biti pozoren na vse nastavitve na osiloskopi.
