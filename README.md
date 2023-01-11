# VAST Data Set
IROS 2022 open source data set containing macro images, spectral readings, and IMU measurements for 11 different surface types from the 2022 IROS Submission:
VAST: Visual and Spectral Terrain Classification in Unstructured Multi-Class Environments

- Asphalt
- Brick
- Carpet
- Concrete
- Grass
- Gravel
- Ice
- Mulch
- Sand
- Tile
- Turf

## What's in the dataset?

- Images from downward facing cameras
- Visible-Near Infrared spectrometer readings captured from a StellarNet BlueWave Spectrometer (350 - 1100 nm)
- Snippets of IMU readings associated

Each numeric index means all entries are associated. E.g. `0000001_img.jpg, 0000001_spec.npy, 0000001_imu.npy` are all readings collected at the same time.
### How to Use?

1. Clone the repo
```
git clone https://github.com/RIVeR-Lab/vast_data
```
2. Open images with OpenCV/Numpy
3. Open spectral/IMU/labels with Numpy
