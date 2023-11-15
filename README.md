# 🌐📡 Mozilla Location Service Globe

![Demonstration Image](/demo-images/simple_demo_1.png)

The [Mozilla Location Service](https://location.services.mozilla.com) (MLS), a collaborative effort by Mozilla, offers an open-source location service. This visualization aims to showcase the extensive reach of the project and highlight connectivity hotspots globally. It leverages the [WebGL Globe](https://github.com/dataarts/webgl-globe) framework, an open-source creation by the Google Data Arts Team.

This repository is an updated version of the original, written back when I was in high school. The original version is available [here](https://github.com/yuan-alex/mozilla-location-service-globe).

#### How to Use:

- Ensure the Mozilla Location Service data is located in your directory.
- Modify the string that `process.py` reads to match the data file's name.
- Execute `python3 process.py`.
- A JSON file named `compiled.json` will be generated in your directory.
- The globe will visualize the new data from `compiled.json`.

If the lines on the globe appear too large or small, adjust the number added during each processing iteration in `process.py`. The `precision` variable dictates the accuracy of the data points displayed on the globe.

The code driving the demo differs slightly from Google's repository version.

#### Data Source and File Availability:

The data fueling this visualization originates from the Mozilla Location Service but is not included in this repository due to its substantial size. You can download it [here](https://location.services.mozilla.com/downloads). After obtaining the raw data, update the CSV file name string in `process.py`.

# Gallery

![Demonstration Image 2](/demo-images/demo_2.png)

![Demonstration Image 3](/demo-images/demo_3.png)
