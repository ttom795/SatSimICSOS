# Realtime Satellite Visualiser

This build provides a real-time 3D visualisation of Low Earth Orbit (LEO) satellites using data from [Celestrak](https://celestrak.org/NORAD/elements/gp.php?GROUP=starlink&FORMAT=tle).

## Overview

**SatSim** is a standalone application that renders the positions and trajectories of satellites in real time.
It uses Two-Line Element (TLE) data from Celestrak and an accurate orbital model via usage of SGP4.

The visualiser provides an interactive, immersive view of global satellite constellations and their motion across the Earth, useful for demonstrations, research, and verification of satellite network algorithms.

## Getting Started

1. Download or clone this repository to your local machine.
3. Run the executable "SatelliteBase" - no installation or Unity Editor is required.
4. *(Optional)* To update satellite data:

   * Replace the `gp.txt` file in the `StreamingAssets` folder with an up-to-date copy from Celestrak.
   * Update the `time` variable in the `config.cfg` file in the same folder to the time the data was gathered (in UTC format).
   * Restart the application to load the new dataset.

## Dependencies

* None required because this is a pre-built standalone application.
* *(Optional)* Internet connection if fetching or updating satellite TLE data manually.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

* **Celestrak** - for publicly available satellite TLE datasets.
* **David A. Vallado** - for his work in orbital mechanics and reference for the SGP4 algorithm.
* **Unity Technologies** - for the 3D engine used to build this visualisation software.

## Contact

For questions, feedback, or collaboration inquiries, contact:
**[ttom795@aucklanduni.ac.nz](mailto:ttom795@aucklanduni.ac.nz)**
