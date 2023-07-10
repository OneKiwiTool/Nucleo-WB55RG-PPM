# Nucleo-WB55RG-PPM

- PPM Freq = 44.(4)Hz = 22.5ms

$$Update\_event=\dfrac{TIM\_CLK}{(PSC + 1)(ARR + 1)}$$
- TIM_CLK = timer clock input
- PSC = 16-bit prescaler register
- ARR = 16/32-bit Autoreload register
- RCR = 16-bit repetition counter
- TIM_CLK = 64 MHz
- Prescaler = 24
- Auto reload = 57599

$$Update\_event=\dfrac{64.000.000}{(24 + 1)(57.599 + 1)}=\dfrac{400}{9}Hz$$
- TIM2_CH1: PA0
- TIM2_CH2: PA1

- https://github.com/v0idv0id/STM32-Scaler