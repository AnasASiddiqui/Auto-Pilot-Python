# PythonPilot
This is an Open Source Python Framework for prototyping ADAS and Autonomous Vehicles. It supports only Lateral Control now.

![](https://github.com/YanbaruRobotics/PythonPilot_readme_resources/raw/master/gifs/pythonpilot-demo.gif)

https://user-images.githubusercontent.com/36523448/132973406-5c318e51-4704-4c4a-be8b-d345cc6421fd.mp4

## Table of Contents
   * [Tested Development Environment](#Tested-Development-Environment)
   * [Getting Started](#Getting-Started)
   * [Running the demo](#Running-the-demo)
   * [Architecture](#Architecture)
   * [Use Cases](#Use-Cases)
   * [Acknowledgments](#Acknowledgments)
   * [License](#License)


## Tested Development Environment

- Processer: Intel Core i9-9900K CPU @ 3.60GHz × 16 
- Memory: 16GB
- Graphics: NVIDIA GeForce RTX 2080/PCIe/SSE2
- OS Types: Ubuntu 16.04 LTS 64-bit
- Disk: 240GB


## Getting Started
### Clone Repository

```
$ cd ~/
$ git clone https://github.com/YanbaruRobotics/PythonPilot
```

### Prerequisites
- Python 3.5.x

- matplotlib 3.0.2

- numpy 1.16.1

- OpenCV 3.4.5

- scipy 1.2.1

- tensorflow 1.13.0

```
$ cd ~/PythonPilot/
$ sudo pip3 install -r requirements.txt
```

### Download and uncompress the model

```
$ cd ~/PythonPilot/
$ wget https://www.dropbox.com/s/i7b6eyzucoxs0fq/models.zip   # 800 MB
$ unzip models.zip
$ rm -r models.zip
```

### Download and uncompress sample log data

```
$ cd ~/PythonPilot/
$ wget https://www.dropbox.com/s/mo6zo1oo2s46l02/log.zip   # 600 MB
$ unzip log.zip
$ rm -r log.zip
```


## Running the demo

![](https://github.com/YanbaruRobotics/PythonPilot_readme_resources/raw/master/gifs/how_to_run_demo.gif)

### Lunch a vehicle server

```
$ cd ~/PythonPilot/scripts/
$ bash run_vehicle_main.sh
```

### Lunch a pilot client
Open a new terminal.

```
$ cd ~/PythonPilot/scripts/
$ bash run_pilot_main.sh
```

### Stop Program
Type 'Ctrl' + 'c' in both terminals.


## Architecture

![](https://github.com/YanbaruRobotics/PythonPilot_readme_resources/raw/master/images/architecture.png)


## Use Cases
You can see other example videos at [here](https://www.youtube.com/playlist?list=PLj08U2JjuXcLGNupnirmlB8kN5zT_TTE4).

