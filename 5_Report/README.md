# CAR WIPER CONTROL SYSTEM 

## ABSTRACT
   Wiper is an essential component that used to wipe the raindrops or any water from the windscreen. Wipers are designed
and made to clear the water from a windscreen.The system is developed to mitigate driving distractions and allow drivers to focus on their primary task of driving. The distraction eliminated with the development of this product is the manual adjustment of windshield wipers when driving in precipitation and made to clear the water from a windscreen. Wipers keep the windshield of a vehicle clear from rain water, snow, dust and road spray. 
   
   The first windshield wipers were operated manually by moving a lever inside the car. Later wiper designs were powered by the engine's manifold vacuum. Virtually all wipers today employ an electric motor coupled with a linkage mechanism and are actuated by a knob beside the steering wheel. The wiper blade speed can be adjusted by the driver.
   
   Here in this project we are using STM32F407vg  arm microcontroller. Considering the 4 leds as wiper and through switch present in STM32 board we are going to control wiper actions.
   * RED led as ignition key.
   * BLUE , GREEN , ORANGE leds as wiper.

   When switch is long pressed for 2s, Ignition Key Position will be at ACC (i.e.) Red led will be ON. On press of the user input, Blue, Green and Orange leds come ON one at a time with the set frequency, The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz. On the 4th press of the switch, led glow pattern gets stopped. When again switch is long pressed for 2s , Ignition Key Position will be at Lock (i.e.) Red led will be OFF.

## INTRODUCTION:
 The main objective of this project is wiper control system using STM32 discovery board . It is used for on controlling the motion of wiper based on frequency. Wiper is an essential component that used to wipe the raindrops or any water from the windscreen. Wipers are designed and made to clear the water from a windscreen.

## FEATURES:

1. When push button is long pressed for 2s , ignition system will be at ACC (i.e.) red led will be ON . 
2. Wiper ON condition depends on short press of the user input, Blue, Green and Orange LEDs come ON one at a time with the set frequency, The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz
3. Wiper OFF condition depends on the 4th press of push button .
4. When push button is again long pressed for 2s , ignition system will be at lock (i.e.) red led will be OFF .

## 4W'S and 1H:
### What?
* It's an application of Wiper Control System for every vehicles. Wiper status will be Indicated through LED's. and controlled using push button.
### WHY?
* It is used for drivers safety and speed is controlled with frequency.
### WHERE?
* It can be used in every car to keep the windscreen clean. 
### WHO?
*  It is used for people who wants safety and clean vision in weather conditions..
### HOW?
* It works with a push button and 4 leds . Red led is for loac/unlock and 3leds are considered as wiper sysem.

## SWOT ANALYSIS:
### Strength:
- Increases the safety of the travellers.
- Easy handle and usage of features through a simple User Button.
- Cost efficient and easy to construct.
- Prevents the cause of road accidents.
### Weakness:
- As technology is wide now-a-days, it is only controlled using push button which can be controlled using timers with more efficiency.
### Opportunity:
- Now-a-days automobile industries are getting updated, so it has a wide scope . It helps the user to cope with the real time environmental issues.   
### Threat:
- Now there are many updation in automobile industries.

## REQUIREMENTS:
### High level requirements:
| S.no | High level requirement | Description | Status |
| :---:| :---: | :---: | ---: |
| 1 | HLR1 |  STM32F407 | Done |
| 2 | HLR2 | Cygwin | Done |
| 3 | HLR3 | Qemu | Done |
| 4 | HLR4 | ON/OFF Push button | Done |

### Low level requirements:
| S.no | Low level requirements | Description | Status |
| :---: | :---: | :---: | ---: |
| 1 | LR1 | RED led ON | Done |
| 2 | LR2 | 3leds blinking with 1hz frequency | Done |
| 3 | LR3 | 3leds blinking with 4hz frequency | Done |
| 4 | LR4 | 3leds blinking with 8hz frequency | Done |
| 5 | LR5 | RED led OFF | Done |

## BLOCK DIAGRAM :
![image](https://user-images.githubusercontent.com/101448322/168249042-c6ed244e-6a67-46d9-9775-a2e3ddf2d33e.png)

## FLOWCHART :
![image](https://user-images.githubusercontent.com/101448322/168246367-bc8f9d3f-afe0-4170-bfa7-956bfea4a334.png)

## TEST PLAN AND OUTPUT :

| **Test ID** | **Description** | **Input** | **Output** | **Status** |
| --- | --- | --- | --- | --- |
| TID\_01 | Turning ON the vehicle (ACC)| press = 1 | RED led is ON  | PASS |
| TID\_02 | Wiper ON - frequency(1hz)| press = 2 | BLUE,GREEN and ORANGE glow squentially  | PASS |
| TID\_03 | Wiper ON - frequency(4hz)| press = 3 | BLUE,GREEN and ORANGE glow squentially  | PASS |
| TID\_04 | Wiper ON - frequency(8hz) | press = 4 | BLUE,GREEN and ORANGE glow squentially  | PASS |
| TID\_05 | Turning OFF the vehicle (ACC) | press = 5 | RED led is OFF | PASS |

## SOFTWARE USED :
* STM32Cube IDE
* Qemu
* cyqwin
* Windows build tools

