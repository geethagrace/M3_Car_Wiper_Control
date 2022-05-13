# M3_Car_Wiper_Control

In this project we are using STM32F407vg arm microcontroller. Considering the 4 leds as wiper and through switch present in STM32 board we are going to control wiper actions.

* RED led as ignition key.
* BLUE , GREEN , ORANGE leds as wiper.

When switch is long pressed for 2s, Ignition Key Position will be at ACC (i.e.) Red led will be ON. On press of the user input, Blue, Green and Orange leds come ON one at a time with the set frequency, The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz. On the 4th press of the switch, led glow pattern gets stopped. When again switch is long pressed for 2s , Ignition Key Position will be at Lock (i.e.) Red led will be OFF.

# Code Quality and Workflow

| Codacy Badge | Workflow Badge |
| --- | --- |
| [![Codacy Badge](https://app.codacy.com/project/badge/Grade/261b649476c2426a889a36a6b9fd76c6)](https://www.codacy.com/gh/geethagrace/M3_Car_Wiper_Control/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=geethagrace/M3_Car_Wiper_Control&amp;utm_campaign=Badge_Grade) | [![Analysis](https://github.com/geethagrace/M3_Car_Wiper_Control/actions/workflows/analysis.yml/badge.svg)](https://github.com/geethagrace/M3_Car_Wiper_Control/actions/workflows/analysis.yml) |



