# Welcome to the DATV Repeater Project!

🚀 **Revolutionize digital amateur television!** 

The DATV Repeater project is at the forefront of software innovation, leveraging advances in GPU hardware to deliver a software-derived DATV Repeater!

## Repeater Overview

![Overview](https://github.com/TVforME/Repeater/blob/main/assets/images/Repeater-Overview.png)

🌍 This project is not just about making the design flexible and extendable; It was inspired by the Voctomix project, the project takes a step further by integrating with Gstreamer pipelines's with the ability for full GPU decoding and encoding, DATV repeater is coded in Go to leverage Go's parallelism and speed. The proptype was developed in Python3 however, the design become far more complex as modules where added making my decision to look for a way to circimvent the complexities of threading with python. 
It was inevitiable for the code to be compiled.  Was it Go, Rust and C++ ??  Out of the 3, I chose Go [![Go-heart-balloon-32x40](https://github.com/TVforME/Repeater/assets/168706311/6d85af8a-82d8-49eb-ae11-fefb2bbc466b)](https://go.dev/ "Visit the GO website") for the reasons of:-

- **Parallelism out of the box:**  Go is design to run function is parallel Go's way of threading
- **Easy to use and gereat support:** Go is a modern programming laugauge. it's easy and there is plenty of support of firum and Youtube how to's..
- **Compiles to ONE executable:**  That's right, ONE executable. No frameworks, or addition dependencies.  GStreamer and few other libraries are requires for repeater to operate.
- **Statically Typed lanuage:**  Hard to get it wrong.. Go's intuitive compiler lets you know before compilation your if your passing a int over a string. 



🛠️ The design aims to reduce valuable rack space and simplify the interconnection process. A typical DATV repeater design consists of black boxes interconnected with HDMI cables, using IR or serial converters to communicate via a dedicated repeater microcontroller. My software approach has been a four-year learning experience, specifically designed for the Geelong Amateur Radio Club DATV repeater.

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
