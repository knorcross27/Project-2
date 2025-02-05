# Project 2: Automatic Headlight Control System
## Sami Foodim and Kye Norcross
### System Behavior:
The goal for this project was to build upon the Driver's Education Car Alarm System form Project 1, and then create a headlight subsystem as well. Within the ignition subsystem, we added the ability for the ssytem to allow additional start attempts. This means that if the user attempts to inhibit the ignition when it is not enabled (i.e. when the user starts the car if either seatbelt is unbuckled or either seat is not occupied), the buzzer will sound, error message and reasons will be displayed, and then they will be given the opportunity to start the car again. Additionally, we added a function that allowed the engine to continue running even if the driver/passenger removed their seatbelts or exited the car, after initially having all conditions satisfied and starting the car. Lastly, for the ignition subsystem we made it so that when the engine was running, the engine could be stopped when the ignition button was pushed and then released.

When creating the headlight subsystem, the first thing we did was make is so that if the engine is running and the user selects ON the low beams (LEDs) turn on and if they select OFF the LEDs turn off. Turning them ON/OFF was controlled by the potentiometer on the board. Then, if the user selected the AUTO position on the potentiometer, if the light level was above a daylight level the headlights would switch off after a two second delay. If the light level was below a dusk level, the headlights would switch on after a one second delay. When in between these two levels, the headlights would hold their previous state. Lastly, all the headlights should turn off when the engine is off.

### Starting Repository:
We built upon Kye's Project 1 code which can be found here: [https://github.com/kaitophuc/ECE-218/tree/main]

### Summary of Testing Results:
Everything in the project worked as it should, initially in the testing phase we had some problems keeping the engine running when someone took their seatbelt off, or exited their seat. But overall, everything worked properly for the demonstration.

Table 1: Ignition Subsystem Testing Results

<img width="483" alt="Screenshot 2025-02-01 at 12 16 41 PM" src="https://github.com/user-attachments/assets/a16b4f69-2110-4146-a120-b630600d02bc" />
<img width="636" alt="Screenshot 2025-02-01 at 12 29 02 PM" src="https://github.com/user-attachments/assets/2277de1f-6b01-4f05-90ef-13f26f8a8abd" />

Table 2: Headlight Subsystem Testing Results
<img width="568" alt="Screenshot 2025-02-01 at 12 14 51 PM" src="https://github.com/user-attachments/assets/2e700eb9-11bc-4186-ba3f-b7c3aae573da" />
