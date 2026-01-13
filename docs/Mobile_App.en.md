![Logo](./assets/logo2.png "Logo")

# Welcome to Yacht On Cloud user guide.

## Login
To perform the log-in, it is mandatory to enter the following fields in the forms: 

* `Tenant`: Identification name of the specific enabled tenant.
* `Email`: Your e-mail address, which represents the user's unique key.
* `Password`: Your password.

<div style="margin-top: 30px;">
    <img src="../../assets/login_screen.png" alt="Login Screen" width="250">
</div>

After filling in the fields, you can click on the `Log In` button.

In case of incorrect credentials, the user will be informed with an error message.

If the credentials are correct, the user will proceed to the next screen.

### Reset Password
To reset your password, it is mandatory to enter the following fields in the forms: 

* `Tenant`: Identification name of the specific enabled tenant.
* `Email`: Your e-mail address, which represents the user's unique key.

<div style="margin-top: 30px;">
    <img src="../../assets/reset_password_screen.png" alt="Reset Password Screen" width="250">
</div>

An email will be sent to the address provided to perform the reset. 

## Vessel Selection

On this screen, the user will be able to view their `Vessels` registered within the system.

If only one vessel is present for a specific customer, it will be automatically selected immediately after the login screen. If multiple customers/vessels are available, the user can scroll through them and select the desired vessel.

<div style="text-align: center; margin-top:30px;">
    <img src="../../../assets/select_vessel1.png" alt="Vessel Screen" width="250">
    <img src="../../../assets/select_vessel2.png" alt="Vessel Screen 2" width="250" style="display: inline-block; margin-left: 30px;">
</div>

The color of the icon, `green` or `gray`, will indicate an online (reachable) or offline (unreachable) vessel, respectively. 

## Vessel Dashboard

<div style="margin-bottom: 30px;"></div>

<div>
    <img src="../../assets/home_page.png" alt="Home Screen" width="250">
</div>

<div style="margin-bottom: 30px;"></div>

### Status Indicators and Information Fields
*Online/Offline*: Text and color indicator (green dot) signaling the yacht's connection status to the cloud.

*Yacht Name*: Field displaying the name of the currently selected vessel (e.g., "I AM").

*Background Map*: Cartographic display showing the real-time GPS position of the yacht.

*Sensor/Device Tiles*: Grid of colored boxes showing the device name (e.g., Door1, Smoke1), the current status (Open/Closed, OK, lux), and an identification icon. Colors indicate the alert status (Green for OK/Closed, Red for Open/Alarm).

### Actions and Controls
*Category Filters* (Action, Other, Environment, etc.): Buttons located at the top to filter the view of IoT devices based on their function.

*Side Quick Actions*:

- Anchor Icon: Activation/deactivation of the anchor alarm.

- Lock Icon: Command for centralized locking or unlocking of access points.

*Edit*: Button with a pencil icon to customize the arrangement or selection of tiles on the dashboard.

*Bottom Navigation Bar*:

- Home (House Icon): Return to the main dashboard.

- Notifications (Bell Icon): Access to the history of alerts and alarms.

- Map (Open Map Icon): Full-screen view of the cartography.

- Geofencing (Placeholder Icon): Access to geographical security perimeter settings.

- Settings (Gear Icon): Access to profile and app configuration.

### Edit Mode

<div style="margin-bottom: 30px;"></div>

<div>
    <img src="../../assets/home_page_edit_mode.png" alt="Home Screen" width="250">
</div>

<div style="margin-bottom: 30px;"></div>

#### Fields and Indicators
*Device Tiles*: Each box displays the sensor name, icon, and current status.

*Selection Check*: In this mode, each tile features a circular checkmark in the top right. If the check is selected, the device will remain visible on the dashboard; by deselecting it, the device will be removed from the main view.

#### Actions and Controls
*Drag & Drop*: The user can reorder devices on the grid by dragging tiles to the desired position.

*Selection/Deselection*: By clicking on a tile, the user decides whether to include or exclude that sensor from their personalized dashboard.

