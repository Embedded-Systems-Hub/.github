<img width="1000" height="790" alt="image" src="https://github.com/Embedded-Systems-Hub/.github/blob/main/assets/embedded-systems-hub.png" />

<br>
<br>

---

This is the private GitHub organization of the **Embedded Systems Hub** community, focused on **real-world, project-driven embedded systems development**.

The repositories in this organization are designed to reflect **industry-level embedded software**, going beyond tutorials and simple examples.

---

<br>

## 🔐 Access

Access to this GitHub organization is **exclusive** to members of the Embedded Systems Hub community (Skool).

To get access:

1. [Join the Embedded Systems Hub waitlist](https://tally.so/r/wMo0BM)
2. You’ll be notified when the community opens.
3. After joining Embedded Systems Hub, you'll receive an **invitation to this GitHub organization**

Once inside, you’ll have access to all current and future repositories.

<br>

---

<br>
<br>

## What You’ll Find Inside

At the moment, this organization contains the following repositories:
- 🗺️ **[Embedded Roadmap Program](#embedded-roadmap-program)**
- 🤖 **[GitHub Actions CI/CD](#github-actions)**
- ⏱️ **[FreeRTOS](#freertos)**
- 🔥 **[Monthly Challenges](#monthly-challenges)**

<br>

<a id="embedded-roadmap-program"></a>
## 🗺️ Embedded Roadmap Program

**[Basic Level](https://github.com/Embedded-Systems-Hub/EMBEDDED-ROADMAP-Basic)**

<img width="500" height="630" alt="EMBEDDED-ROADMAP-Basic" src="https://github.com/Embedded-Systems-Hub/.github/blob/main/assets/embedded-roadmap-basic.png" />

<br>

Build a solid foundation and the right mindset in embedded systems development.  
Focus on bare-metal development, core embedded concepts and low-level peripheral access.

You’ll learn:
- Embedded systems fundamentals (MCU vs MPU, sensors, actuators)
- How to read datasheets and reference manuals
- Bare-metal peripheral configuration (GPIO, UART, ADC, Timers, Interrupts, I2C, SPI)
- The embedded build process, toolchain, and debugging basics
- Industry workflows and mindset (Git, Agile/SCRUM, V-cycle)

<br>

##

**[Advanced Level](https://github.com/Embedded-Systems-Hub/EMBEDDED-ROADMAP-Advanced)**

<img width="500" height="630" alt="EMBEDDED-ROADMAP-Advanced" src="https://github.com/Embedded-Systems-Hub/.github/blob/main/assets/embedded-roadmap-advanced.png" />

<br>

Move from “working code” to scalable and maintainable embedded software architectures.  
Focus on design decisions, modularity, and workflows used in real embedded projects.

You’ll learn:
- Performance, constraints, and design trade-offs in embedded systems
- Architecture vs microarchitecture and their impact on software design
- Modular firmware architecture and clean code organization
- State machines and control logic design
- Defensive programming and robust error handling
- Advanced peripherals and data handling (PWM, DMA)
- Professional tooling and workflows (CMake, Docker, CI/CD with GitHub Actions)

<br>

##

**[Expert Level](https://github.com/Embedded-Systems-Hub/EMBEDDED-ROADMAP-Expert)**

<img width="500" height="630" alt="EMBEDDED-ROADMAP-Expert" src="https://github.com/Embedded-Systems-Hub/.github/blob/main/assets/embedded-roadmap-expert.png" />

<br>

Master real-time, reliable, and production-grade embedded systems.
Focus on RTOS-based designs, fault tolerance, timing guarantees, power management, and industry-level quality practices.

You’ll learn:
- Real-time systems fundamentals (tasks, scheduling, priorities, WCET)
- RTOS-based designs and concurrency management
- Common RTOS pitfalls and synchronization mechanisms
- Reliability and safety patterns (watchdog, post-mortem reporting, reset analysis)
- Time-aware systems (RTC, timestamped logs and diagnostics)
- Power and energy management (low-power modes, standby, wake-up strategies)
- Embedded CI/CD pipelines and quality artefacts (unit tests, static analysis, documentation)
- Building firmware ready for long-term operation, maintenance, and delivery

<br>
<br>

<a id="github-actions"></a>
## 🤖 GitHub Actions CI/CD

**[GitHub Actions CI/CD](https://github.com/Embedded-Systems-Hub/my-cicd-project)**

<img width="500" height="1969" alt="GitHub-Actions" src="https://github.com/Embedded-Systems-Hub/.github/blob/main/assets/github-actions-cicd.png" />

<br>

Learn how to set up a **CI/CD system for embedded projects** using GitHub Actions.

**Course Structure:**
1. Introduction
2. CI Skeleton (Build + Artifacts)
3. Understanding ci.yml
4. Dockerized Builds
5. CMake Build System
6. Multi-Job Pipeline
7. Non-Blocking Jobs
8. Docker Hub Integration
9. Release Management & Versioning
10. Hardware Deployment (Self-Hosted Runner)

You’ll learn:
- GitHub Actions workflow fundamentals (triggers, jobs, steps, artifacts).
- Docker-based toolchains for reproducible builds.
- CMake build system for cross-compilation.
- Multi-job pipelines with code quality checks:
  - Style checking with clang-format.
  - Building with CMake + Ninja.
  - Static analysis with cppcheck.
  - Complexity analysis with Lizard.
  - Unit tests with CppUTest.
  - Coverage reporting with gcovr.
- Docker Hub integration with dynamic tagging and caching strategies.
- Non-blocking jobs for flexible CI during development.
- Release management with SemVer (Semantic Versioning) and automated GitHub releases.
- Hardware deployment using self-hosted runners (complete CI/CD).
- Professional embedded software delivery workflows.

<br>
<br>

<a id="freertos"></a>
## ⏱️ FreeRTOS - Available January 2026

<img width="500" height="630" alt="FreeRTOS" src="https://github.com/Embedded-Systems-Hub/.github/blob/main/assets/freertos.png" />

<br>

Learn how to build **real-time embedded systems** using **FreeRTOS**.

You’ll learn:
- Real-time concepts
- FreeRTOS kernel fundamentals
- Task design: priorities, scheduling, stack sizing
- Inter-task communication (queues, semaphores, mutexes, event groups)
- Time management (tick, delays, software timers)
- Memory management and heap strategies
- Common RTOS issues (race conditions, priority inversion, deadlocks)
- Debugging and tracing RTOS-based systems

<br>
<br>

<a id="monthly-challenges"></a>
## 🔥 Monthly Challenges

Monthly, hands-on challenges designed to **learn by doing** and grow together as embedded engineers.

Each challenge:
- Focuses on a practical, industry-relevant skill
- Can be completed without special hardware whenever possible
- Encourages sharing solutions, approaches and questions
- Includes a follow-up explanation and discussion

The goal is to get **hands-on with useful embedded technologies**, explore different approaches and learn from each other.

**Current challenges:**
- **[Challenge #1 - QEMU & Debugging](https://github.com/Embedded-Systems-Hub/Challenges/tree/main/ch001-qemu-stm32vldiscovery-uart):** Emulation-based development and debugging workflows
- **[Challenge #2 - Sections & Memory Layout](https://github.com/Embedded-Systems-Hub/Challenges/tree/main/ch002-sections-memory-layout):** Understanding binaries, linker outputs, and memory organization
- **[Challenge #3 - FreeRTOS Tasks](https://github.com/Embedded-Systems-Hub/Challenges/tree/main/ch003-FreeRTOS-tasks):** FreeRTOS task creation, priorities, scheduling behavior, and real-time analysis using SEGGER SystemView

<br>
<br>

<img width="1000" height="313" alt="Embedded Systems Hub (3)" src="https://github.com/Embedded-Systems-Hub/.github/blob/main/assets/embedded-systems-hub-banner.png" />
