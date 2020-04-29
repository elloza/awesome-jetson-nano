# awesome-jetson-nano [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome Nvidia Jetson Nano projects and resources.

![](https://www.nvidia.com/content/dam/en-zz/Solutions/intelligent-machines/jetson-nano/nvidia-jetson-nano-developer-kit-2c50-d.png)

## Needed hardware

* [Official Hardware Guide]()

| Item  | Description  | Price  |
|---|---|---|
| [Jetson Nano Pack](https://www.nvidia.com/es-es/autonomous-machines/embedded-systems/jetson-nano/)*  |  This pack only includes the Jetson Nano Board.   |  ~134 € including shipping.|
|  [Micro SD Card](https://www.amazon.com/gp/product/B06XX29S9Q/ref=as_li_ss_tl?ie=UTF8&psc=1&linkCode=sl1&tag=jetsonhacks-20&linkId=cef2bdb66716da2f7134cdbbed3aa5b8&language=en_US)* |  Recommended >= 32GB UHS-1 minimum | ~10 € |
| [Power Supply USB](https://www.amazon.com/Official-Raspberry-Foundation-Power-Supply/dp/B0793FR8ZJ/ref=as_li_ss_tl?keywords=official+usb+raspberry+pi+power+supply&qid=1552391931&s=gateway&sr=8-4&linkCode=sl1&tag=thedailyack-20&linkId=2fe6fdc43dce40300082328e95458fff&language=en_US)*  | Get Official power supply USB  | ~14€ |
| [Power Supply Jack](https://es.aliexpress.com/item/Adaptador-de-corriente-de-5-V-DC-5-V-1-5A-2A-2-5A-3A-3/32967617602.html?spm=2114.search0204.3.46.4f52391dSr16Gx&transAbTest=ae803_3&ws_ab_test=searchweb0_0%2Csearchweb201602_10_10065_10068_319_10059_10884_317_10887_10696_321_322_10084_453_10083_454_10103_10618_10307_537_536%2Csearchweb201603_54%2CppcSwitch_0&algo_pvid=81805edb-1130-433d-8ad8-74e5bde90173&algo_expid=81805edb-1130-433d-8ad8-74e5bde90173-10) |  5V 4A |  ~10€ |
| [Wireless USB](https://www.amazon.es/Edimax-EW-7811UN-Adaptador-Interfaz-negro/dp/B003MTTJOY/ref=sr_1_1?__mk_es_ES=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=Edimax+EW-7811Un&qid=1556966774&s=electronics-accessories&sr=8-1) | Check what wifi dongle is compatible with this board! [chipset LIST](https://elinux.org/Jetson/Network_Adapters#List_of_desired_Wifi_chipset_drivers)  | ~9€  |
|   [Wireless M2](https://es.aliexpress.com/item/Dual-G-Band-2-4-5-GHz-Wifi-Bluetooth-Wlan-para-Intel-8265NGW-inal-mbrico-AC/32847646700.html?albbt=Google_7_shopping&isdl=y&slnk=&albslr=200151807&src=google&acnt=494-037-6276&aff_platform=google&crea=es32847646700&netw=u&plac=&albcp=1633820309&mtctp=&aff_short_key=UneMJZVf&gclid=CjwKCAjw8LTmBRBCEiwAbhh-6N0x3I3zol-4pdglsM6tc7XukFhhuQyGQJ0yJ2F0fcKbTPosJ9_WvBoC91wQAvD_BwE&albag=63890294393&albch=shopping&albagn=888888&gclsrc=aw.ds&trgt=539263010115&device=c) | M2 wifi option  |  ~17€ |
|  [CSI Camera](https://www.amazon.com/Raspberry-Pi-Camera-Module-Megapixel/dp/B01ER2SKFS/ref=as_li_ss_tl?keywords=raspberry+pi+camera+v2&qid=1554226144&s=electronics&sr=1-3&linkCode=sl1&tag=jetsonhacks-20&linkId=d83850d1e300144afae124acab8ab636&language=en_US) |  MIPI-CSI(2) Camera | ~20€ |
|  [USB Camera](https://www.amazon.com/Logitech-Widescreen-Calling-Recording-Desktop/dp/B006JH8T3S/ref=as_li_ss_tl?ie=UTF8&qid=1543709223&sr=8-3&keywords=logitech+c920+webcam&linkCode=sl1&tag=jetsonhacks-20&linkId=71cb7db6e3b4cee2ed9a3f758cd63969&language=en_US) |  USB Camera | ~50€ |
|   |  TOTAL | ~158€-190€ |

(*) Basic Required

## Forums
* [Official Nvidia Forum](https://devtalk.nvidia.com/default/board/371/)


## Common errors
* [hangs on unnatended uppgr](https://forums.developer.nvidia.com/t/hangs-at-first-boot-at-waiting-for-unattended-upgr-to-exit/72686)


## How to setup you Jetson Nano
* [Getting Started with the NVIDIA Jetson Nano Developer Kit](https://blog.hackster.io/getting-started-with-the-nvidia-jetson-nano-developer-kit-43aa7c298797): A great tutorial to perform the initial setup of your Jetson Nano. This could save a lot of your time for the initial setup.
* [Official Setup Guide](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit)

## SWAP file
* [Install SWAP file](https://github.com/JetsonHacksNano/installSwapfile)

## CSI Camera
* [Jetson Nano CSI Camera](https://github.com/JetsonHacksNano/CSI-Camera)

## GPIO Jetson
* [Jetson NVIDIA GPIO](https://github.com/NVIDIA/jetson-gpio)

## Jetson Nano case 3d models
* [Jetson Nano Case](https://www.thingiverse.com/thing:3603594): A great case by Enrique Coiras. [Without antennas](https://www.thingiverse.com/thing:3518410)

![](https://cdn.thingiverse.com/renders/a5/00/69/3f/ee/a8579806d3b3eb1dc5d5bbd876e14171_preview_featured.jpg)

## Software Development USEFUL!

* [Visual studio Code](https://www.jetsonhacks.com/2019/10/01/jetson-nano-visual-studio-code-python/)
* [Tutorial](https://havedatawilltrain.com/got-nano-will-code/)

## Python & Tensorflow install
* Using these useful [scripts](https://github.com/karaage0703/jetson-nano-tools)

## Pytorch install
* [NVIDIA Forum thread](https://devtalk.nvidia.com/default/topic/1049071/pytorch-for-jetson-nano/)

## OpenCV
* [OpenCV 4 Install Script](https://github.com/AastaNV/JEP/blob/master/script/install_opencv4.0.0_Nano.sh) 

## ROS install
* [Jetson Easy Configurator](https://github.com/rbonghi/jetson_easy)
* [JetBot ROS](https://github.com/dusty-nv/jetbot_ros)

## Youtube Channels
* [JetsonHacks](https://www.youtube.com/channel/UCQs0lwV6E4p7LQaGJ6fgy5Q)
* [Zack's Lab](https://www.youtube.com/watch?v=U3VJCSDqdG4)

## Github projects
* [Official JetBot](https://github.com/NVIDIA-AI-IOT/jetbot)
* [Jetson Nano Object Detection and Tracking](https://github.com/SteveMacenski/jetson_nano_detection_and_tracking)