*Add All*: Command to simultaneously add all available devices to the dashboard.

*Add Device*: Button to access the selection of individual IoT devices to be monitored.

*Apply*: Button to definitively confirm changes to the order and selection (inclusion/removal) of devices.

#### Adding and Configuring Devices
A scrollable list showing all available sensors (e.g., Door, TriSensor, Smoke) identified by an icon and name.
For devices that monitor multiple parameters, a submenu is displayed listing the specific measurements available.

<div style="text-align: center; margin-top:30px;">
    <img src="../../assets/add_device1.png" alt="Vessel Screen" width="250">
    <img src="../../assets/add_device2.png" alt="Vessel Screen 2" width="250" style="display: inline-block; margin-left: 30px;">
</div>

**Actions and Controls**

- *Device Selection*: The user can scroll through the list and select the sensor to be added to the Dashboard.

- *Submenu Expansion*: By clicking on a multi-value device (indicated by an arrow next to the name), the user can expand the details list to choose which specific value to display in the Dashboard tile.

- *Close (X)*: Button in the top right to close the selection panel and return to the previous editing mode.

- *Confirm Selection*: The arrow icon at the bottom right allows proceeding with the insertion of the chosen parameter.

## Device Details

This section describes the detail screen of a single device, which provides in-depth information on its status and event history.

**Fields and Information Indicators**

- *Yacht Connection Status*: The "Online" status of the vessel is indicated at the top left with the relative color indicator.

- *Yacht Name*: Identifies the vessel on which the sensor is installed (e.g., "I AM").

- *Device Category*: Indicates the type of category the sensor belongs to (e.g., "Security").

- *Device Name and ID*: Displays the name assigned to the sensor (e.g., "Door1").

- *Current Status*: Shows the real-time condition of the sensor (e.g., "Closed" or "Open") accompanied by an icon indicating its power or connection status.

- *Latest Update (Latest)*: Indicates the date and time of the last reading received from the sensor (e.g., "14.11.2025 13:43").

- *Last Alarm*: Specifies the date and time of the last recorded alarm event (e.g., "14.11.2025 13:09").

**Actions and Controls**

- *Back Button (Arrow)*: Located at the top left, it allows returning to the main Dashboard.

- *Historic*: Selectable section that grants access to the full history of states and events recorded by the device over time.

- *Click on details*: Allows opening the section for the complete history of states and events recorded by the device over time.

### 1. Door

The *Door* screen is used to monitor the status of the doors, whether they are open or closed.

`Green` indicates the door is closed, `Red` indicates the door is open.

<div style="margin-top:30px;">
    <img src="../../assets/door_page.png" alt="Door Screen" width ="250">
</div>

### 2. Tri-Sensor

The *Tri-Sensor* screen is used to monitor 3 sensors: `Motion Sensor`, `Temperature`, and `Illuminance`.

<div style="margin-top:30px;">
    <img src="../../assets/trisensor_page.png" alt="Trisensor Screen" width ="250">
</div>

* **Motion Sensor** = Detects movements within a range of action.
* **Temperature** = Measures the vessel's temperature.
* **Illuminance** = Measures the amount of *Light* present.

### 3. Smoke

The *Smoke* screen is used to detect the presence of smoke. 

As with the *Door*, the colors are the same; therefore, `Green` indicates no smoke is present, and `Red` indicates the presence of smoke. 

<div style="margin-top:30px;">
    <img src="../../assets/smoke_page.png" alt="Smoke Screen" width ="250">
</div>

### 4. Actuator

*Actuators* allow controlling the status of the lights inside the vessel.

The switches indicate whether the light is off or not, based on the active/inactive color.

By operating the switch, it will change color and the lights inside the vessel will behave accordingly.

The `ON` and `OFF` value indicated under the *Line* labels is an additional notice of the current status of the lights.

### 5. Siren

The *Siren* screen allows monitoring the status of the siren, whether it is sounding or not.

Here too, the colors are the same as for the door. 

<div style="margin-top:30px;">
    <img src="../../assets/siren_page.png" alt="Siren Screen" width ="250">
