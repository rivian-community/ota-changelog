# Rivian OTA Changelog

## 2022.19.03 (a4073715)

Initial public release: May 27, 2022

**Important Note:** This software release will automatically scan the
characteristics of the front passenger seat and will display a notification to
the driver if the seat is affected by safety recall FSAM-651

### New Battery Preconditioning en route to Charger

Battery preconditioning strives to minimize DC fast charging time and achieving
optimal charging performance by bringing the battery to ideal temperatures while
navigating to a DC fast charger. Preconditioning will automatically start when
using the Navigation app and routing to a DC fast charger. The system cools or
heats based on battery temperature. The time spent preconditioning can vary
based on the advertised power of the charger you're navigating to, and the state
of charge with which you may arrive at the DC fast charger.

### New Soft Sand Mode

This new off-road drive mode maximizes vehicle performance and capability in
soft sand. This mode uses unique traction control settings, minimal stability
control support, and reduced regenerative braking to optimize vehicle handling.
Navigate to **Drive Modes** button
<img src="./images/icons/drive-modes.png?raw=true" alt="drive modes icon" height="20px" />
on the center display, then choose the **Off-Road** button, and then choose the
**Soft Sand** button.

### Additional Improvements

- Refined Vehicle Hold feature with smoother and quieter auto hold disengagement
- Improved regenerative braking in low traction surfaces and during descents on
  rocky terrain in Rock Crawl mode
- Improved range estimation in Navigation app when routing to a destination
- Added Home mode for proximity lock / unlock. This will prevent frequent
  lock / unlock issues if your vehicle is parked very closely to your phone, and
  the resulting overnight range loss.
  - **Important Note:** Enabling this in the Vehicle Access settings menu will
    leave your vehicle unlocked when parked at your home location set in the
    Navigation app.
- User can now customize their vent and recirculation settings while climate
  control is in Auto mode
- Improved garage door flyout behavior by allowing it to open while in reverse
  and making the timeouts more consistent
- Bird's eye view now shows when doors, tailgate, and front trunk are open
- New algorithm to improve the accuracy and aesthetics of backup camera view
  guidelines when turning the steering wheel
- Reduced the number of redundant Gear Guard videos captured
- Added Gear Guard Video functionality to automatically delete videos after
  10 days
- Addressed issues with loss of Gear Guard videos post OTA update, and
  instability of "motion detection" tab
- Added visual and audible notification to the driver to place hands on wheel in
  cases where Highway Assist lane centering control performance may be limited
- Improved Highway Assist availability logic after a highway interchange, and
  improved notification consistency when approaching highway junctions
- Improved Automatic Cruise Control behavior when engaging and disengaging
  feature for smoother speed transitions
- Addressed issues with Alexa responsiveness and wake sensitivity
- Fixed a rare issue when Navigation app would reboot when using Alexa to find
  directions
- Updates to Spotify to provide indication of shuffle and repeat statuses on
  screen, appropriately visualize buffering, and minor fixes
- Fixed a rare issue where cabin preconditioning automatically turned on during
  charge sessions
- Fixed a rare occurrence when Bluetooth audio would not be available until the
  next drive
- Fixed an issue when leaving vehicle while on Hands Free Call would result in
  audio playing after vehicle is unoccupied
- Fixed very rare cases of camera displaying green squares
- Addressed very rare cases of 12v battery drain



## 2022.15.0 (bb3579b1)

Initial public release: May 2, 2022

### New Garage Door Opener

You can now control a garage door. To add a new garage, use one of the
following methods:

1. In the vehicle center display, choose the **Garage Door** button
   <img src="./images/icons/garage.png?raw=true" alt="garage door icon" height="24px" />
   in the status bar at the top of the screen, then choose **Add a Garage**.
2. Choose the **Settings** button
   <img src="./images/icons/settings.png?raw=true" alt="settings icon" height="20px" />
   from the menu on the center display. Choose **Connect** and then choose
   **Garages**.

### New Exterior Lights Settings

You can now control certain exterior lights, including the light bars and charge
port light when the vehicle is charging. Choose **Settings**
<img src="./images/icons/settings.png?raw=true" alt="settings icon" height="20px" />
from the menu on the center display. Choose **Vehicle** and then choose
**Exterior Lights**.

### New Automatic High Beams

