# Real-Time Kinetic (RTK) positioning

Real-Time Kinetic (RTK) positioning is a satellite navigation technique used to enhance the precision of position data derived from satellite-based positioning systems such as GPS, GLONASS, Galileo, and BeiDou. RTK positioning provides real-time corrections to the data received from GNSS (Global Navigation Satellite System) satellites, allowing for centimeter-level accuracy.  
## Key Components of RTK Positioning
**Base Station**: A fixed GNSS receiver at a known location that continuously receives satellite signals and calculates corrections.
**Rover**: A mobile GNSS receiver that applies the corrections received from the base station to its own satellite data to determine its precise position.
**Communication Link**: A data link (e.g., radio, cellular, internet) that transmits the correction data from the base station to the rover in real-time.

## How RTK Works

- The base station calculates the difference between its known position and the position calculated from satellite signals.
- These differences (corrections) are transmitted to the rover.
- The rover applies these corrections to its own satellite data to achieve high-accuracy positioning.
- RTK is widely used in applications requiring high precision, such as surveying, agriculture, construction, and autonomous vehicles.

## Real-Time Kinetic (RTK) positioning is needed for several reasons  

- **High Accuracy**: RTK provides centimeter-level accuracy, which is essential for applications requiring precise positioning, such as surveying, construction, and agriculture.  
- **Real-Time Data**: RTK delivers real-time corrections, allowing users to obtain accurate position data instantly, which is crucial for time-sensitive operations.  
- **Reliability**: RTK improves the reliability of GNSS data by correcting errors caused by atmospheric conditions, satellite orbits, and clock discrepancies.  
- **Efficiency**: By providing accurate and real-time position data, RTK enhances the efficiency of field operations, reducing the need for post-processing and rework.  
- **Versatility**: RTK is compatible with various GNSS systems (GPS, GLONASS, Galileo, BeiDou), making it a versatile solution for global positioning needs.  

Overall, RTK is essential for any application where high precision and real-time positioning are critical.

https://upload.wikimedia.org/wikipedia/commons/b/b4/Comparison_satellite_navigation_orbits.svg

# Networked Transport of RTCM via Internet Protocol (NTRIP)

NTRIP is a protocol designed to stream GNSS correction data over the internet for Real Time Kinematic (RTK) positioning. It is built on the HTTP/1.1 protocol and optimized for integration with RTK correction services.<br>

Key components of NTRIP include:  

- NTRIP Server: Streams GNSS data to the NTRIP Caster.
- NTRIP Caster: Acts as a relay, distributing data from the NTRIP Server to multiple NTRIP Clients.
- NTRIP Client: Receives GNSS data from the NTRIP Caster for use in real-time applications.
- NTRIP uses standard internet protocols (HTTP/HTTPS) and is designed to be lightweight and efficient, making it suitable for use over various types of internet connections.

## Radio Technical Commission for Maritime Services (RTCM)

RTCM is a non-profit international standards organization. RTCM has released internationally recognized standards for 

- maritime navigation, 
- communication equipment, 
- distress alert systems, and 
- satellite positioning technologies like GPS. 

These standards support various fields, including 

- transportation, 
- surveying, geodesy, 
- precision agriculture, and 
- autonomous vehicles, 

providing essential high integrity and centimeter-level accuracy.

# NTIRP Server



# NTRIP Client







[What is GNSS/RTK technology and how does it work?](https://www.youtube.com/watch?v=k49sUW7vkY4) by [Ardusimple](https://www.youtube.com/@ardusimple)

[RTK vs PPK: Differences between Real-Time and Post-Processed Kinematic for precise GNSS location](https://www.youtube.com/watch?v=vi_eGCWUq2Y) by by [Ardusimple](https://www.youtube.com/@ardusimple)

https://www.youtube.com/watch?v=qPTIi7Ds15M