</div>

### 6. Engine

The *Engine* screen allows monitoring the values related to the vessel's engine.

<div style="margin-top: 30px;">
    <img src="../../assets/engine_page.png" alt="Engine1" width="250" style="display: inline-block;">
</div>

Inside, several values are present:

* `Fuel Rate`: Allows monitoring the fuel consumption rate.
* `Total Hours`: Allows monitoring the engine operating hours.
* `Load`: Allows monitoring the engine load. 
* `Oil Pressure`: Allows monitoring oil pressure. 
* `Engine Speed`: Allows monitoring speed indicated in **RPM**.
* `Throttle`: Allows monitoring the percentage of acceleration requested by the driver.

### 7. Navigation Page

The *Navigation* screen allows monitoring all data regarding navigation.

As with Engine, several values are available here: 

* `Latitude`: Allows viewing the latitude.
* `Longitude`: Allows viewing the longitude.
* `Depth`: Allows monitoring the depth level.
* `Heading`: Allows viewing the direction of the vessel's bow.
* `Rudder`: Allows monitoring the ratio between speed and rudder angle. 
* `Speed over the Ground`: Allows monitoring the vessel's speed relative to the earth's surface.

### 8. Meteo Page

The *Meteo* screen allows monitoring atmospheric conditions according to nautical data.

Various values are available here as well: 

* `Wind Direction`: Allows monitoring the direction from which the wind blows.
* `Wind Speed`: Allows monitoring the average wind speed.
* `Outside Temperature`: Allows monitoring the correct outside temperature.
* `Outside Humidity`: Allows monitoring the correct outside humidity.
* `Atmosphere Pressure`: Allows monitoring atmospheric pressure.

### 9. Battery Page

The *Battery* screen allows real-time monitoring of the engine battery values.

### 10. History

The *History* section allows viewing the historical `telemetry` data of a device. 

### Common Fields and Indicators

- *Metric/Sensor Name*: Title at the top left identifying the monitored data (e.g., fuelRate or Door1).

- *Time Interval*: Indicates the period analyzed via start (from) and end (to) dates.

- *Sampling Note*: Bottom caption specifying the density of the data shown (e.g., "Only the last 24 values shown").

<div style="text-align:center; margin-top: 30px;">
    <img src="../../assets/history_page1.png" alt="Graph 1" width="250" style="display: inline-block;">
    <img src="../../assets/history_page2.png" alt="Graph 2" width="250" style="display: inline-block; margin-left: 70px;">
</div>

### Linear Chart (Continuous Data)

Used for numerical parameters that vary over time, such as fuel consumption (fuelRate).

Dynamic Trend: A continuous line shows the fluctuations of the value.

Scale Values: The vertical axis reports the specific minimum and maximum values recorded in the period (e.g., from 33.8 lt/h to 41.9 lt/h).

### Point Chart (Discrete States/Events)

Used for binary or state sensors, such as door sensors (Door).

Event Detection: The graph shows isolated points corresponding to each state change or detection made.

State Axis: The vertical axis indicates the state or number of events, while the horizontal axis reports the specific dates of occurrences.

The final representation is shown when there is no telemetry in the last 7 days. 

### Actions and Controls

- *Edit (Calendar Icon)*: Allows modifying the time interval to consult historical data from different periods.

- *Close (X)*: Button in the top right to close the history popup and return to the detail screen.

Above the graph or the message warning that no recent data was found, there is information regarding the device, the range of days for data retrieval, and the aggregation time. *These are default values.*

By clicking the *History Filter* button in the top right, it is also possible to set filters for better data visualization management. 

It is possible to decide the range of days and filter data for that range; by default, the aggregation mode will be *DAILY*. 

By checking the *Advanced Mode* box, advanced filters will be available. 

In this way, we can modify certain data including: Retrieved Data, Aggregation Time, and Aggregation Function. 

Various types of aggregation functions exist:

* **AVG**
* **MAX**
* **MIN**
* **COUNT**
* **SUM**

