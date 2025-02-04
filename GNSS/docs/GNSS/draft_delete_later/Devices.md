# GNSS Devices for Training

## EOS

Mobile internet connection required.

### Antenna

### EOS Gold (RTK GNSS receiver )

https://eos-gnss.com/products/hardware/arrow-gold

* 1 cm accuracy with RTK
* 10-15 cm accuracy with Galileo HAS
* 4 cm accuracy worldwide w/ Atlas® subscription
* Retain RTK in poor cell areas with SafeRTK®
* Access all GNSS constellations and signals
* Easily integrate with any mobile app
* Compatible with all mobile devices

### EOS Tools Pro  (Software)

https://eos-gnss.com/products/software/eos-tools-pro

* Mobile workers monitor GNSS metadata in real time.
* Facilitates connections to RTK networks and base stations via its built-in NTRIP client.
* Configurable alarms and real-time GEOID height conversions.
* EOS Tools Pro does not collect data. We will use ArcGIS Field Maps for data collection.



## Leica

### Zeno GG04 plus Smart Antenna

Precise point positioning (PPP)

- Achieve high accuracy data collection without a mobile data connection
- Available anywhere in the world, anytime
- Removes reliance on post-processing

### Zeno Mobile (Software)

* Mobile data collection app. Use with GNSS receiver such as  GG04 Plus and FLX100.
* Capture point, line, and polygon data with centimeter accuracy.

### Zeno Connect (Software)

* Configure your Leica receiver and use real-time connection source.
* Collect with third-party mapping apps such as ArcGIS Field Maps.

# NPS Common Workflow

Rule of thumbs

* There is no need for post-processing kinematics when real-time correction is available.
* Collect raw data when real-time correction is unavailable in the field for post processing the data after getting back to the office.
* Use Leica SmartLink Precise Point Positioning (PPP) when internet connection is unavailable or unreliable but require real-time and high accuracy data collection is required.
* Post-processing for mobile data collection for the accuracy.



Questions:

When to use 

* EOS arrow or 
* Leica GG04 Plus + Zeno Mobile
* Leica GG04 Plus + Zeno Connect
* [High Accuracy GPS , leica gg04 plus, Field Maps on Android. Altitude is incorrect](https://community.esri.com/t5/arcgis-field-maps-questions/high-accuracy-gps-leica-gg04-plus-field-maps-on/m-p/1291805#M6094)



# Precise Point Positioning (PPP) Services with EOS Arrow
* Galileo High Accuracy Service (HAS)
  * Initial Service on the 24th of January 2023
  * Global coverage (Service Level 1 (SL1)) -  typical convergence time of less than 300 seconds (5 minutes)
  * Regional coverage availability over the European Coverage Area (ECA) (Service Level 2 (SL2)) - convergence time will be lower than 100 seconds
  * Free of charge
  * Real-time corrections
  * Accuracy target (95%): 20cm (horizontal) / 40cm (vertical)
  * E6-B signal
  * Internet not required
  [EOS Positioning](https://eos-gnss.com/blog/galileo-high-accuracy-service-early-observations)
  Note: [Galileo HAS Internet Data Distribution](https://www.gsc-europa.eu/galileo/services/galileo-high-accuracy-service-has/internet-data-distribution) service also available.
  [FAQs on HAS](https://www.gsc-europa.eu/galileo/faq#HAS)  

[Have you met HAS? 22 Jan 2024](https://www.euspa.europa.eu/newsroom-events/news/have-you-met-has#:~:text=While%20SL1%20will%20have%20a,be%20lower%20than%20100%20seconds.)
[PPP Galileo HAS Technology: Pros and Cons](https://gpsgeometer.com/en/blog/pros-and-cons-of-ppp-galileo-has)

### Precise Point Positioning (PPP) Services with Leica SmartLink
* Subscription-based
* Correction based argumentation satellites
[SmartLink](https://leica-geosystems.com/en-us/products/gnss-systems/smart-antennas/leica-viva-gs16/life-beyond-traditional-rtk-satellite-based-precise-point-positioning)