To use Automatic High Beams, choose **Settings**
<img src="./images/icons/settings.png?raw=true" alt="settings icon" height="20px" />
from the menu on the center display. Choose **Vehicle** and then choose
**Driver+**. Turn on **Automatic High Beams** and then push the lights stalk
away from you.

### Additional Improvements

- Improved the sleep performance and consistency to reduce range loss while
  vehicle is in idle state
- Improved accelerator pedal response when transitioning between drive modes
- Improved automatic leveling behavior on uneven terrain
- Improved regenerative braking performance after DC fast charge sessions
- Introduced new "Show and Tell" mode to keep exterior lights and screens ON
  while vehicle is in Park. This mode is deactivated in drive or at less than 30
  miles of range.
- Added functionality to the tonneau cover button to enable manual control
  - Press and hold the tonneau cover button and then release the button to stop
- Enrolled key band will now display in the driver keys list
- Improved Birds eye view stitching based on suspension ride height
- Improved passive entry behavior near front trunk and liftgate
- Improved **AUTO** climate control response when frequently re-entering vehicle
- Reduced frequency of navigation reroute suggestions after initial prompt
- Addressed inaccurate range displayed in rare cases, after DC fast charging
- Addressed rare cases of total audio loss
- Addressed rare cases of false alarm activations
- Improved Lane Keeping Assist, Adaptive Cruise Control, and Highway Assist performance
- Enhanced stability of infotainment system

```
        .     .....       .
       . .  :::::::-:.   . .
            :---::--:.
           .::....:.:.
           .:..-==:....
          ..............
        .----::..:--====-
        =+++++=..=++++++++
      ...-+++++:.=++*++++:..
    .....:+++++..+++*+++=....
   ......=++===..===+++++::..:.
 ....:::++++==-..====++++=......
......-======+:..+=======+.:.....
....::-+++++++:..+++++++++:....::
:.:.:.:#+++*++:-:=++++++++: ....:.
.......++=++==**#+**+****+- ......
   . ..++=++----+----*==+=:  :....
      :===+=----+----+====-
       -=======. ===--====-
        ..:..:    ..:..:.
        --:::-.   =-----:
        -....:.   -     :
        =.   ..   -    :-
```


## 2022.11.02 (d9184158)

Initial public release: April 11, 2022

### New Car Wash Mode

Car Wash mode closes the windows, locks the charge port door, and pauses other
functions while you wash your vehicle. To use Car Wash mode, choose **Vehicle**
<img src="./images/icons/vehicle.png?raw=true" alt="vehicle icon" height="20px" />
from the menu on the center display.

### Updated TuneIn Design

We've improved the user interface, features, performance, and responsiveness of
TuneIn.

### Improved DC Fast Charging Performance

We enabled the support of 500 A charging.

### Additional Improvements

This software release includes the following:

- Improved traction control in muddy terrain
- Added Low ride height in Conserve drive mode as a manual setting
- Improved ride height leveling accuracy
- Improved range loss consistency while the vehicle is sleeping
- Improved interoperability with third-party public chargers
- Improved passenger detection so climate, media, and other features stay active
  while the driver is away, and front or rear passengers remain in the vehicle
- Vehicle now selects cellular network as preferred network when vehicle is not
  in Park
- New user interface for Phone panel with a numeric keypad and mute button
- Addressed loss of connectivity in rare cases
- Improved defrost heating and air circulation
- Improved Auto behavior for climate controls
- Improved the automatic brightness and white balance when you select the backup
  camera view or bird's eye view
- Improved Gear Guard detection in low light and snow conditions
- Improved Gear Guard activation at Home
- Improved stability of the infotainment system
- Improved performance of Adaptive Cruise Control and Highway Assist


## 2022.7.0 (b1146918)

Initial public release: March 5, 2022

### New Bird's Eye View

The bird's eye view is available to increase visibility around the vehicle when
you back up the vehicle or access it from the Cameras app: choose **Cameras**
<img src="./images/icons/video-camera.png?raw=true" alt="video camera icon" height="20px" />
from the menu on the center display.

### New Trip Data

You can track distance, speed, duration, efficiency, and energy for two trips.
Choose **Vehicle**
<img src="./images/icons/vehicle.png?raw=true" alt="vehicle icon" height="20px" />
from the menu on the center display, and then choose **About My Rivian**.

