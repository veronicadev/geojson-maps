<h2 align="center">Geojson maps</h2>
  <p align="center">
    Collection of geojson maps
    <br />
    <a href="https://github.com/veronicadev/geojson-maps"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/veronicadev/geojson-maps">Report Bug</a>
    ·
    <a href="https://github.com/veronicadev/geojson-maps">Request Map</a>
  </p>


<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
* [Contributing](#contributing)
* [Contact](#contact)

## About the Project
A simple collection of geojson maps to use in projects.

## Getting Started

Follow the instructions for creating a new geojson map.

1. Go to https://labs.mapbox.com/svg-to-geojson/

2. Zoom in on the region you want to generate

3. Using the **Polygon Tool** and trace the path of the region you want
<img src="https://raw.githubusercontent.com/veronicadev/geojson-maps/master/readme_img/001.PNG" alt="image">

4. After tracing the path click the **Dowload** button to download the map
<img src="https://raw.githubusercontent.com/veronicadev/geojson-maps/master/readme_img/002.PNG" alt="image">

5. You should have a file that looks like this
```
{
  "type": "FeatureCollection",
  "features": [
    {
      "id": "984c20526317009f7bd7df99094d0932",
      "type": "Feature",
      "properties": {},
      "geometry": {
        "coordinates": [
          [
            [
              10.84402560634058,
              45.82774964543475
            ],
            [
              10.890742407189265,
              45.804494147368075
            ],
            [
              10.872945530673775,
              45.78588275538863
            ],
            [
              10.88184396893152,
              45.76726514681599
            ],
            [
.....
```
6. Now you can use the .geojson file or if you prefer you can rename it with .json as extension

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Contact

Project Link: [https://github.com/veronicadev](https://github.com/veronicadev)
