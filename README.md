# niceties_collection
A collection of template sensors, automations, node-red flows and other which I find nice to have.


HA Sensors:
* low_battery_entity_counter.yaml
  * A sensor for counting the total of devices with a battery level <= 'value'
  
    <img src="https://user-images.githubusercontent.com/58105460/214123126-746e9f91-c854-4520-be31-f5948f00adf3.png" width="400">
    
* count_open_doorswindows.yaml
  * A sensor for counting open doors and windows.



HA UI:
* samsung_washer.yaml
  * UI card displaying the current state of the washer
  
    <img src="https://user-images.githubusercontent.com/58105460/214364246-2f30003d-8cb7-4bef-a085-502dc491e809.png" width="400">
    
Automations:
* lights_random_predefined_colors.yaml
  * Add this as an action to generate a random (predefined list) color of the light(s).
* automatic_light_with_dim.yaml
  * My own automatic lights by motion, where current brightness state is saved, lights are dimmed down, then previous brightness state restored at the next motion.

Node Red Flows:
* notify_persons_at_home.yaml
  * Send notifications only to the residents currently at home. E.g. the washer is done, fridge is left open.
