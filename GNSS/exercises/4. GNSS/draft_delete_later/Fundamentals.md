# Global Navigation Satellite System (GNSS)

# GPS vs GNSS

GPS (Global Positioning System) and GNSS (Global Navigation Satellite System) are both satellite-based navigation systems, but they have some differences.


![GPS vs GNSS](../../assets/images/gnss/gps_vs_gnss.png)<br>
*Image: GPS vs GNSS [^1]*

### GPS:
* Developed and maintained by the United States.
* Consists of a constellation of at least 31 satellites.[^2]
* Provides global coverage.
* Primarily used for navigation, mapping, and timing.

### GNSS:
* A broader term that includes all satellite navigation systems.
* Includes 
[GPS (USA)](https://www.faa.gov/about/office_org/headquarters_offices/ato/service_units/techops/navservices/gnss/gps), 
[GLONASS (Russia)](https://glonass-iac.ru/en/about_glonass/), 
[Galileo (European Union)](https://www.euspa.europa.eu/eu-space-programme/galileo), 
[BeiDou (China)](http://en.beidou.gov.cn/), and others ([IRNSS (India)](https://www.ursc.gov.in/navigation/irnss.jsp),
[QZSS(Japan)](https://qzss.go.jp/en/overview/services/sv02_why.html)).
* Provides more satellites and better coverage, especially in challenging environments.
* Offers improved accuracy and reliability by combining signals from multiple systems.

![4 GNSS constellations](../../assets/images/gnss/gnss_constellations.png)<br>
*Image: 4 GNSS constellations [^5]*<br>

### Updates:<br>
The number of satellites and their operational status changes over time. This information pertains to April 2023.
* GPS - 31 satellites (31 operational)[^2][^6]<br>
* GLONASS - 25 satellites (24 operational)[^6]<br>
* Galileo - 28 satellites (24 operational)[^6]<br>
* BeiDou - 29 satellites (27 operational)[^6]<br>

https://www.faa.gov/about/office_org/headquarters_offices/ato/service_units/techops/navservices/gnss/gps/howitworks#:~:text=However%2C%20by%20taking%20a%20measurement,longitude%2C%20altitude%2C%20and%20time.
https://cmr.earthdata.nasa.gov/search/concepts/C1419766346-CDDIS.html


#### How GPS maintain accurate orbit and time
* Atomic clocks - typically measuring time to within a nanosecond (one billionth of a second). 
* Time dilation - Einstein's theory of relativity: the clocks on the satellites run slightly faster than clocks on 
Earth because of their high speed and lower gravity. [^3] 
* Orbit - GPS satellites orbit the Earth at a medium altitude, typically around 20,200 kilometers (12,540 miles)
and each satellite completes two orbits per day.
* Ground station monitoring - continuously monitor the satellite clocks and orbits, sending correction data to the 
satellites to maintain accuracy. [^4]

[^1]: [What is the difference between GNSS and GPS?](https://www.mobatime.com/article/difference-between-gnss-and-gps/), MOBATIME, 2021-05-26. 

[^2]: [Satellite Navigation - Global Positioning System (GPS)](https://www.faa.gov/about/office_org/headquarters_offices/ato/service_units/techops/navservices/gnss/gps#:~:text=Currently%2031%20GPS%20satellites%20orbitand%20in%20all%20weather%20conditions), Federal Aviation Administration.

[^3]: [The Satellite Clock](https://www.e-education.psu.edu/geog862/node/1714#:~:text=However%2C%20this%20apparent%20slowing%20of,about%2045%20microseconds%20a%20day.), PennState College of Earth and Mineral Science.

[^4]: [Control segment](https://www.gps.gov/systems/gps/control/), GPS.gov.

[^5]: [What are the limitations of GNSS?](https://inertiallabs.com/what-are-the-limitations-of-gnss/) Inertial Labs, 2024-10-02.

[^6]: [GPS Overview Part 1: What is GPS and GNSS Positioning?](https://eos-gnss.com/knowledge-base/gps-overview-1-what-is-gps-and-gnss-positioning), EOS Positioning Systems.

### Satellite Based Augmentation System (SBAS)

Reid, Tyler & Walter, Todd & Blanch, Juan & Enge, Per. (2015). GNSS Integrity in the Arctic.</br>
![Geostationary orbit](/GNSS/assets/images/gnss/gnss_sbas_geostationary_orbit.png)







[What is GNSS/RTK technology and how does it work?](https://www.youtube.com/watch?v=k49sUW7vkY4) by [Ardusimple](https://www.youtube.com/@ardusimple)

[RTK vs PPK: Differences between Real-Time and Post-Processed Kinematic for precise GNSS location](https://www.youtube.com/watch?v=vi_eGCWUq2Y) by by [Ardusimple](https://www.youtube.com/@ardusimple)

https://www.youtube.com/watch?v=qPTIi7Ds15M