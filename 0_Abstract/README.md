# CAR WIPER CONTROL SYSTEM 

## ABSTRACT :
   Wiper is an essential component that used to wipe the raindrops or any water from the windscreen. Wipers are designed
and made to clear the water from a windscreen.The system is developed to mitigate driving distractions and allow drivers to focus on their primary task of driving. The distraction eliminated with the development of this product is the manual adjustment of windshield wipers when driving in precipitation and made to clear the water from a windscreen. Wipers keep the windshield of a vehicle clear from rain water, snow, dust and road spray. 
   
   The first windshield wipers were operated manually by moving a lever inside the car. Later wiper designs were powered by the engine's manifold vacuum. Virtually all wipers today employ an electric motor coupled with a linkage mechanism and are actuated by a knob beside the steering wheel. The wiper blade speed can be adjusted by the driver.
   
   Here in this project we are using STM32F407vg  arm microcontroller. Considering the 4 leds as wiper and through switch present in STM32 board we are going to control wiper actions.
   * RED led as ignition key.
   * BLUE , GREEN , ORANGE leds as wiper.

   When switch is long pressed for 2s, Ignition Key Position will be at ACC (i.e.) Red led will be ON. On press of the user input, Blue, Green and Orange leds come ON one at a time with the set frequency, The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz. On the 4th press of the switch, led glow pattern gets stopped. When again switch is long pressed for 2s , Ignition Key Position will be at Lock (i.e.) Red led will be OFF.
