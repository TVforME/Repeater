# Welcome to the DATV Repeater Project!

🚀 **Revolutionize digital amateur television!** 

The DATV Repeater project is at the forefront of software innovation, leveraging advances in GPU hardware to deliver a software-derived DATV Repeater!

## Repeater Overview

![Overview](https://github.com/TVforME/Repeater/blob/main/assets/images/Repeater-Overview.png)

🌍 This project is not just about making the design flexible and extendable; It was inspired from  BBC [Brave](https://github.com/bbc/brave) and [Voctomix](https://github.com/voc/voctomix) projects, both written in Python with the Gstreamer framework. I have adapted to take full advantage of newer GPU H264 hardware decoding and encoding using [NVIDIA Tesla P4](https://images.nvidia.com/content/pdf/tesla/184457-Tesla-P4-Datasheet-NV-Final-Letter-Web.pdf) PCIe card/s in my design. 

I initially wrote code to both windows and linux however, dropped windows over linux for driver support and issues with gstreamer shmsrc and shmsink and also interpipe not compatable on windows. Linux is a far more robust OS for 24/7 operation.
Please don't get into a debate on OS.. I've programmed on both and I personally find Linux flaovour suited to my understanding and getting code to work. Windows has it advantages, however, it's never played up well compared to Linux both Ubuntu, Debian, Raspberry Pi and recently CoreLinux

I've opted to build DATV repeater in GO! <img src="assets/icons/go.ico" alt="icon" width="30" height="25"> to leverage concurrency and parallelism and speed. I orginally developed with Python 3 however, soon relised I was going in too deep and began using asyncio and GLib and other packages making the code base complex. I'm new to golang and I decided to give it a shot to learn and see what I can pull together.

## Let's GO! <img src="assets/icons/go.ico" alt="icon" width="30" height="25">
- **GO is built for concurrency. Parallelism out-of-the-box:**  GO is design to run functions is parallel GO's way of threading using goroutines.
- **NO Object Orientated Programming:** I'm not a fan of OOP Classes and overrides all that jazz.  I've come from C pointers and structures, GO uses old school C structure, interfaces and can handle "strings" properly.
- **Easy to use and great support:** GO is a modern programming laugauge. it's easy and there is plenty of support of forums and Youtube how to's..
- **Compiles to ONE executable:**  That's right, ONE executable. No frameworks, or addition lanuage dependencies.  GStreamer and few other libraries are requires for repeater to operate however, this is a given regardless of language used.
- **Statically Typed lanuage:**  Hard to get it wrong.. GO's intuitive compiler lets you know before compilation your if your passing a function a int over a string. 

🛠️ The design aims to reduce valuable rack space at a facility and use a more modern approach to AV mixing and playout in DVB tansport stream. A typical DATV repeater consists of black boxes interconnected with HDMI/USB/SDI cables, using IR or serial converters to communicate between these blackboxes with a microcontroller. My software approach has been a four-year learning experience, and ongoing addiction..

💡 Dive into our documentation to learn more about how the DATV Repeater is setting new standards in the amateur television landscape.
The repeater site is located at Mount Anakie, Victoria. Call sign **VK3RGL**.
[DATV Repeater Wiki](https://github.com/TVforME/Repeater/wiki)

🆘 If you're into GStreamer and GO or bash install scripts and up to helping out, please drop me an email and introduce yourself. 
[VK3DG](mailto:vk3dgtv@gmail.com?subject=DATV%20Repeater%20Help)

🔗 Stay tuned for files to be added as parts are working!
Explore, contribute, and be a part of the DATV Repeater Project's journey to transform digital amateur television!


---
