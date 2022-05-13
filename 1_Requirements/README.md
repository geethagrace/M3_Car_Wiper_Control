# INTRODUCTION:
The main objective of this project is wiper control system using STM32 discovery board . It is used for on controlling the motion of wiper based on frequency. Wiper is an essential component that used to wipe the raindrops or any water from the windscreen. Wipers are designed
and made to clear the water from a windscreen.
# FEATURES:
1. When push button is long pressed for 2s , ignition system will be at ACC (i.e.) red led will be ON . 

2. Wiper ON condition depends on short press of the user input, Blue, Green and Orange LEDs come ON one at a time with the set frequency, The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz

3. Wiper OFF condition depends on the 4th press of push button .

4. When push button is again long pressed for 2s , ignition system will be at lock (i.e.) red led will be OFF .
# 4W'S and 1H:
## What?
* It's an application of Wiper Control System for every vehicles. Wiper status will be Indicated through LED's. and controlled using push button.
## WHY?
* It is used for drivers safety and speed is controlled with frequency.
## WHERE?
* It can be used in every car to keep the windscreen clean. 
## WHO?
*  It is used for people who wants safety and clean vision in weather conditions..
## HOW?
* It works with a push button and 4 leds . Red led is for loac/unlock and 3leds are considered as wiper sysem.

# SWOT ANALYSIS:
## Strength:
- Increases the safety of the travellers.
- Easy handle and usage of features through a simple User Button.
- Cost efficient and easy to construct.
- Prevents the cause of road accidents.
## Weakness:
- As technology is wide now-a-days, it is only controlled using push button which can be controlled using timers with more efficiency.
## Opportunity:
- Now-a-days automobile industries are getting updated, so it has a wide scope . It helps the user to cope with the real time environmental issues.   
## Threat:
- Now there are many updation in automobile industries.

# REQUIREMENTS:
## High level requirements:
| S.no | High level requirement | Description | Status |
| :---:| :---: | :---: | ---: |
| 1 | HLR1 |  STM32F407 | Done |
| 2 | HLR2 | Cygwin | Done |
| 3 | HLR3 | Qemu | Done |
| 4 | HLR4 | ON/OFF Push button | Done |

## Low level requirements:
| S.no | Low level requirements | Description | Status |
| :---: | :---: | :---: | ---: |
| 1 | LR1 | RED led ON | Done |
| 2 | LR2 | 3leds blinking with 1hz frequency | Done |
| 3 | LR3 | 3leds blinking with 4hz frequency | Done |
| 4 | LR4 | 3leds blinking with 8hz frequency | Done |
| 5 | LR5 | RED led OFF | Done |



