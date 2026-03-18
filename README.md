# NissanConnect for Home Assistant for Nissan Townstar EV (by ME and AI)

An unofficial integration for interacting with NissanConnect vehicles in Europe. Based on the work of [mitchellrj](https://github.com/mitchellrj/kamereon-python) and [tobiaswk](https://github.com/Tobiaswk/dartnissanconnect). I have no affiliation with Nissan besides owning one of their cars.

_Please note this integration is only for vehicles using the NissanConnect Services app, not NissanConnect EV or any other app._

## Tested Vehicles
This integration has been tested with the following vehicles:
* Nissan Townstar EV 2024

## Supported Regions
* Europe

## Installation
### HACS

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=dan-r&repository=HomeAssistant-NissanConnect&category=integration)

This is the recommended installation method.
1. Search for and install the **NissanConnect [EU]** integration from HACS
2. Restart Home Assistant
**3. uploud(replace file) kamereon.py**

### Manual
1. Download the [latest release](https://github.com/dan-r/HomeAssistant-NissanConnect/releases)
2. Copy the contents of `custom_components` into the `<config directory>/custom_components` directory of your Home Assistant installation
3. Restart Home Assistant

## Setup
From the Home Assistant Integrations page, search for and add the Nissan Connect integration.

## Entities
This integration exposes the following entities. Please note that entities will only be shown if the functionality is supported by your car.

* Binary Sensors
    * Car Plugged In (EV Only)
    * Car Charging (EV Only)
* Sensors
    * Battery Level
    * Charge Time
    * Internal Temperature
    * Range (EV Only)
    * Odometer
    * Daily Distance
    * Climate
* Buttons
    * Update Data
    * Start Charge
    * Climate
