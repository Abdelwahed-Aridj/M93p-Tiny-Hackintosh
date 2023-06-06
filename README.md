<div align="center">
  
# OpenCore 0.9.2 for Lenovo M93p Tiny

![Ventura About This Mac](Resources/darkabout.png#gh-dark-mode-only) ![Ventura About This Mac](Resources/lightabout.png#gh-light-mode-only) |
| ----------------------------------------- |

  ## ⚠️ NOTICE ⚠️
  
  **This Configuration is be used as a guide to help you create your own OpenCore configuration for this ThinkCentre as some Configuration was made to work specifically for this PC e.g wifi Card,Bluetooth but it can be used as is, only at your own risk.**
  
  
## System Specifications
  
| Component | Model |
| :-: | :-: |
| CPU | Intel(R) Core(TM) i7-4790 CPU @ 3.60GHz |
| RAM | (12GB) of DDR3-1600 |
| GPU | Intel HD Graphics 4600 |
| Storage | SATA 512GB SSD |
| Audio | Realtek ALC283 |
| Internal WiFi/Bluetooth | Intel Centrino Wireless-N 2230  |
| Ethernet | Intel I217-LM |
  
## Contents
  
[**System Specifications**](#system-specifications)

[**Known Issues**](#known-issues-and-work-arounds)


## known issues and work arounds
  
  ### VGA Port
  **VGA is Officially not supported and wont work,if you have HDMI or Display Port use them instead**

  ### Intel HD 4400 and 4600 GPU Support
  **Due to changes in MacOS Ventura 13 the support for Intel GPU in 4th Gen CPUs was dropped you need to install an app called "OpenCore Legacy Patcher" to be able to use Graphical acceleration, its almost similar to driver mods in windows**
  

  | Step # | Link/Description |
  | :-: | :-: |
  | 1** | **(For Ventura Only)** [Use OpenCore Legacy Patcher to get graphics acceleration.](/Resources/Documentation/VenturaOCLP.md) |
  | 2** | check supported Broadcom WiFi card from [this link](https://dortania.github.io/Wireless-Buyers-Guide/types-of-wireless-card/mpcie.html#supported), if you want to use USB WIFI Adapter check [ this link](https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter#%EF%B8%8E---known-working-and-testing-adapter). |
 


</div>
