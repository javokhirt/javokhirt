# Hi, I'm Javohir 

**Embedded firmware engineer in training. Bare-metal C, ARM Cortex-M, FreeRTOS.**

CS student at Penn State and co-founder of [JSRobotics](#-https://jsrobotics.uz/). I write firmware the hard way, straight against the reference manual, no HAL, no code generators; I love to actually understand the silicon, not click through a wizard.

I'm currently going deep on bare-metal STM32 and FreeRTOS, building toward the two-processor robotics architecture (real-time MCU + Linux/ROS2 compute) that serious robotics platforms run on.

---

## I work with:

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![ARM](https://img.shields.io/badge/ARM_Cortex--M-0091BD?style=flat-square&logo=arm&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-37AA4F?style=flat-square)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)

**Firmware:** bare-metal C, register-level peripheral drivers, interrupts/NVIC, DMA, FreeRTOS (tasks, queues, semaphores, mutexes)
**Protocols:** UART, SPI, I2C, CAN, PWM, ADC
**Toolchain:** `arm-none-eabi-gcc` · Make · OpenOCD · GDB/SWD — no IDE, terminal-driven
**Hardware:** STM32F411RE Nucleo · ESP32 · logic analyzer · oscilloscope
**Next on the roadmap:** embedded Linux (Buildroot/Yocto, device trees, kernel modules) → ROS2

---

## Featured projects

> Building these in public over summer 2026. 

| Project | What it demonstrates | Status |
|---|---|---|
| **[bare-metal-stm32-uart](#)** | Interrupt-driven UART driver with TX/RX ring buffers. No HAL — written against RM0383. | in progress |
| **[stm32-motor-controller](#)** | Closed-loop DC motor control: encoder input capture + PI loop running as FreeRTOS tasks at 1 kHz. | in progress |
| **[stm32-fault-forensics](#)** | Hard-fault handler that decodes the exception stack frame and reports the faulting PC over UART. | in progress |
| **[esp32-sumo-robot](#)** | Autonomous sumo robot — sensor reading, motor control, decision logic. | done |

<!-- Replace the (#) links with real repo URLs as each project ships.
     Each repo should have: a demo GIF/photo, wiring diagram, build/flash steps,
     and a "How it works" section explaining one non-obvious technical decision. -->

---

## JSRobotics (Robotics LMS Project)

Co-founder & CEO of **JSRobotics**, a project-based robotics & electronics education platform aimed at students in Uzbekistan — curriculum, product, and hands-on hardware mentoring. Long-term I'm building toward a hardware–software company at the intersection of firmware, embedded Linux, and robotics.

---

## 📍 Currently

-  Embedded Software Engineer intern — Inno Technopark Electronics Lab (STM32 firmware, CANSAT project)
-  Working through a self-directed bare-metal → FreeRTOS → embedded Linux roadmap
-  Targeting Summer 2027 embedded/firmware internships

---

## Connect
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/javokhir-tuychiyev/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:javokhir.tuychiyev16@gmail.com)

<!-- Replace your-handle and your-email above. -->

<!--
SETUP NOTE: To make this show on your GitHub profile, create a repository
named EXACTLY the same as your GitHub username (e.g. github.com/javohir/javohir),
make it public, and put this file in it as README.md.
-->
