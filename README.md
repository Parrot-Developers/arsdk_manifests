ARDroneSDK3
===============

**Welcome to the Software Development Kit for Parrot Drones Version 3.**

It can be used to write applications which control the latest generation of Parrot Drones:
- Bebop Drone
- Bebop 2
- Rolling Spider
- Airborne Night
- Airborne Cargo
- Hydrofoil
- Jumping Sumo
- Jumping Night
- Jumping Race
- Skycontroller

<br>
  
The SDK provides the source code you need to do everything provided by the freeflight 3 application:
- discover the drones on the network
- connect the drones
- send piloting and camera commands
- configure the drones
- get informations (depends on drones capabilities)
- get H264 video stream on bebop
- get MJpeg video stream on Jumping Sumo
- transfer Photos / videos
- update the drones
- handle Drone Academy / Mavlink files
- and everything which pops out of your mind

<br>

**The easiest way to control a drone is to create a device controller thanks to the [libARController](https://github.com/Parrot-Developers/libARController)**. Samples which use this new API are available : [iOS Sample](https://github.com/Parrot-Developers/Samples/tree/master/iOS/SDKSample), [Android Sample](https://github.com/Parrot-Developers/Samples/tree/master/Android), [JSPilotingNewAPI](https://github.com/Parrot-Developers/Samples/tree/master/Unix/JSPilotingNewAPI) and [BebopPilotingNewAPI](https://github.com/Parrot-Developers/Samples/tree/master/Unix/BebopPilotingNewAPI) for Unix.

It's BSD license allows to use, change, distribute with no restriction.
Contributions and new feature discussions are highly appreciated.


**The latest release version is tagged ARSDK3_version_3_9_0**. This version of the SDK is the one used in the 3.9 versions of FreeFlight 3. <br/>
It is fully compatible with the versions :

* 3.2.0 and later for the Bebop drone
* 3.2.0 and later for the Bebop 2
* 1.99.2 for the Rolling Spider
* 2.1.55 for the Airbornes
* 1.99.0 for the Jumping Sumo
* 2.1.53 for the Jumping Sumo Evos

Usage
-------------
Please read [the install documentation](http://developer.parrot.com/docs/bebop/#go-deeper)

Questions
----
**If you have any questions, please open a new DroneSDK topic on the [Parrot Developer forum](http://forum.developer.parrot.com/).**

Samples
---------
You can find [samples files](https://github.com/ARDroneSDK3/Samples.git). These samples will help you to build the interface between products and controllers. 
Feel free to use and adapt them to your needs.

License
---------
Please read the [license file](https://github.com/ARDroneSDK3/ARSDKBuildUtils/blob/master/LICENSE.md).