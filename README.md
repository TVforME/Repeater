# Welcome to the DATV Repeater Project!

🚀 **Revolutionize digital amateur television!** 

The DATV Repeater project is at the forefront of software innovation, leveraging advances in GPU hardware to deliver a software-derived DATV Repeater!

## Repeater Overview

![Overview](https://github.com/TVforME/Repeater/blob/main/assets/images/Repeater-Overview.png)

🌍 This project is not just about making the design flexible and extendable; It was inspired by the Voctomix project, the project takes a step further by integrating with Gstreamer pipelines's with the ability for full GPU decoding and encoding, DATV repeater is coded in Go to leverage Go's parallelism and speed. The proptype was developed in Python3 however, the design become far more complex as modules where added making my decision to look for a way to circumvent the complexities with threading.
It was inevitiable for a lanuage change.  Do I use Rust go with C++ ?? or GO! 

Out of the 3, I found the balance with Go. 

My reasons are:-
- **Go is built for concurrency. Parallelism out-of-the-box:**  Go is design to run functions is parallel Go's way of threading using goroutines.
- **NO Object Orientated Programming:** I'm not a fan of OOP Classes and overrides all that jazz.  I've come from C pointers and structures, Go is bases on old school C structure, interfaces and can handle "strings" properly.
- **Easy to use and great support:** Go is a modern programming laugauge. it's easy and there is plenty of support of forums and Youtube how to's..
- **Compiles to ONE executable:**  That's right, ONE executable. No frameworks, or addition lanuage dependencies.  GStreamer and few other libraries are requires for repeater to operate however, this is a given regardless of language used.
- **Statically Typed lanuage:**  Hard to get it wrong.. Go's intuitive compiler lets you know before compilation your if your passing a int over a string. 

🛠️ The design aims to reduce valuable rack space at a facility and use a more modern approach to AV mixing and playout in DVB tansport stream. A typical DATV repeater consists of black boxes interconnected with HDMI/USB/SDI cables, using IR or serial converters to communicate between blackboxes through a microcontroller. My software approach has been a four-year learning experience, and addiction since joining the Geelong Amateur Radio Club.

The repeater site is located at Mount Anakie, Victoria. Call sign **VK3RGL**.

💡 Dive into our documentation to learn more about how the DATV Repeater is setting new standards in the amateur television landscape.
[DATV Repeater Wiki](https://github.com/TVforME/Repeater/wiki)

🆘 If you're into GStreamer and GO or bash install scripts and up to helping out, please drop me an email and introduce yourself. 
[VK3DG](mailto:vk3dgtv@gmail.com?subject=DATV%20Repeater%20Help)

🔗 Stay tuned for files to be added as parts are working!

---

**Key Features:**

- **Configurable and Extendable:** Tailor the repeater to fit your specific needs and preferences.
- **GPU-Accelerated:** Harness the power of GPU hardware for efficient decoding and encoding.
- **Golang Integration:** Benefit from Golang's concurrency features for improved performance.
- **Space Efficiency:** Reduce the physical footprint of your setup by minimizing rack space.
- **Community Connection:** Join a network of amateur television enthusiasts across Australia.

Explore, contribute, and be a part of the DATV Repeater Project's journey to transform digital amateur television!


---
