# Rivian OTA Changelog

## 2022.31.0 (cf5aac07)

Initial public release: August 24, 2022

### New Camping App Available

For your convenience, you can now do the following:

- Energy use: To optimize your camping experience inside or outside the vehicle,
  choose your vehicle's energy use: Stay Off, Normal, or Stay On.
- Outlets: 120 V, 12 V, USB-C, and the wireless charging pad stay on. The
  outlets can stay on for a maximum of 24 hours, with the option to chose a
  shorter duration.
- Camp courtesy: You can turn off exterior lights, vehicle sounds, proximity
  locking or unlocking and the Gear Guard alarm sound. This alto enables quiet
  cooling or heating.
- Displays: You can turn off the driver, center, and rear displays.
- Flood lights: You can turn on the flood lights, which are located neat the
  side mirrors.
- Vehicle leveling: You can level the vehicle when parked on uneven terrain.

Camping controls, except for the outlets, are avatable only when the vehicle is
in Park. Choose **Camping**
<img src="./images/icons/camping.png?raw=true" alt="camping app icon" height="20px" />
from the menu on the center display.

### Range Now Viewable as Percentage of State of Charge

For the range estimate on the driver display, you can set the state of charge to
show distance, percentage, or both. Choose **Settings**
<img src="./images/icons/settings.png?raw=true" alt="settings icon" height="20px" />
from the menu on the center display, and then choose **Vehicle**. Choose
**Units**. Under **Range**, in Driver Display, choose the distance, **%**
(percentage), or **Both**.

### Units of Measurement Now Available in Metric

You can now chose metric units of measurement for speed, distance, temperature,
and air pressure. Choose **Settings**
<img src="./images/icons/settings.png?raw=true" alt="settings icon" height="20px" />
from the menu on the center display, and then choose **Vehicle**. Choose
**Units**.

### New Vehicle Controls on the Rivian Mobile App

The Rivian mobile app version 1.5.0 or later enables new vehicle commands that
allow you to remotely control the hood, vent the windows, and activate or stop
the panic alarm. (If the new controls don’t automatically appear in the Rivian
mobile app, we recommend that you restart the app.)

### Additional Improvements

- Reduced noise from cabin climate upon vehicle startup.
- Reduced the offset of the speedometer display. It now displays no more than
  1-2 mph over the actual vehicle speed.
- Introduced new algorithms for improved locking or unlocking speed.
- Improved user profile detection in case there are multiple users. Also fixed
  occasional issue: Side mirrors don’t move into the profile position when the
  vehicle unlocks via proximity unlocking.
- Addressed issues when opening the front trunk may require pressing the button
  twice if the vehicle is asleep.
- Displays now can’t be accessed if the Gear Guard alarm is triggered.
- Reduced battery drain while the vehicle is parked by an average of 10%.
- Improvements to vehicle sleep behavior:
- Rear occupancy detection: Heavy objects left in the rear seats won’t prevent
  vehicle sleep.
- Outlets that are turned on in the Energy app automatically turn off after 24
  hours; then the vehicle can sleep.
- Fixed garage door opener interoperability issues with LiftMaster 8500/8500W,
  CSW24UL, and Jackshaft openers.
- Addressed issues when the FM Radio would freeze or restart.
- Fixed an occasional issue: Alexa doesn’t wake up or respond to voice commands.
- Fixed an occasional issue: The audio volume changes when the vehicle wakes.
- Fixed an occasional issue in the Navigation app: The vehicle retains the
  satellite view while it sleeps.
- Fixed a rare issue: The trip planner within the Navigation app is offline even
  though the network status indicates it is connected.
- Fixed an occasional issue: The charge session summary indicates 0 kWh added
  after a charge session.
- Fixed an occasional issue: A partial keyboard is shown for a phone address or
  media search.
- Made various improvements to Adaptive Cruise Control and lane centering for
  Highway Assist.
- Improved notifications in case Highway Assist is unavailable.



## 2022.27.02 (1b35e554)

