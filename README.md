[中文](README.zh-CN.md) | [English](README.md)
# Awesome UAS List [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)
[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/)
# Awesome UAS List  
A curated list of AI, machine learning, computer vision, and autonomy resources for unmanned aerial vehicles (UAS), drones, quadcopters, and aerial robotics — including navigation, SLAM, flight control, path planning, simulation, and perception.

## Software
- [Frameworks](#frameworks)
- [Firmware for Flight Controllers](#Firmware-for-Flight-Controllers)
- [Firmware for Transmitters](#Firmware-for-Transmitters)
- [SDK & Libraries](#sdk--libraries)
- [Ground Control Stations](#ground-control-stations)
- [BlackBox](#blackbox)
## Tools & Ecosystem
- [Learning Resources](#learning-resources)
- [SLAM & State Estimation](#slam--state-estimation)
- [Computer Vision](#computer-vision)
- [Simulation](#simulation)
- [Datasets](#datasets)
- [Mechanical](#mechanical)
- [Electronics](#electronics)
- [Services](#services)
### Hardware
- [Remote Control Transmitters](#remote-control-transmitters)
- [Drone Frames](#drone-frames)
- [Headsets](#headsets)
- [Video Receivers](#video-receivers)
- [Electronics and Motors](#electronics-and-motors)
- [Cameras](#cameras)
### Products & Projects
- [Unmanned Aerial Vehicles](#unmanned-aerial-vehicles)
- [Unmanned Ground Vehicles](#unmanned-ground-vehicles)
- [Unmanned Underwater Vehicles](#unmanned-underwater-vehicles)
### Meta
- [Related Lists](#related-lists)
- [Contribute](#contribute)
- [License](#license)
---
## Software
### Frameworks
- [PX4 Autopilot](https://github.com/PX4/PX4-Autopilot) – Widely used open-source flight control stack for drones.
- [ArduPilot](https://github.com/ArduPilot/ardupilot) – Mature autopilot software for UAVs and autonomous vehicles.
- [ROS (Robot Operating System)](https://github.com/ros/ros) – Standard robotics middleware for UAV perception, planning, and control.
- [ROS 2](https://github.com/ros2/ros2) – Modern version of ROS designed for distributed, real-time robotics.
- [AirSim](https://github.com/microsoft/AirSim) – Open-source simulator for drones, robotics, and autonomous systems.
- [DroneKit](https://github.com/dronekit/dronekit-python) – Python library for drone control using MAVLink-compatible vehicles.
### Firmware for Flight Controllers
- [Ardupilot](https://github.com/ArduPilot/ardupilot)
- [BaseFlight](https://github.com/multiwii/baseflight) -
- [Betaflight](https://github.com/betaflight/betaflight) - Fork of Cleanflight.
- [ButterFlight](https://github.com/ButterFlight/butterflight) - Fork of Betaflight. Firmware focusing on Mini Quads.
- [Cleanflight](https://github.com/cleanflight/cleanflight) - Fork of BaseFlight. Supports more FCs and has additional PID contollers.
- [dRonin](https://dronin.org) - Autopilot/flight controller firmware for controllers in the OpenPilot/Tau Labs family.
- [EmuFlight](https://github.com/emuflight/EmuFlight) - FC Firmware focusing on flight performance, innovative filtering, leading-edge feature additions, and wide target support.
- [FalcoX](https://flightone.com/download.php?version=stable) - Formerly known as Raceflight one, FlightOne.
- [INAV](https://github.com/iNavFlight/inav)
- [Kiss](https://www.flyduino.net/en_US/page/downloads) - Firmware for KISS FCs.
- [LibrePilot](https://github.com/librepilot/LibrePilot) - (GitHub fork is Outdated/Inactive)
- [madflight](https://github.com/qqqlab/madflight) - Flight controller for Arduino ESP32 / RP2350 / RP2040 / STM32.
- [Open Source Rover Control Code](https://github.com/nasa-jpl/osr-rover-code) - Nasa JPL command firmware for the OSR.
- [PX4 Autopilot](https://github.com/PX4/PX4-Autopilot) - Rebranded to AutoPilot from Firmware
- [SilverWare](https://github.com/silver13/BoldClash-BWHOOP-B-03) - Firmware for BoldClash BWHOOP B-03 mini drone
- [SilverWare(NFE)](https://github.com/NotFastEnuf/NFE_Silverware) - Firmware for Alienwhoop ZER0, E011, BWHOOP B-03, H8mini, and BETA FPV LITE flight controllers with NotFastEnuf settings and experimental features.
### Firmware for Transmitters
- [FreedomTX](https://github.com/tbs-fpv/freedomtx) - Custom firmware for TBS Tango 2 based on OpenTX.
- [OpenTX](http://www.open-tx.org/) - Highly configurable open source firmware for RC radio transmitters.
- [EdgeTX](https://github.com/edgetx/edgetx) - EdgeTX is the cutting edge open source firmware for your R/C radio.
- [OpenVTx](https://github.com/OpenVTx/OpenVTx) - Open source video transmitter firmware for FPV.
- [OpenIPC](https://github.com/OpenIPC/firmware) - Alternative IP Camera firmware from an open community.
### SDK & Libraries
- [DJI Onboard SDK](https://github.com/dji-sdk/Onboard-SDK) - The Onboard SDK allows you to connect to a supported DJI flight controller using a serial port (TTL UART).
- [GoBot](https://github.com/hybridgroup/gobot) - Golang framework for robotics, drones, and the Internet of Things (IoT).
- [Libcyphal](https://github.com/OpenCyphal-Garage/libcyphal) - Portable reference implementation of the Cyphal protocol stack in C++ for embedded systems and Linux. Formerly known as LibUAVCAN.
- [MAVLink](https://github.com/mavlink/mavlink) - Micro Air Vehicle Message Marshalling Library.
- [MAVSDK](https://github.com/mavlink/MAVSDK) – APIs for controlling drones via MAVLink.
- [MAVROS](https://github.com/mavlink/mavros) – ROS interface for MAVLink-enabled pilots.
- [UAV Toolbox (MATLAB)](https://www.mathworks.com/products/uav.html) – Tools for modeling, simulation, and control design.
- [RotorS Simulator](https://github.com/ethz-asl/rotors_simulator) – UAV control and planning simulator for ROS.
- [ETHZ MPC Controllers](https://github.com/ethz-asl/mav_control_rw) – Model predictive control for quadrotors.
### Ground Control Stations
- [QGroundControl](https://github.com/mavlink/qgroundcontrol) - Cross-platform ground control station for drones (Android, iOS, Mac OS, Linux, Windows).
- [Arduleader](https://github.com/geeksville/arduleader) - An android ground controller (and other things) for Mavlink/Arduplane.
- [Tower](https://github.com/DroidPlanner/Tower) - Ground Control Station for Android Devices.
- [MAVProxy](http://ardupilot.github.io/MAVProxy/) - A UAV ground station software package for MAVLink based systems.
- [Ardupilot Mission Planner](https://ardupilot.org/planner/index.html) - A full-featured ground station application for the ArduPilot open source autopilot project.
- [APM Planner 2](https://ardupilot.org/planner2/) - An open-source ground station application for MAVlink based autopilots including APM and PX4/Pixhawk that can be run on Windows, Mac OSX, and Linux.
- [ArduPilot Mission Planner](https://github.com/ArduPilot/MissionPlanner)
- [Paparazzi](http://wiki.paparazziuav.org/wiki/Main_Page)
- [QGroundControl](http://qgroundcontrol.com/)
### BlackBox
- [Easyquadtune](https://easyquadtune.vercel.app) - Betaflight blackbox log analysis: filter changes from the log's noise peaks, PID changes from the measured step response, emitted as a CLI diff. First log free.

---
## Tools & Ecosystem
### Learning Resources
- [MIT UAV Robotics Course](https://aeroastro.mit.edu/)
- [ETH Zurich Aerial Robotics](https://asl.ethz.ch/)
- [UPenn GRASP Lab](https://www.grasp.upenn.edu/)
- [Stanford Aerial Mobility](https://aa.stanford.edu/)
- [PX4 Documentation](https://docs.px4.io/)
- [ArduPilot Docs](https://ardupilot.org/)
- [Flying Car and Autonomous Flight Engineer](https://eu.udacity.com/course/flying-car-nanodegree--nd787)
- [Robotics: Dynamics and Control](https://www.edx.org/course/robotics-dynamics-control-pennx-robo3x)
- [UAS/Drone Remote Pilot Test Prep for Part 107](https://www.udemy.com/remote-pilot-certificate-test-prep-for-part-107-exam/)
- [Drone Photography](https://www.udemy.com/course/dronephotography/)
- [Drone Programming with Python](https://www.udemy.com/course/drone-programming-with-python-face-recognition-tracking/)
### SLAM & State Estimation
- [ORB-SLAM3](https://github.com/UZ-SLAMLab/ORB_SLAM3) – State-of-the-art visual, stereo, and RGB-D SLAM.
- [VINS-Fusion](https://github.com/HKUST-Aerial-Robotics/VINS-Fusion) – Visual-inertial odometry for aerial robotics.
- [OKVIS](https://github.com/ethz-asl/okvis) – Keyframe-based visual–inertial odometry.
- [RTabMap](https://github.com/introlab/rtabmap) – Real-time appearance-based SLAM.
- [Kimera](https://github.com/MIT-SPARK/Kimera) – Visual–inertial SLAM with 3D mesh reconstruction.
- [Drone-Satellite-Ground Three Platiform Localization](https://github.com/layumi/University1652-Baseline) 
- [ACM MM2023 Workshop: UAV in Multimedia](https://www.zdzheng.xyz/ACMMM2023Workshop/)
- [Visual Localization Leaderboard](https://github.com/layumi/University1652-Baseline/tree/master/State-of-the-art)
### Computer Vision
- [YOLOv8](https://github.com/ultralytics/ultralytics) – Real-time object detection good for onboard UAV tasks.
- [OpenCV](https://github.com/opencv/opencv) – Core library for computer vision and onboard perception.
- [DeepSORT](https://github.com/nwojke/deep_sort) – Tracking-by-detection pipeline for UAV object tracking.
- [Detectron2](https://github.com/facebookresearch/detectron2) – Modern vision detection and segmentation.
- [FastSAM](https://github.com/CASIA-IVA-Lab/FastSAM) – Lightweight segmentation for real-time UAV workloads.
- [OpenMMLab](https://github.com/open-mmlab) – Full computer vision stack useful for UAV perception.
### Simulation
- [AirSim](https://github.com/microsoft/AirSim) – Photorealistic simulation environment with UAV physics.
- [Gazebo](https://gazebosim.org/) – Widely used robotics simulator for aerial and ground robots.
- [NVIDIA Isaac Sim](https://developer.nvidia.com/isaac-sim) – High-fidelity simulation for robotics and aerial drones.
- [JMAVSim](https://github.com/PX4/jMAVSim) – Java-based simulator used by PX4.
- [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents) – Unity-based reinforcement learning and simulation.
- [Unreal Engine](https://www.unrealengine.com/) – Realistic environments for drone simulation and synthetic data generation.
- [AirSim](https://github.com/Microsoft/AirSim) - Open source simulator based on Unreal Engine for autonomous vehicles.
- [LiftOff](https://www.immersionrc.com/fpv-products/liftoff-drone-race-simulator/) - :dollar: FPV racing simulator with realistic OSD (on-screen display) experience.
- [Orqa FPV.SkyDive](https://skydive.orqafpv.com/) - Orqa FPV's racing and freestyle simulator.
- [RotorRush](http://rotorrush.com/) - :dollar: Formerly known as FPV Event. Subscription based simulator.
- [VelociDrone](https://www.velocidrone.com/) - :dollar: Multiplayer FPV racing simulator.
### Datasets
- [EuRoC MAV Dataset](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets) – Visual–inertial SLAM benchmark.
- [UAV123](https://cemse.kaust.edu.sa/ivul/uav123) – UAV tracking dataset.
- [VisDrone](https://github.com/VisDrone/VisDrone-Dataset) – Drone-based detection & tracking dataset.
- [AirSim Datasets](https://github.com/microsoft/AirSim) – Synthetic UAV perception data.
- [DronesDataset](https://github.com/Ahmedsalman88/DronesDataset) – Drone detection dataset.
- [UAVDT](https://github.com/VisDrone/UAVDT) – UAV traffic detection dataset.
- [UAV-Human](https://github.com/SUTDCV/UAV-Human) – Drone-captured human activity dataset.
### Mechanical
- [GrabCAD](https://grabcad.com/library) – Open-source mechanical CAD models for drone frames and components.
### Electronics
- [Oshwhub](https://oshwhub.com/) – Open-source hardware platform for sharing PCB designs and electronics projects.
### Services
- [AirMap](https://www.airmap.com/) - Aeronautical data & services to unmanned aircraft.
- [DroneDeploy](https://www.dronedeploy.com/) - Drone & UAV Mapping Software.
- [RotorBuilds](https://rotorbuilds.com/) - FPV Part lists and Build Logs.
- [Zeitiew](https://www.zeitview.com/) - Online marketplace for Drone services. Formerly known as DroneBase.
## Hardware
### Remote Control Transmitters
- [FlySky](http://www.flyskyrc.com/) - Entry level transmitters.
- [FrSky](https://www.frsky-rc.com/) - Taranis and Horus line of transmitters powered by OpenTX firmware.
- [Futaba](https://www.futabarc.com)
- [Spektrum](https://www.spektrumrc.com)
- [Team Blacksheep](https://team-blacksheep.com) - Tango 1 and 2 transmitters.
### Drone Frames
- [Source One by TBS](https://github.com/tbs-trappy/source_one) - Open Source freestyle FPV drone frame.
- [Source Two by TBS](https://github.com/ps915/source_two) - Open Source racing FPV drone frame.
- [Source Micro by TBS](https://github.com/ps915/source_micro) - Open Source mini drone frame.
- [Source PodRacer](https://github.com/ps915/source_podracer) - Open source ultra-light drone frame.
- [Source V by TBS](https://github.com/ps915/source_v) - Open Source ultra-stiff drone frame.
- [Source X by TBS](https://github.com/ps915/source_x) - Open Source giant racing drone frame.
### Headsets
- [DJI Digital FPV System](https://www.dji.com/fpv/) - Low latency digital FPV goggles.
- [FatShark](https://www.fatshark.com) - Headsets praised by racers.
- [ORQA FPV.One](https://orqafpv.com) - Headsets and controllers
### Video Receivers
- [ClearView XLR 1.3](https://clearview-direct.com/product-category/ground-station-receivers/1-3-receivers/)
- [ClearView XLR 2.4](https://clearview-direct.com/product-category/ground-station-receivers/2-4-receivers/)
- [TBS Ground station](https://www.team-blacksheep.com/products/prod:tbs_gs_2g4)
- [ClearView Goggle Receiver](https://clearview-direct.com/shop/clearview-goggle-products/clearview-goggle-module/)
- [ClearView 5.8GHz Ground Station Receivers](https://clearview-direct.com/product-category/ground-station-receivers/5-8-receivers/)
- [rapidFIRE](https://www.immersionrc.com/fpv-products/rapidfire/)
- [TBS Fusion](https://www.team-blacksheep.com/products/prod:tbs_fusion) - Has CRSF integration (for changing channels).
### Electronics and Motors
Terminology:
- FC = Flight Controller
- ESC = Electronic Speed Controller
- PDB = Power Distribution Board
- RX = Receivers
- TX = Transmitters (external)
- VRX = Video Receiver
- VTX = Video Transmitter

List:
- [3BHobby](https://www.3bhobby.com) - Motors
- [Airbot](https://store.myairbot.com/flight-controller.html) - FC, ESC
- [BrotherHobby](https://www.brotherhobbystore.com) - Motors
- [ClearView](https://clearview-direct.com/) - VRX, VTX
- [DalProp](http://dalprop.com) - Props
- [Diatone](https://www.diatone.us/) - FC, ESC, VTX, Motors
- [Fl1ghtOne](https://flightone.com) - FC, ESC
- [Flyduino](https://www.flyduino.net/en_US/) - FC, ESC
- [GemFan](https://www.gfprops.com/) - Props
- [Hobbywing](http://www.hobbywing.com) - FC, ESC, Motors
- [Holybro](http://www.holybro.com) - FC, ESC, PDB
- [HQProp](http://www.hqprop.com) - Props
- [iFlight](https://www.iflight-rc.com) - Motors
- [Lumenier](https://www.lumenier.com) - FC, ESC, PDB, VTX, Motors
- [MatekSys](http://www.mateksys.com) - FC, PDB, VTX
- [RacerStar](https://www.racerstar.com) - FC, ESC, Motors
- [SP Racing](http://seriouslypro.com) - FC
- [T-Motor](http://www.tmotor.com) - FC, Motors
- [Team Blacksheep](https://www.team-blacksheep.com) - ESC, RX, TX, VRX, VTX
### Cameras
- [Caddx.us](https://caddxfpv.com/)
- [DJI O3 Air unit](https://www.dji.com/ee/o3-air-unit) - Camera with digital video transmission
- [Foxeer](http://www.foxeer.com)
- [RunCam](https://runcam.com)
## Products and Projects
### Unmanned Aerial Vehicles
- [DJI](https://www.dji.com/) - DJI is the world's leader in the consumer drone market - Mavic, Phantom, Inspire and Matrice series drones.
- [Autel](https://www.autelpilot.eu/) - Compact EVO series drones, alternative to DJI Mavic series. Dragonfish series fixed-wing UAVs coming soon.
- [Eachine](https://www.eachine.com/) - Mini and micro drones. FPV beginners sets.
- [Hubsan](https://www.hubsan.com/na/) - Micro and Mini lower cost drones.
- [Parrot SA](https://www.parrot.com/global/) - Famously Parrot Bebop and Parrot AR series drones.
- [Syma](http://www.symatoys.com/) - RC toy quadcopters.
- [Yuneec International](https://www.yuneec.com/) - Yuneec camera drones.
- [AeroVironment](https://www.avinc.com/) - Small range fixed-wing UAVs.
- [Baykar](https://www.baykartech.com/en/) - Bayraktar series battle- proven long-range fixed-wing UAVs.
- [Eli](http://www.uav.ee/) - Pneumatic launchers for fixed wing UAVs.
- [INSITU](https://www.insitu.com/) - Long-range and extended endurance fixed-wing UAVs.
- [Threod Systems](http://threod.com/) - Fixed-wing and multi-rotor UAVs.
### Unmanned Ground Vehicles
- [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover) - Nasa JPL scaled down version of the curiosity rover, made of COTS.
- [Turtlebot](https://www.turtlebot.com) - Open sourced UGV, [ROS](http://www.ros.org/) standard platform.
### Unmanned Underwater Vehicles
- [Geneinno](https://www.geneinno.com/) - Underwater drones.
## Related Lists
- [Awesome Robotics](https://github.com/awesomelistsio/awesome-robotics)
- [Awesome Computer Vision](https://github.com/awesomelistsio/awesome-computer-vision)
- [Awesome Reinforcement Learning](https://github.com/awesomelistsio/awesome-reinforcement-learning)
- [Awesome AI Agents](https://github.com/awesomelistsio/awesome-ai-agents)
- [Awesome AI Research Tools](https://github.com/awesomelistsio/awesome-ai-research-tools)
- [Awesome Drones](https://github.com/janesmae/awesome-drones)
## Contribute
Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.
## License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
