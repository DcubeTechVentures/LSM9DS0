[![LSM9DS0](LSM9DS0_I2CS.png)](https://www.controleverything.com/content/Accelorometer?sku=LSM9DS0_I2CS)
# LSM9DS0
LSM9DS0 3D Accelerometer, 3D Gyroscope, 3D Magnetometer

The LSM9DS0 device, provides digital acceleration, angular acceleration and magnetic field for X, Y and Z axis

This Device is available from ControlEverything.com [SKU: LSM9DS0_I2CS]

https://www.controleverything.com/content/Accelorometer?sku=LSM9DS0_I2CS

This Sample code can be used with Raspberry pi, Arduino, Particle and Beaglebone Black.

## Java
Download and install pi4j library on Raspberry pi. Steps to install pi4j are provided at:

http://pi4j.com/install.html

Download (or git pull) the code in pi.

Compile the java program.
```cpp
$> pi4j LSM9DS0.java
```

Run the java program.
```cpp
$> pi4j LSM9DS0
```

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python LSM9DS0.py
```

## Arduino
Download and install Arduino Software (IDE) on your machine. Steps to install Arduino are provided at:

https://www.arduino.cc/en/Main/Software

Download (or git pull) the code and double click the file to run the program.

Compile and upload the code on Arduino IDE and see the output on Serial Monitor.


## Particle Photon

Login to your Photon and setup your device according to steps provided at:

https://docs.particle.io/guide/getting-started/connect/photon/

Download (or git pull) the code. Go to online IDE and copy the code.

https://build.particle.io/build/

Verify and flash the code on your Photon. Code output is shown in logs at dashboard:

https://dashboard.particle.io/user/logs


##C

Download (or git pull) the code in Beaglebone Black.

Compile the c program.
```cpp
$>gcc LSM9DS0.c -o LSM9DS0
```
Run the c program.
```cpp
$>./LSM9DS0
```
#####The code output is the raw values of acceleration, angular acceleration and magnetic field in X, Y and Z axis.