Source:
  [R1S](https://stories.rivian.com/r1s-software-update-2022-27-02),
  [R1T](https://stories.rivian.com/r1t-software-update-2022-27-02)

Initial public release: August 4, 2022

### Automatic Ride Height

We have added the ability to enable automatic or manual ride height control to
All Purpose and Conserve modes. When the ride height is set to Auto, the
vehicle automatically changes to Low ride height at higher speeds for increased
efficiency and energy conservation. The vehicle returns to Standard ride height
at lower speeds for increased ground clearance and comfort.

Conserve Auto mode has now the same ride height strategy as All Purpose, and
hence reduces the amount of suspension auto-adjustment when approaching stop
lights in urban environments.

To turn off automatic ride height changes in All-Purpose or Conserve mode,
manually select another available ride height These manual settings are now
latching across drive cycles.

### Direct Current Fast Charging

We have improved DC fast charging performance and battery preconditioning when
using trip planner. In ideal conditions, you may experience up to a 20%
improvement in miles added per minute.

### Additional Improvements

- Improved automatic leveling behavior of the vehicle by reducing the frequency
  of suspension adjustments when the vehicle is at a stand still (4x reduction)
- Fixed occasional issues with loss of calibration of climate vents
- Improved cabin comfort vent control behavior
- Improved cabin comfort cooling while also cooling the drive train in hot
  conditions
- Improved range loss over night (15% average improvement)
- Improved ride comfort with suspension damping changes in high and highest ride
  heights
- Front Trunk can now be closed if vehicle is locked
- **R1S**: Liftgate can now be closed if vehicle is locked
- Fixed a rare issue with lock/unlock passive unlock where the closures were
  unlocked, but door handles did not unfold
- Improved turn signal canceling behavior when it sometimes canceled too soon
  during the steering wheel rotation
- Improved camp speaker lock/unlock functionality
- Fixed an occasional issue that could cause the volume level settings to change
  after some cases of vehicle inactivity
- Fixed a rare issue when mini media player controls and steering wheel media
  controls become unresponsive
- Fixed an issue when media audio pauses upon waking Alexa
- Addressed a rare issue of cellular connectivity not restored when the vehicle
  returns from poor coverage areas
- Fixed an issue when the hotspot would turn off after vehicle would go to sleep
- Fixed an occasional issue when Alexa would not be able to connect to the
  internet
- Improved Bluetooth pairing for some Android phones
- Improvements to Highway Assist lane centering control
- Improved informative notification display to let the user know that they
  should center the vehicle in the lane more before Highway Assist can be
  engaged



## 2022.23.05 (007dde12)

Source:
  [R1S](https://stories.rivian.com/r1s-software-update-2022-23-05),
  [R1T](https://stories.rivian.com/r1t-software-update-2022-23-05)

Initial public release: July 6, 2022

Addressed an issue when the Rivian app occasionally displayed cold temperatures
while the vehicle is idle



## 2022.23.03 (8babae52)

Source:
  [R1S](https://stories.rivian.com/r1s-software-update-2022-23-03),
  [R1T](https://stories.rivian.com/r1t-software-update-2022-23-03)

Initial public release: June 30, 2022

### New Mode for Pets

When Pet Comfort is active, your vehicle maintains the last cabin temperature
you set and disables the interior alarm, so pets can remain in your vehicle
after you leave. The center display shows an animated message with the cabin
temperature, so passersby know your pet is safe. Choose the **Temperature**
button from the menu on the center display, and then choose the **Pet Comfort**
button. When you return and start driving, your vehicle automatically turns off
Pet Comfort.

To monitor Pet Comfort in the Rivian app on your smartphone, ensure you're
using version 1.4.1 or later.

### New Front Camera View Behavior For Parking

We made it easier to park in tight parking spots with confidence. When you
shift the vehicle from Reverse to Drive, the front camera view automatically
appears on the center display until you exceed approximately 5 mph. This allows
you to see the front camera and bird's eye views without having to take your
hands off of the steering wheel. To disable this feature, choose **Settings**
from the menu on the center display, and then choose **Vehicle**. Choose
**Driver+** and turn off **Automatic Front Camera**.

### New Setting to Adjust Cabin Lights

We added a control to adjust the brightness of cabin lights. Choose **Vehicle**
from the menu on the center display, and then choose **Lighting and displays**.

### Updated Energy App

The Energy app is now a separate application; choose **More** from the menu on
the center display, and then choose **Energy**. We also added a Session Summary
to provide details about energy usage for charge sessions.

### Additional Improvements

- The vehicle now remains in Off-Road mode even after you have left the
  vehicle. The vehicle automatically switches to All-Purpose mode the next
  calendar day.
- Updated algorithm to improve proximity locking and unlocking of the vehicle
- Improved the consistency of user profile loading. The vehicle now loads the
  user profile associated with the phone
- Reduced volume level of the pedestrian audio alert while still complying with
  the Federal Motor Vehicle Safety Standard (FMVSS) No. 141
- Added control of the windshield vent on the climate panel
- Improved cooling and air conditioning response when you enter a vehicle with a
  hot cabin
- Improved Automatic High Beams behavior: To turn on **Automatic High Beams**,
  choose Settings from the menu on the center display, and then choose
  **Vehicle**. Choose **Exterior Lights** or **Driver+**, and then turn on
  **Automatic High Beams**.
  - To temporarily turn off Automatic High Beams, push or pull the lights stalk.
    To turn on Automatic High Beams again, push the lights stalk away from you
    (the Automatic High Beams setting must remain turned on).
- Updated Car Wash mode to retract door handles, disable proximity locking, and
  enhance support of belt conveyor systems.
- You can now exit the vehicle while it's in Neutral. The vehicle stays in
  Neutral and won't automatically lock the doors.
- Enhanced color accuracy of camera views. Also improved brightness control for
  nighttime usage.
- Improved connection stability of paired Bluetooth devices
- For the Navigation app, charger filters now persist while the audio panel
  appears on the center display.
- Fixed an occasional issue when the charger filter for +100 kW in the
  Navigation app doesn't work
- **R1S**: The center display now notifies you when the liftgate can't close
  because the tailgate isn't closed.
- Fixed an issue when the vehicle turns off accent lighting after a software
  update or vehicle reset. The accent lighting defaults to ON when you update
  the software to version 2022.23. Then for future software updates, the
  existing setting will persist after the software update.
- Fixed an issue when the vehicle locks the rear display after it sleeps
- Fixed an issue with the behavior of the Camp Speaker lock button in the
  Settings app
- Improved SOS call handling: Incoming calls that are spam or invalid are now
  rejected.
- Improved Highway Assist availability logic after a highway interchange, and
  improved notification consistency when approaching highway junctions
- Enabled smoother acceleration and deceleration performance in Adaptive Cruise
  Control and Highway Assist when you press the accelerator pedal
- Made multiple improvements to lane centering control for Highway Assist
- Improved pairing compatibility with garage door openers
- Fixed a rare issue when the vehicle removes garage doors from the Garages list
- Fixed very rare cases of corrupted content on the center display



## 2022.19.03 (a4073715)

Source:
  [R1S](https://stories.rivian.com/r1s-software-update-2022-19-03),
  [R1T](https://stories.rivian.com/r1t-software-update-2022-19-03)


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
- **R1S**: Improved cabin comfort during DC fast charging
- Improved garage door flyout behavior by allowing it to open while in reverse
  and making the timeouts more consistent
- **R1S**: Added a notification to indicate rear wiper is turned off
- **R1S**: Liftgate lights now turn on when liftgate is opened
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
- **R1T:** Added functionality to the tonneau cover button to enable manual control
  - Press and hold the tonneau cover button and then release the button to stop
- Enrolled key band will now display in the driver keys list
- Improved Birds eye view stitching based on suspension ride height
- Improved passive entry behavior near front trunk
- **R1S:** Improved passive entry behavior near liftgate
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
