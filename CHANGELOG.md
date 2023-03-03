# Rivian OTA Changelog

## 2023.06.02

Initial public release: March 2, 2023

Source:
  [R1S](https://stories.rivian.com/r1s-software-update-2023-06-02),
  [R1T](https://stories.rivian.com/r1t-software-update-2023-06-02)

### Additional Improvement

Improved the reliability of the key fob software update. If the key fob update
previously failed, you can try the update again without contacting Rivian
Service; go to **Settings**
<img src="./images/icons/settings.png?raw=true" alt="settings icon" height="20px" />
› **Vehicle** › **Updates**.



## 2023.06.00

Initial public release: March 2, 2023

Source:
  [R1S](https://stories.rivian.com/r1s-software-update-2023-06-02),
  [R1T](https://stories.rivian.com/r1t-software-update-2023-06-02)

### New Proximity Locking and Unlocking via Key Fob

Proximity locking and unlocking is now available via your key fob. To turn on
this feature, go to  **Settings**
<img src="./images/icons/settings.png?raw=true" alt="settings icon" height="20px" />
› **Vehicle** › **Access**. Also, if the battery level of the key fob is low, a
notification appears on the driver display, and you see a low battery indicator
when you go to **Settings**
<img src="./images/icons/settings.png?raw=true" alt="settings icon" height="20px" />
› **Drivers and Keys**.

We've also improved the proximity locking experience for both phones and key
fobs: locking is more consistent, and we've decreased the number of unintended
locking occurrences.

### Navigation Improvements

We've introduced the following new features in navigation:

- Place search is now powered by Google Maps™.
- You can now easily switch between charger status pins on the map to preview
  information. Choose a charger. Then choose **Start** to begin a new route to
  that charger.
- We've enhanced detection of your vehicle's arrival at its destination. The
  Navigation app now ends your trip when you park your vehicle near the
  destination.

### Enhanced Front Camera View

We've improved the front camera view on the center display:

- Increased the horizontal and vertical fields of view for the front camera to
  provide a better perspective of the bumper relative to any obstacles.
- Improved the image quality of the front camera and increased the number of
  usable pixels by 50%.

### Additional Improvements

- Driver+ Improvements
  - Increased the Highway Assist hands-off warning time period from 10 to 20
    seconds for your convenience.
  - Your vehicle now notifies you that rear Park Assist warnings aren't
    available while the Rear accessory setting is enabled.
  - Reduced the time window from 2 seconds to 1 second to engage Highway Assist
    when you push the drive stalk twice. This enhances usability when you
    initiate Adaptive Cruise Control with the first push of the drive stalk,
    accelerate the vehicle to the desired speed, and then push the drive stalk
    again to set the higher speed.
- Your vehicle now retains calibration for the windows, seats, and steering
  wheel after loss of 12 V battery power.
- Fixed a rare issue that briefly triggered limited performance mode when you
  started driving in cold ambient temperatures.
- Fixed a rare issue when quickly turning defrost on or off changed the set
  temperature to the maximum.
- Media Improvements
  - In Spotify®, added a progress bar for podcast episodes or audiobooks.
  - In Spotify and TIDAL®, added a notification to confirm when a song is added
    to a queue.
  - Fixed an issue where the FM radio channel frequency wasn't displayed
    properly.
  - Choosing the logo of a media source now goes to the Home tab of that app.
  - Fixed a rare issue when the Bluetooth® media album art wasn't displayed
    properly if you quickly switched between media sources.
- Bluetooth® audio is now transferred from your phone to the vehicle only when
  you open either of the front doors.
- Fixed a rare issue when the paired phone didn't appear in the Bluetooth panel.
- Fixed a rare issue with loss of cellular connectivity in Canada after the
  vehicle woke from sleeping.
- Fixed a rare issue with Gear Guard videos not being properly saved to USB
  external storage drives.



## 2023.02.03 (05a93d2e)

Initial public release: February 7, 2023

Source:
  [R1S](https://stories.rivian.com/r1s-software-update-2023-02-03),
  [R1T](https://stories.rivian.com/r1t-software-update-2023-02-03)

### Improved EPA-Estimated Range Numbers

Thanks to various incremental improvements over previous software updates, this
update includes updated EPA-estimated range. The update also increases the depth
of discharge, which increases the usable battery energy. You will now see higher
available miles at the top of charge.

### Key Fob Software Update

The new key fob firmware improves connection reliability and latency for faster
locking and unlocking. It also improves battery life performance compared to
very early versions of the firmware. If your key fob has an update available,
your vehicle will notify you on the center display. You can also go to
**Settings** › **Vehicle** › **Updates**.

**Important:** When updating your key for software, we recommend that you have
your phone set up as a key or have a spare key, such as a key card as a backup.

### New Door Ajar Notification

When proximity locking and unlocking is enabled, you will now be notified via
the Rivian mobile app if the vehicle fails to lock due to a door or closure that
is left open, and you've left the vicinity of the vehicle.

### Additional Improvements

- Reduced steering effort to maintain straight ahead driving on crowned roads.
- Software containment for front trunk latch sensor issue resulting in reduced
  sleep and increased overnight range loss.
- Addressed certain cases where Direct Current Fast Charger (DCFC) was slowed
  due to delayed battery cooling by up to 10 minutes.
- Addressed a rare DC-DC converter fault that resulted in limited performance
  and required a vehicle reset to clear.
- Fixed an occasional issue where changes to suspension settings were
  unavailable due to cold ambient temperatures.
- Improved compatibility with BC Hydro and Flo charging networks.
- Range estimation fixes
  - Fixed a frequent issue where range estimation was incorrectly higher in Tow
    Mode (Thanks for the video, Zack!).
  - Fixed a rare Issue where incorrect top o charge range was seen based on
    wheel configuration.
- New Power Outlet Timer: In the Energy app you can now set a timer in
  increments of 1 hour up to 8 hours, for when your power outlets will turn off.
  Auto turn of after 24 hours is still available.
- Gear Guard improvements
  - Reduced the number of extraneous videos by up to 30% by improving the
    accuracy of the Gear Guard video algorithms and handling of stationary
    objects, such as mailbox, traffic cone, sign board, fence, and adverse
    weather, such as rain and snow
  - Gear Guard video recordings will include footage recorded from all cameras
    before the triggering event was detected.
- Remote cabin preconditioning and heated surfaces improvements
  - New Vented Seat remote command when used with Rivian Mobile App 1.10 and
    later.
  - Addressed an Issue where sending cabin preconditioning and heated surfaces
    remote commands from the mobIlE app were not successful in close proximity
    to the vehicle.
  - Improved consistency when sending multiple heated surface commands at the
    same time from the mobile app.
  - Fixed an occasional issue where the defrost command was not functional.
- Window control improvements
  - Individual recalibration or reset of all windows can now be done from the
    driver side master switches. See R1 Owner Guide for recalibration or reset
    procedure.
  - Improved window close speed.
  - improved window object detection and reaction.
- Media improvements
  - Steering wheel buttons now handle seek differently for music and podcasts.
    - Music will move to next song
    - Podcasts will skip 15 seconds
  - Fixed the issue in Spotify where the artist's name was hidden on albums and
    playlists.
  - Fixed an intermittent issue where song progress goes to 00:00 after coming
    back from another media source.
  - Fixed an intermittent issue where Spotify did not load the content on
    initial load.
  - Fixed an intermittent issue where incorrect radio state displayed when
    resumed to radio from a phone call.
- Phone screen fixes
  - Fixed an intermittent issue where an incorrect phone number displayed on the
    flyout panel.
  - Fixed an intermittent issue where the selected contact card didn't display
    the correct phone number (more frequent after FaceTime calls)
- Fixed an issue where language switching did not work after infotainment reset.
- Addressed certain cases where Highway Assist was unavailable due to errors
  related to Global Navigation Satellite System corrections.
- Addressed an issue where Park Assist chimes were provided for select zones in
  the rear, while rear accessory mode was enabled.



## 2022.47.00 (6ab8b27e)

Initial public release: December 19, 2022

Source:
  [R1S](https://stories.rivian.com/r1s-software-update-2022-47-english),
  [R1T](https://stories.rivian.com/r1t-software-update-2022-47-english)

### New Snow Mode

This new on-road only mode enhances confidence and control on roads and
highways with snow, slush, or Ice. A relaxed response and reduced regenerative
braking allow tor more precise control on low-grip road surfaces. Also, the
vehicle otters improved performance when It slows to a stop. Go to **Drive
Modes**
<img src="./images/icons/drive-modes.png?raw=true" alt="drive modes icon" height="20px" />
**› Snow**.

**Note**: To go off road in snow, use the **Off-Road All-Terrain** mode

### New Address Sharing From Your Smartphone to the Vehicle

If you have the Rivian mobile app version 1.9 or later, you have two options:

- **Share a charger address from the Rivian mobile app:** Open the Charger Map.
  View the details for the charger you want, and then choose **Send to
  Vehicle**.
- **Share any address from Google Maps™ or Apple® Maps:** Search tor an address.
  Choose **Share** for the address you want, and then choose the Rivian mobile
  app from the list of options to share.

### New Vehicle Controls Support With the Rivian Mobile App

With the Rivian mobile app version 1.9 or later, you have remote cabin
preconditioning controls so you can remotely prepare the cabin climate for
travel in cold weather:

- Heat the front and second-row seats.
- Heat the steering wheel.
- Turn on defrost. (This option is available after you turned on the cabin
  climate from the Rivian mobile app.)

### New Tidal Music Source

TIDAL® is now available in the Media app. To use TIDAL, log into a **paid
account** when your vehicle is in Park and has cellular or Wi-Fi® connectivity.

**Note:** Music playback from a free account is currently not supported.

### New Song Queues

For Spotify® and TIDAL, you can add a song to a queue and view a song queue to
find out which songs will play next.

For Spotify, you can do the following to further customize your music listening
experience:

- Search or play a stand-alone song, and add it to the queue
  <img src="./images/icons/playlist.png?raw=true" alt="queue icon" height="20px" />
- Open an album, playlist, or audiobook, and add those tracks to the queue.

### New Audiobooks in Spotify

Audiobooks are now available for users with US-based Spotify Premium accounts.

### Independent Volume Controls

You can now set different volume levels for various audio sources, including
voice navigation, phone calls, media, and Alexa. Choose **Volume**
<img src="./images/icons/volume.png?raw=true" alt="drive modes icon" height="20px" />
at the bottom right of the center display to adjust the volume of the audio
source that is currently active. To access controls for the other audio
sources, choose the audio source button located above the volume control.

You can also use the left thumb control on the steering wheel to set the volume
of the audio source that is currently active.

### New Data and Privacy Controls

The Settings app now offers a new Data and Privacy tab to provide better
visibility and control over vehicle data that is shared and used. We've added
options to limit sharing of precise location data to support certain features
and services. We've also added options that allow you to enable your vehicle's
interior camera to support safety features. To review and confirm your data
privacy settings, go to **Settings**
<img src="./images/icons/settings.png?raw=true" alt="drive modes icon" height="20px" />
**› Data and Privacy**.

**Note:** If you limit sharing of precise location data, Highway Assist won't be
available.

### Additional Improvements

- Improved ride quality with updated suspension settings and refined the Drive
  Modes › Ride settings as follows:
  - Soft: Active dampening improvements to ride quality.
  - Stiff: Improved handling capabilities.
- Improved battery longevity, battery durability, and regenerative braking
  performance. Also enhanced regen availability, and you can use regen for
  longer durations.
  
  **Note:** Regen performance may be reduced at lower ambient temperatures.
- When Gear Guard video is disabled, overnight range loss can be reduced by up to
  20%.
- The vehicle can now sleep even if a door is left open.
- Improved responsiveness and reliability of key card taps and key fob button
  presses when the vehicle is asleep.
- In the Navigation app, you can now set your current location as your Home or
  Work location.
- Improved automatic humidity control to help keep the cabin more comfortable.
- Fixed an issue so the vehicle now reverts to Auto for the cabin climate after
  you choose Defrost or Defog.
- Fixed rare occurrences when a Gear Guard animation was displayed while you
  drove or charged the vehicle.
- Fixed an issue that allowed you to set proximity locking to Off at Home
  without a prompt to add a Home location.
- Improved stability of the infotainment system by fixing rare occurrences of
  restarts for the Phone app, FM radio, and center display.
- Fixed a rare issue when the center and driver displays flashed white during
  start-up.
- Addressed a rare issue when voice navigation unmuted itself.
- Fixed a rare issue in which Spotify didn't play your selection.
- Addressed an occasional issue when the Roomy entry and exit feature was
  disabled after the vehicle updated its software and then went to sleep.
- If your windows require calibration, the center display notifies you to reset
  the windows. Choose **Owner's Guide**
  <img src="./images/icons/book.png?raw=true" alt="drive modes icon" height="20px" />
  from the menu on the center display. Search for **Reset the Windows** and
  follow the instructions.
- Improved the SOS or emergency call feature to help prevent accidental calls
  by increasing the duration of the cancellation period on the center display
  from 10 to 20 seconds.
- **R1S:** Fixed an issue when the Power liftgate operation setting didn't
  persist during vehicle sleep and software updates.
- **R1S:** Fixed an issue when the third-row reading lights didn't turn off or
  dim after cabin lights were turned on from the center display.
- Fixed a rare issue when a password was required for an open Wi-Fi network.
- Addressed an issue that turned off Pet Comfort when you heated the steering
  wheel.
- Highway Assist improvement to more easily override automatic steering when
  you want to take over.
- Addressed a rare issue when Highway Assist disengaged during heavy traffic
  conditions with low visibility of lane markings.
- Improved Highway Assist availability on banked roads.
- Fixed a rare issue when after the vehicle displayed a warning that your hands
  were off of the wheel, it erroneously displayed a failure notification if you
  moved the steering wheel.



## 2022.43.02 (a733dedb)

Initial public release: November 29, 2022

Source:
  [R1S](https://stories.rivian.com/r1s-software-update-2022-43-02),
  [R1T](https://stories.rivian.com/r1t-software-update-2022-43-02)

### Roomy Entry and Exit

Roomy entry and exit allows the driver's seat and steering wheel to
automatically adjust between a preferred driving position and a preferred entry
or exit position, for easier access at the beginning and end of a drive. The
setting and the preferred entry and exit positions are saved to your specific
user profile. This feature is disabled by default.

To use Roomy entry and exit, choose **Settings**
<img src="./images/icons/settings.png?raw=true" alt="settings icon" height="20px" />
from the menu on the center display. Choose **Vehicle**, then choose
**Access**, and then follow the prompts on your screen.

**Note**: If your seat or steering wheel is not calibrated, the Roomy Entry &
Exit setting and automatic driving position adjustments will not be available.
Please contact Rivian Service to get the seat or steering wheel calibrated.

### Shift to Neutral Feature for Car Wash Mode

When Car Wash mode is enabled and the vehicle is not in neutral, a "Shift to
Neutral" button appears to allow for easier neutral access when moving forward
in a drive-through car wash. Press the brake pedal to allow the shift to Neutral.

_Thanks Dad for this idea and feedback_ - RJ

### Additional Improvements

- Kneel Vehicle feature setting is now tied to your user profile
  
  **Note**:  You may need to re-enable the Kneel Vehicle setting after updating
  to 2022.43.
- Improved passive entry and exit performance for specific types of cell phones
  (Pixel 5, Pixel 6, Pixel 6 Pro)
- Improved the automatic display brightness user interface to indicate the
  difference between the original baseline and a manual adjustment made by the
  user
- Improved EV trip planner experience to include more charger location coverage
  and reduce the trip planner calculation time
- Fixed a bug where some users saw range numbers based off the wrong tire
  configuration
- Fixed various rare issues related to the navigation experience, that include
  but are not limited to:
  -  Disappearing navigation cursor
  - Saved locations not able to be deleted
  - Disappearing "Recenter" button
  - App crashes
- When Pet Comfort mode is enabled, window control is automatically disabled for
  pet safety
- Fixed a regression with 2022.39.1 update that resulted in auxiliary air
  compressor failure on some vehicles
- Fixed an occasional issue with controlling media using left steering wheel
  buttons
- Fixed a very rare issue that caused the infotainment system to reset when
  playing FM radio
- Fixed some Spotify issues:
  - Stream moved from one source or device to the vehicle due to proximity
    unlock
  - Fixed an occasional issue where the incorrect media track appeared in the
    media panel
  - Fixed an occasional issue in which the same song name from a different album
    or artist was highlighted as playing
- Improved online route request behavior in poor connectivity conditions
- Fixed an occasional issue with the TuneIn screen not loading properly
- Fixed an occasional issues in which Alexa didn't understand some commands or
  appeared to be offline
- Fixed an issue in which the Gear Guard app didn't load correctly during fast
  app switching
- Fixed an issue in which Gear Guard didn't appear in the foreground after an
  alarm event
- Fixed the recent call history display, which showed an incorrect day of the
  week
- Fixed an issue where vehicle didn't automatically restart charging when charge
  limit was reached then modified via Rivian mobile app version 1.8 and above
- Introduced an improvement where a vehicle reset cannot be initiated when an
  SOS is in progress
- Improved the logic to reduce the occurrence of unnecessary Highway Assist
  driver takeover requests in response to short tunnels or overpasses
- Improved ability to engage Adaptive Cruise Control when Highway Assist is
  unavailable
- Decreased Adaptive Cruise Control and Highway Assist disengagements due to low
  traction situations
- Fixed a very rare issue with sleep that would cause the vehicle to deplete low
  voltage



## 2022.39.03 (f6db01d8)

Initial public release: October 28, 2022

(Same release notes as 2022.39.01. See below.)



## 2022.39.01 (2bf7f386)

Initial public release: October 25, 2022

Source:
  [R1S](https://stories.rivian.com/r1s-software-update-2022-39-03),
  [R1T](https://stories.rivian.com/r1t-software-update-2022-39-03)

### Easier Vehicle Access

The new feature, Kneel vehicle upon parking, enhances vehicle access. The
vehicle can lower itself when you shift into Park while it is at Standard ride
height and in All-Purpose or Conserve drive mode. The vehicle kneels regardless
of the Auto ride height button selection. Kneeling pauses when you open a door.

Choose **Settings**
<img src="./images/icons/settings.png?raw=true" alt="settings icon" height="20px" />
from the menu on the center display. Choose **Vehicle** and then choose
**Access**. Turn on **Kneel vehicle upon parking**.

**Notes**:

- The vehicle returns to the previous ride height when it travels above 5 mph
  (8 km/h).
- Some vehicles may need to be driven after the Software Update before Kneel
  vehicle upon parking can be enabled.

### Enhanced Radio User Interface

Choose **Media**
<img src="./images/icons/music.png?raw=true" alt="settings icon" height="20px" />
from the menu on the center display to use these new features:

- A control that turns the radio on or off from the FM Radio user interface.
- The ability to snap to a station through the tuner.
- A new icon to quickly access the keypad and search for stations.
- A grid layout that displays radio stations for easier access.
- The content title that displays on the audio panel for HD Radio.

### Automatic Screen Brightness

You can now set your screen brightness to automatically adjust to ambient
light. Choose **Vehicle**
<img src="./images/icons/vehicle.png?raw=true" alt="settings icon" height="20px" />
from the menu on the center display, and then choose **Lighting and Displays**.
In the Displays section, choose **Auto** next to the brightness slider.

When **Auto** is turned on, use the brightness slider to manually adjust the
brightness level with an offset relative to the ambient light. The brightness
level continues to automatically adjust, with your offset, until you turn off
**Auto**.

### Improved Gear Guard User Interface and Motion Detection

When you view an event in the Gear Guard app, the first video that plays is the
one whose camera first detected motion. The app displays a vehicle image
showing the different camera views available via thumbnails. Select a thumbnail
and the video automatically plays in the video player. Choose **Gear Guard**
<img src="./images/icons/guard.png?raw=true" alt="settings icon" height="20px" />
from the menu on the center display and then choose an event to view.

We've also improved the user experience as follows:

- We've reduced the number of extraneous videos by up to 50% by improving the
  accuracy of the Gear Guard video algorithms and handling of stationary
  objects, such as poles and trees.
- When you enter your vehicle, the Gear Guard app now appears on the center
  display only if the alarm was triggered.
- If the Gear Guard app detects motion and then records videos, the
  notifications appear in the notification panel on the center display.
- We've resolved rare cases in which the Gear Guard app didn't record videos.

### New Controls for the Rivian Mobile App

The Rivian mobile app version 1.8.0 or later enables new commands:

- Enable or disable video recording in the Gear Guard security system.
- Start and stop charging, as well as set a charge limit.

### Additional Improvements

- Improved Navigation app:
  - Allows you to find chargers more easily; the app uses pins that dynamically
    display more information at increasing levels of zoom.
  - Shows the estimated range and charge status at the time of arrival.
  - Provides a more accurate vehicle location shown at higher speeds.
  - Includes improved navigation during loss of cellular connectivity.
- Driver display improvements:
  - Provide better animation of pedestrians and cyclists.
  - Give a more accurate depiction of steering wheel rotation when the vehicle
    is turning.
  - Provide a new notification if speed is limited while the vehicle returns to
    a previous ride height.
- An improved AC charging rate at higher battery temperatures.
- Improved defog performance clears the windshield more quickly.
- Fixed an inaccurate cabin temperature displayed in the Rivian mobile app when
  the vehicle is asleep.
- Turning off rear climate also turns off airflow to the rear vents.
- **R1S**: A chime indicates that the liftgate won't open or close because the
  tailgate isn't closed.
- Addressed this issue: The Drive Modes app wouldn't respond to touch when you
  enabled the Rear accessory option and then chose Towing mode.
- Improved robustness and notifications for leveling in the Camping app.
- Resolved the issue of false notifications about the air compressor
  overheating.
- Addressed an occasional issue: Update Details did not display.
- For your privacy, the driver monitoring camera is turned off when Highway
  Assist isn't engaged.
- Better Adaptive Cruise Control in-lane and Highway Assist lane centering
  during highway driving.
- A chime that indicates Highway Assist isn't available is now louder so it's
  easier to hear.
- A new chime indicates immediate cancellation of Highway Assist.
- An increased delay before the vehicle shifts to Reverse or Neutral after
  Highway Assist or Adaptive Cruise Control ends. This prevents unintended
  shifts.
- On the weekend of tricks and treats,<br/>
  When the pale moon slowly rises,<br/>
  Look below the gear that can't be stowed,<br/>
  For a friend with a few surprises.

```
                                 ,*,,(,,@,,
                               %&((      (@//.                      @@ @@ #
                             .,             .,                     *#@. @*(@ @
                            .@    @       @   ,.              %&  @ @@@@@@@@#
                           ,&                  @@             .@,@@@ # @ & @@
                          ./*.                .,,&              (@@*@@@@@@@@@&
                          ,,(,@     \/\/\/    *,%,*,             @@@@@ @ @@@@@@
                         .*,,,,,@           @#,,.@,.           @@@@@ @ @@@@@@@
                        /,,,,*,,,,@@@@@@@@@,*,,,,,,,.       (@@@@@@ @(*@@@@@@@,
                        ,%,,,,%*,*,,,(%,,,%,*&#&@@@@@@@@@@@@@@@@@(,@* @@@@@@@@
                     @@@@@@@@@@@@@@@  .@@@@@@@@@@@@@@@@@@@@@@@ @  % @@@@@@@@@
                  &@@@@             @ @              @  /        @@@@@@@@@@@
                /@@@   @@@@@@@@@@@@@@ #@@@@@@@@@@@@@(  ,@@@@@@@@@@@@@@@@@@@
              @@@@@  @@@@@@@      @@@ .@         @@@@@@@@@@@@@@@@@@@@@@@@
            @@@@@  @@@,     #@@@@@@@@  @@@@@@@@@&   @@@@@@@@@@@@@@@@@@*
          @@@@@@ @@@@@@@@@@@      #@@  @@     .@@@@@@@@@@@@@@@@@(
        @@@@@&   @@@@@%     @@@@@@@@@  @@@@@@@@,    %@@@@@
       @@@@@ # @@@@@@@@@@@@@      %@@  @@@    *@@@@@@@@@@@
      &@@@@ @  @@@@@@@@@@   @@@@@@@@@ @@@@@@@@@     @@@@@@.
      @@@@ @/ @@@@@@@@@@@@@@      @@@ @@@@     /@@@@@@@@@@@
     @@@@@    @@@@@@@@@@@@@@@@@@@@@@@ @&@@@@@@@@@@@@@@@@@@,
     %@@    @@@@@@@@@@@@@@@@@@@@@@@    ,@@@@@@@@@@@@@@@@@@@
     ,@@ @ (@@@@@@*@@@@@@  @@   @@@@  /@@@@   @@@   @@@@@@@
      @ @ & @ (@@# @@@@@@   @@@(  @@ .@@  (@@@@@@   @@@@@@,
   @,  @@@@@@@@@   @@@@@@@@#    @  @&&@         (@@@@@@@@@@
  @,          ,@  @@@@@@@@@@@@@@@@@@@@@@@@@@@@@/@@@@@@@@@
  @@(@(%&,& %@(@@  @@@@@@      @@@@@@@@@@@@@     @@@@@@@@@
 #@(#(((((((@((((  .@@@@@@  #@@@@@@@@ ,@@@@@@   @@@@@@@@@@
@@(&((@#(((((((((,  @@@@@@  %@@@@@@@   @@@@@@   @@@@@@@@@%
.@(&(((((@@((#(((   @@@@@@  @@@@@@@@    @@@@@   @@@@@@@@.
  @(#((((@&((((#.    @@@@#   @@@@@@    *@@@@@   @@@@@@@,
         .          .@@@@*  .@@@@@     @@@@*&&   @@@@@
                     @@@@  (/@@@@@      @@@@@ @@ @@@@@*
                     @@@@  #,@@@@@       @@@@ @@ @@@@@@
                     @@@@   @@@@@@       @@@@(   @@ @#.
                    *  *@ @  @@ #@       @@@ @@ *@@  @@@
                  *@@@@@@@@@@@@@@*       *@@@@@@@@@@@@@*
```



## 2022.35.03 (f03aebd9)

Initial public release: September 30, 2022

<!-- Source:
  [R1S](https://stories.rivian.com/r1s-software-update-2022-35-03),
  [R1T](https://stories.rivian.com/r1t-software-update-2022-35-03) -->

### Remote Cabin Preconditioning Temperature Adjustment

With the Rivian mobile app 1.7, you will be able to use the mobile app to adjust
the remote cabin preconditioning temperature. This allows you to select the
desired cabin temperature for when you return to your vehicle.

### New Rear accessory Setting

When you have accessories installed on the rear tow hitch, you can now hide rear
visual alerts and mute audio warnings while in reverse. To enable this feature,
choose **Settings**
<img src="./images/icons/settings.png?raw=true" alt="settings icon" height="20px" />
from the menu on the center display, and then choose **Vehicle**. Choose
**Driver+** and turn on **Rear accessory**.

### Driver+ Settings Are Now Persistent

Your Driver+ settings for Adaptive Cruise Control (ACC) / Highway Assist (HWA)
distance, Forward Collision Warning Proximity settings, Lane Keeping Assist,
Blind Spot Warning, Park Assist Audio Warnings, and Rear Cross-Traffic Warning
will now persist across software updates and drive cycles.

**Note**: The Driver+ settings for Rear Cross-Traffic Warning, Park Assist Audio
Warnings will default to factory settings after this software update, and after
that will persist for future software updates.

### Additional Improvements

- Improvements to Infotainment System:
  - Overall system stability, responsiveness, performance
  - Redesigned Drivers and Keys, Driver+, and Exterior Lighting settings menus
  - Simplified the media panel behavior and made it easier to mark your
    favorite songs on Spotify and TuneIn
  - Alexa can now be canceled mid-command; say "Alexa, stop" or tap the blue
    activity bar at any time to immediately end your interaction with Alexa
  - Improvements to various screen animations
- Fixed rare issue where the navigation application would reset
- Fixed very rare occurrence of infotainment screen resets
- Improved FM Radio stability and addressed occasional issues where the radio
  would not play or would experience intermittent drops in audio
- Addressed occasional Alexa internet connectivity and echo cancellation issues
- Addressed occasional issues with Wi-Fi hotspot availability
- **R1T**: Addressed an occasional issue with the driver's side gear tunnel door
  not opening upon first request from gear tunnel release button on the bed rail
- Passenger-side cabin comfort settings now synchronizes to driver's settings
  when a passenger is not present
- Reduced fan cooling noise and duration after Direct Current Fast Charger
  (DCFC) charge sessions in moderate ambient temperature
- Reduced fan cooling noise when you approach the vehicle with passive entry,
  or manually unlock with key fob, and cabin comfort starts up
- Addressed an occasional issue where the posted speed limit on the driver's
  display is shown in kph (kilometers per hour) instead of mph (miles per hour)
- Park Assist warnings in Drive will now trigger earlier for obstacles in the
  front
- Improved Highway Assist (HWA) lane centering
- Fixed an occasional issue where Adaptive Cruise Control (ACC) was not
  available after a Highway Assist (HWA) disengagement



## 2022.31.05 (00ee7394)

Initial public release: September 2, 2022

Source:
  [R1S](https://stories.rivian.com/r1s-software-update-2022-31-05),
  [R1T](https://stories.rivian.com/r1t-software-update-2022-31-05)

### New Camping App Available

For your convenience, you can now do the following:

- Energy use: To optimize your camping experience inside or outside the vehicle,
  choose your vehicle's energy use: Stay Off, Normal, or Stay On.
- Outlets: 120 V, 12 V, USB-C, and the wireless charging pad stay on. The
  outlets can stay on for a maximum of 24 hours, with the option to choose a
  shorter duration.
- Camp courtesy: You can turn off exterior lights, vehicle sounds, proximity
  locking or unlocking, and the Gear Guard alarm sound. This also enables quiet
  cooling or heating.
- Displays: You can turn off the driver, center, and rear displays.
- Flood lights: You can turn on the flood lights, which are located near the
  side mirrors.
- Vehicle leveling: You can level the vehicle when parked on uneven terrain.

Camping controls, except for the outlets, are available only when the vehicle is
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
the panic alarm. (If the new controls don't automatically appear in the Rivian
mobile app, we recommend that you restart the app.)

### Additional Improvements

- Reduced noise from cabin climate upon vehicle startup.
- Reduced the offset of the speedometer display. It now indicates no more than
  1-2 mph over the actual vehicle speed.
- Introduced new algorithms for improved proximity unlocking speed and
  consistency.
- Updated user profile functionality:
  - Improved user profile detection in case there are multiple users.
  - In addition to the phone key, unlocking the vehicle with a key fob, key
    card, or key band now loads the profile associated with that key.
  - Fixed an occasional issue: Side mirrors don't move into the profile
    position when the vehicle unlocks via proximity unlocking.
- Updated behavior: Use of a key fob or key card now loads the profile assigned
  to that key fob or key card.
- Addressed issues when opening the front trunk may require pressing the button
  twice if the vehicle is asleep.
- Displays now can't be accessed if the Gear Guard alarm is triggered.
- Reduced battery drain while the vehicle is parked by an average of 10%.
- Improvements to vehicle sleep behavior:
  - Rear occupancy detection: Heavy objects left in the rear seats won't
    prevent vehicle sleep.
  - Outlets that are turned on in the Energy app automatically turn off after
    24 hours; then the vehicle can sleep.
- Addressed the slow display of range on the driver display when the vehicle
  wakes.
- Fixed garage door opener interoperability issues with LiftMaster 8500/8500W,
  CSW24UL, and Jackshaft openers.
- Addressed issues when the FM Radio would freeze or restart.
- Increased security of TuneIn integration: This may clear the Favorites and
  Recents of users who didn't sign into TuneIn.
- Fixed an occasional issue: Alexa doesn't wake up or respond to voice commands.
- Fixed an occasional issue: The audio volume changes when the vehicle wakes.
- Fixed an occasional issue in the Navigation app: The vehicle now retains the
  satellite view while it sleeps.
- Fixed a rare issue: The trip planner within the Navigation app is offline
  even though the network status indicates it is connected.
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


## 2021.45.01

(Shipped with earliest vehicles; Details unknown)