### Enhanced Owner's Guide

We've improved the usability of the Owner's Guide. Choose **More**
<img src="./images/icons/dots.png?raw=true" alt="ellipsis icon" height="20px" />
and then **Owner's Gulde**
<img src="./images/icons/book.png?raw=true" alt="book icon" height="20px" />
from the menu on the center display.

### Rear Display Now Available

To unlock the rear display, choose **Vehicle**
<img src="./images/icons/vehicle.png?raw=true" alt="vehicle icon" height="20px" />
from the menu on the center display, and then choose **Lighting and Displays**.

### Additional Improvements

This software release includes the following:

- Improved automatic locking and. unlocking of vehicle, including quicker
  deployment of door handles and a better user experience when approaching the
  vehicle from the front or rear
- Increased driving comfort during highway drives and enabled a smoother
  response to accelerator pedal changes for a better driving experience in
  on-road drive modes
- Reduced pedal travel required during hill climbs for a better driving
  experience in off-road drive modes
- Improved Vehicle Hold performance on very steep inclines
- Improved performance of Adaptive Cruise Control and Highway Assist
- Added the ability to reset vehicle settings in the Drive Modes app
- Enhanced the power gauge on the driver display
- Enhanced driver display user interface in Towing mode
- Improved responsiveness and stability of the infotainment system
- Improved performance and stability of the Navigation app
- Added vent control animation for a more intuitive user experience
- Added the capability to adjust more than one vent at a time
- Improved availability of the Gear Guard app
- Improved stability of Bluetooth connections
- Improved audio availability for a better listening experience


## 2022.3.1 (547d39ee)

Initial public release: February 4, 2022

### Tire Pressure Status Now Available on Driver Display

To view the current pressure of all tires while the vehicle is traveling,
long-press the left or right thumb control button on the left controls of the steering wheel.

### New App Name and Icon to Access Gear Guard Video

The Videos app is now named the Gear Guard app and uses a new icon. While the
vehicle is parked, you can access Gear Guard video by choosing **Gear Guard**
<img src="./images/icons/guard.png?raw=true" alt="guard icon" height="20px" />
from the menu on the center display. This release also includes multiple
improvements for the accuracy of Gear Guard motion detection.

### Additional Improvements

This software release includes the following:

- Enhanced infotainment system stability and usability
- Improved regenerative braking performance when the battery is at a high state
  of charge
- Improved DC fast charging curve and behavior in low temperatures
- Improved AC charging performance and efficiency
- Enhanced climate performance for increased cabin comfort
- Enhanced defog and defrost to quickly clear your windshield
- Improved sleep consistency, resulting in reduction of range loss while vehicle
  is parked
- Improved vehicle access performance for a more consistent user experience
- Improved Highway Assist performance, availability, and notifications
- Improved Adaptive Cruise Control performance and availability
- Improved vehicle suspension consistency and fault management
- Improved audio volume management for a better listening experience
- Improved Bluetooth hands-free audio stability
- Reduced interior lighting brightness at night for greater eye comfort in Auto
  mode
- Improved cellular and Wi-Fi connectivity performance
- Improved the Camp Speaker User Interface (UI)
- Improved UI on the driver display for exterior lighting selection using the
  lights stalk
- Improved UI on the driver display for front wiper mode selection using the
  wiper switch on the lights stalk


## 2021.49.2 (4e2d905f)

Initial public release: January 3, 2022

### Improved Navigation App

We enhanced navigation and usability for a more seamless experience, and the
vehicle will inform you of how much time you can save if you use a suggested
route that's faster than your current route.

### Enhanced Bluetooth Connectivity and Audio

We improved the stability of the Bluetooth connection and enhanced the audio
performance.

### Additional Improvements

This software release includes the following:

- Improved automatic locking and unlocking of vehicle
- Improved Highway Assist performance
- Improved Driver+ safety and awareness notifications
- Improved climate and defrost performance
- Enhanced User Interface (UI) support for the backup camera view
- Enhanced infotainment system performance and stability
- Enhanced switching between apps for smoother transitions on the center display
- Made various UI improvements to enhance usability

### Limitation

The rear display is temporarily locked and will be available for use in a future
update.


## 2021.45.1

(Unknown)
