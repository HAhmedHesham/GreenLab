# Evolution of Kotlin apps replication package
.
.
### About
The purpose is to test how the energy consumption of Kotlin applications changes with time

### Requirements
##### Hardware:
• Raspberry Pi 3: Debian 11, ARM Cortex-A53, 1 GB RAM
• Android Device: Nokia 6.2, Android 10, Qualcomm SDM636,
4GB RAM, eMMC 5.1
• Personal computer for connecting to Raspberry PI via SSH
connection.
##### Software:
• Android Runner: A tool for launching applications and automating testing on an Android device.
• Python v.3.9.13: Python development environment and application interpreter, used to run the Android Runner.
• Android SDK: Set of tools to build, test, and debug apps for Android.
• Monkeyrunner : A tool provides an API for writing programs that control an Android device or emulator from outside of Android code.
• RStudio v.2022.07.2-576 4


### Reproduction
This repository consists of subfolders that allow the replication of the project. Each subfolder contains its own readme file that provides a description on the requirements and usage. If only interested in replicating the data analysis the subfolder 00 Data and 05 Analysis are sufficient.

### 01 Data
It contains a list of 88 mobile apps that represents the initial pool of apps to choose from. Also, it contains the list after applying the inclusion and exclusion criteria. Finally, it contains the data that were collected after each trial of the experiment.

### 02 Tests
It contains the tests(recorded keystrokes) that were used on each release of each application.

### 03 Experiment
Contains the adjusted python experiment scripts for android-runner and the required android-runner config file.

### 04 Analysis
Contains R scripts to perform statistical tests