Additionally, where possible (in case of multiple values in a single device), you can also choose which telemetry you want to analyze.

## Alarms Dashboard

Within the `Main Menu`, by clicking on the appropriate icon (depicted by an **alarm clock**), you can view a list of the latest triggered alarms.

From the dashboard, we can see which device triggered an alarm, indicating the date and time. 

<div style="margin-top:30px;">
    <img src="../../assets/alarm_screen.png" alt="Alarm Screen" width ="200">
</div>

By clicking on the alarm, it is possible to view the responsible device for details.

### 1. Alarm Notifications

Upon receiving an alarm, the user will be informed via a notification on their mobile device.

The notification will present the following information: 

* Device category: Safety, Security, Anchor.
* Device Name. 
* Date and time.

While the app is open, a pop-up notification with alarm information will be shown.

The modal will contain two `buttons`, one to access the detail of the sensor connected to the alarm event and a button that allows arming or disarming.

Based on the type of error, the modal will have different functionalities. 

If the alarm event is a specific sensor, there will be the possibility to access the detail of the sensor connected to the alarm and a button to arm or disarm.

If the alarm event concerns the GPS, the option to access the tracking page will appear. 

In the case of a `Security` alarm, the option to perform armor unlocking will also appear; similarly, in the case of an `Anchor` type alarm, the button to deactivate the anchor will appear. 

## Tracking

Within the `Main Menu`, by clicking on the appropriate icon (depicted by a **Map**), it is possible to activate real-time tracking of your vessel and weather information.

<div style="text-align:center; margin-top: 30px;">
    <img src="../../assets/tracking_page1.png" alt="Map" width="250" style="display: inline-block;">
    <img src="../../assets/tracking_page2.png" alt="Map2" width="250" style="display: inline-block; margin-left: 70px;">
</div>

By clicking on your vessel's icon, it will be possible to view data such as the Latitude and Longitude of the vessel's current location.

In this section, we have several functionalities, all corresponding to a specific button, which we will describe in detail.

### 1. Virtual Anchor

By clicking the *Virtual Anchor* button, it is possible to activate the virtual anchor. A legend illustrating its operation is also available on the relative screen.

<div style="margin-top: 30px;">
    <img src="../../assets/virtual_anchor.png" alt="Virtual Anchor1" width="250" style="display: inline-block;">
</div>

If active, it creates a circle around the vessel; when the vessel moves further than the selected radius from the circle, an alarm will trigger.

### 2. Tracking History

By clicking the *Tracking History* button, it is possible to view the vessel's movements on a specific day selectable from a calendar.

### 3. Layer

By clicking the *Layer* button, it is possible to select the level of information to display on the map. The available layers are:

* `Default`: Standard map view.
* `Wind Speed`: Real-time wind speed.
* `Wind Symbol`: Wind direction and intensity represented by symbols.
* `Temperature`: Air temperature.
* `Sea Surface Temperature`: Sea surface temperature.
* `Visibility`: Estimated visibility level.
* `Mean Wave Direction`: Mean wave direction.
* `Significant Wave Height`: Significant wave height.
* `Wind Waves`: Height of waves generated by wind.
* `Wind Wave Directions`: Direction of waves generated by wind.

<div>
    <img src="../../assets/layer.png" alt="Layer1" width="220" style="display: inline-block;">
</div>

At the bottom of the screen, there are two other buttons, also related to layers:

1 - Date: Allows selecting a specific date to view information related to the chosen layer.

2 - Info: Allows opening a legend that helps correctly interpret the different layers.

### 4. Meteo (Weather)

