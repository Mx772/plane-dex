# Plane-Dex
Like a poke-dex for airplanes using your ADSB server!

## Description

This is a fun little project that hooks up dirkhh's [adsb-feeder-image](https://github.com/dirkhh/adsb-feeder-image) using port 30152's rest API. 

## Setup

TODO

## Examples

### Unique Aircraft Collection Page:
![image](https://github.com/user-attachments/assets/10e81dbf-9843-4159-b5c1-53e648c1d8a5)

This page returns the first time your reciever spotted a specific aircraft type. (For example, Boeing 737 Max 8)

### New Aircraft Spotted:

![image](https://github.com/user-attachments/assets/311a408f-3820-4653-ac7f-adf112ac81d5)

When a new aircraft is spotted by the server. The next visit to the webpage will display the new aircraft in a grid like so.

### Rare Aircraft:

![image](https://github.com/user-attachments/assets/b3aab940-80f0-4018-838d-0e789b3d54b9)

This page displays all 'rare' aircraft, noted by PlaneFence's [Alert List](https://planefence.com/plane-alert/alertlist.txt).

Usually a combination of 'As seen on TV', 'Military', and unique aircraft.

### Stats page

![image](https://github.com/user-attachments/assets/f250a5f7-0cb2-4a39-8cf1-72af36a00719)

Shows filter/sorted stats for EVERY aircraft your reciever has spotted.



Note: All images are work-in-progress and not final. 


## Other Projects Used:

- PlaneSpotter's API
- [ADSB-Feeder-Image](https://github.com/dirkhh/adsb-feeder-image)
- [Planefence](https://github.com/sdr-enthusiasts/docker-planefence)
