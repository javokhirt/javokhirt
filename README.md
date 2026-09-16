# Javokhir Tuychiyev

Embedded software engineer. Register-level firmware written from datasheets and
reference manuals, no vendor HAL — with the evidence kept: logic analyzer
captures, unit tests in CI, and writeups of what broke.


## Where to look

**[sentinel-node](https://github.com/javokhirt/sentinel-node)** — A bare-metal STM32F411 environmental sensor node: I2C master and SHT3x
drivers written from RM0383 and the sensor datasheet. Every reading is
CRC-verified — 1,320 readings over 22 minutes, zero failures, captured off the
wire with a Saleae. Host-compiled unit tests run in CI on every push. The docs
include a build log, design decisions, and bug hunts — including an ACK race on
the last byte of an I2C read, caught in the reference manual before it ever ran.
If you want to know how I debug, start with the bug hunts.

**[stm32-bare-metal](https://github.com/javokhirt/stm32-bare-metal)** — My peripheral drivers. Fourteen self-contained projects from raw GPIO register writes to timer
output-compare. No HAL, no CubeMX.

Sentinel-node is the sensor layer of [Rovion Controls](https://www.rovioncontrols.com/en),
an agritech company I'm building. The firmware I've written in industry — STM32
work at an electronics laboratory in Tashkent, including a CANSAT program — is
private IP, so everything public here is built from scratch, in the open.

## How I work

Read the manual before writing the code. Split drivers so the logic compiles on
the host and gets tested there. When something breaks, capture it on the wire
and write down what happened.

## Stack

C on ARM Cortex-M (STM32F4). `arm-none-eabi-gcc`, Make, OpenOCD, GDB over SWD —
terminal only, no IDE. Saleae for anything on a bus. Unity tests on the host,
run in GitHub Actions.

## Now

- **Open to Summer 2027 embedded software / firmware internships.**
- CS student at Penn State.
- Next on sentinel-node: FreeRTOS with sensor and radio tasks, a register-level
  SX126x-family LoRa driver, then a custom PCB.

## Contact

[LinkedIn](https://www.linkedin.com/in/javokhir-tuychiyev/) ·
javokhir.tuychiyev16@gmail.com
