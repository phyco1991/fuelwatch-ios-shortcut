# fuelwatch-ios-shortcut
iOS Shortcut for FuelWatch (Western Australia) Petrol Prices

Compatible with iOS 26 (and potentially earlier builds)

## Setup and Usage

1. First you need to import the shortcut file onto your iOS device - in doing so it may ask you to grant permissions for location access and access to mapping applications.

2. You will need to set your preferred fuel type from the options available. Due to the way iOS shortcuts work, I could not provide these as a selectable menu. You must type them exactly as shown, or the shortcut won't work. You will also need to choose your preferred maps application (i.e. Apple Maps, Google Maps, Waze).

3. Ask Siri "Get Petrol Prices" - it will prompt you to choose from 'today' or 'tomorrow'. Once you've provided your answer it will read the 3 cheapest prices for your preferred fuel type in your location. After this, it will ask if you would like to get directions to the cheapest. If you say 'yes' it will load your preferred maps application with directions to the station.

## How does it work?

Quite simply, it uses a linked generated from your preferred fuel type, location, and chosen day to access the FuelWatch RSS Feed/API (https://www.fuelwatch.wa.gov.au/tools/rss). There is a bit of logic to sort the responses by cheapest price and then to output the three top results.

## Disclaimer

This is an unofficial iOS shortcut created by me (phyco1991). It is not supported by FuelWatch in any way, and is subject to breaking if they change their API in future.