This section contains all information regarding hourly weather conditions and marine details from the [DTN](https://devportal.dtn.com/catalog) service.

Below is a list of all data that can be found in the details:

* `Hourly Forecast`: Presented as a horizontally scrollable widget and indicates the day's weather forecast.
* `Sea Surface Temperature`: Temperature of the sea surface.
* `Air Pressure`: Atmospheric pressure.
* `Wind Speed`: Wind speed measured in km. 
* `Wind Direction`: Wind direction measured in degrees.
* `Visibility`: Visibility rate measured in km. 
* `Wave Height`: Measurement of wave size.
* `Wave Direction`: Wave direction measured in degrees.
* `Total Swell Wave Direction`: Total direction of wave motion measured in degrees.
* `Total Swell Wave Height`: Total height of wave motion.

### 5. Ports

By clicking the Ports button, it is possible to view the ports closest to the vessel. By selecting a specific port, the following information data is shown, if available: `name`, `radio channel`, `coordinates`, and `port authority phone number`.

<div style="text-align:center; margin-top: 30px;">
    <img src="../../assets/port1.png" alt="Port" width="250" style="display: inline-block;">
    <img src="../../assets/port2.png" alt="Port Details" width="250" style="display: inline-block; margin-left: 70px;">
</div>

## Settings
The last button in the `Main Menu`, represented by the **Gear** icon, is for *Settings*.

<div style="margin-top:30px;">
    <img src="../../assets/settings.png" alt="Settings" width ="250">
</div>

Once the button is clicked, a menu will open.

On this page, the user will have access to various options regarding the application settings. 

### 1. Profile Page

On this page, the user can view their information such as `tenant`, `customer`, `username`, `email`, `first name`, and `last name` of the account.

<div style="margin-top: 30px;">
    <img src="../../assets/profile_page.png" alt="Profile Page" width="250" style="display: inline-block;">
</div>

It is possible to modify the profile picture by clicking the appropriate button. A menu will open allowing you to select a photo from the device's archive or take a new one.

### 2. Settings Page

On this page, the user can view all app settings: vibration, ringtone.

<div style="margin-top:30px;">
    <img src="../../assets/settings_notification.png" alt="Settings" width ="250">
</div>

### 3. Change Pin

By clicking *Change Pin*, the screen will open where it will be possible to change the pin for arming and disarming the vessel.

Initially, a *default* pin is provided, which it is recommended to change as soon as possible and create a personalized one for greater security.

<div style="text-align:center; margin-top:30px;">
    <img src="../../assets/change_pin.png" alt="Change Pin" width ="250">
</div>

### 4. Change Password for Wi-Fi

By clicking *Change Password for Wi-Fi*, the dedicated screen opens from which it is possible to modify the password of the pixora-edge device's Wi-Fi network, used for internet connection.

<div style="text-align:center; margin-top:30px;">
    <img src="../../assets/change_wifi_password.png" alt="Change Wi-Fi" width ="250">
</div>

### 5. Change Boat

By clicking the *Change Boat* button, you will be taken back to the section where you can select another vessel from those you own.

### 6. Logout

By clicking Logout, the user will be taken back to the Login screen where they can re-enter their access credentials. 

## TLC

Within the `Dashboard`, it is possible, by clicking on the appropriate TLC device, to view a list of all your cameras.

<div style="margin-top:30px;">
    <img src="../../assets/tlc1.png" alt="Telecamere" width ="250">
</div>

What the user will see on this screen will be the latest `Snapshot` taken by each camera.

By clicking on one of the available cameras, you will be redirected to the detail screen of that specific camera.

<div style="margin-top:30px;">
    <img src="../../assets/tlc2.png" alt="Sigle TLC" width ="250">
</div>

The screen will feature a `live` video of the selected camera, with the option to activate *Fullscreen* by clicking the button on the right, or to *Pause* and then resume from the current moment.

Below the live feed, via a calendar, it is possible to check all recordings captured by the alarms triggered for that specific date. *The calendar will be horizontally scrollable to change the selection month.*

The selectable days on the calendar will have different colors: 

* `Light Blue`: Current day.
* `Red`: Day on which recordings are present.
* `Gray`: Day on which no recordings are present.

By clicking on a day where an `event` is present, a list of alarms corresponding to the implicated device will appear. By clicking on the event, the `Playback` of the recording for the current TLC stream channel begins. 

In this way, the green highlighted ***Live*** text at the top right will be replaced by yellow highlighted ***VOD***, to indicate that the video is no longer live but is a recording.