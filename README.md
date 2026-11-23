# Letter of Recommendations for Bao

For Professor Matthew Campisi.

## Schools List and Deadlines

| **School** | **Letter Deadline** | **Status** |
| --- | --- | --- |
| University of California, Los Angeles | December 31, 2026 | Not Requested by Program Yet |
| University of California, Berkeley | January 5, 2027 | Not Requested by Program Yet |
| Columbia University | January 14, 2027 | Not Requested by Program Yet |
| Northwestern University | January 14, 2027 | Not Requested by Program Yet |
| University of Michigan | January 14, 2027 | Not Requested by Program Yet |
| Carnegie Mellon University | January 14, 2027 | Not Requested by Program Yet |
| Cornell University | January 14, 2027 | Not Requested by Program Yet |
| Cornell Tech | January 14, 2027 | Not Requested by Program Yet |
| University of Pennsylvania | January 14, 2027 | Not Requested by Program Yet |

## What I Am Applying For and Why

I am applying to master's programs to deepen my understanding of embedded systems and strengthen my ability to design them. Digital signal processing would help me examine how filtering and recording conditions affect features extracted from recorded signals, while control theory would help me assess feedback stability under measurement delays. This training would build on my coursework and support my long-term goal of founding my own company to develop neural recording and analysis tools.

## Academic Performance

### My Courses with You

- Signals and Systems (ECE-UY 3054): A
- Introduction to Embedded Systems Design (ECE-UY 4144): A
- Real-Time Embedded Systems (ECE-GY 6483)
- Impact Innovation Lab (ECE-UY 4423)

### General

- Overall GPA: 3.677/4.000
- Advanced GPA (final 2 years): 3.896/4.000

## Resume

[View my resume (PDF)](Bao-Nguyen_resume.pdf)

## How You Know Me

### My Courses With You

- Signals and Systems (ECE-UY 3054): A
- Introduction to Embedded Systems Design (ECE-UY 4144): A
- Real-Time Embedded Systems (ECE-GY 6483)
- Impact Innovation Lab (ECE-UY 4423)

### Research

- Dorsal root ganglion signal processing research with Dr. Mammis.

### Projects

- Smart Watch personal project with the Seeed Studio XIAO nRF52840 Sense Plus.
- MaGlovin, a magnetic teleoperation glove, for Impact Innovation Lab (ECE-UY 4423).

## Specific Work You Have Seen Me Do

### Dorsal Root Ganglion Research

| **Timeline** | **My Contribution** | **Outcomes** |
| --- | --- | --- |
| October 2026 | **Research Initiation and Preliminary Investigation:**<br>Approached Dr. Mammis after his fireside chat and continued discussions that led to research with him, you, and Professor Davidson; began reviewing DRG recording and signal-processing questions. | • Established a research collaboration across neurosurgery and electrical engineering.<br>• Framed preliminary questions about DRG activity, recording methods, and potential pain biomarkers to guide subsequent technical preparation. |
| November 2026 | **Acquisition Requirements and Analog Front-End Research:**<br>Reviewed recording-source options and ADC, amplifier, and filter documentation to define an acquisition approach beginning with synthetic electrical inputs. | • Documented a proposed 8-channel, 18-bit acquisition baseline with gain and filtering requirements.<br>• Identified source-interface and analog headroom constraints before committing to circuit values or biological recording. |
| November 2026 | **Synthetic Signal Preparation and Measurement Planning:**<br>Prepared synthetic extracellular waveforms, documented WaveForms playback and attenuation settings, and checked sample reconstruction for planned Digilent Analog Discovery Studio bench tests. | • Prepared 10 repeatable waveform cases covering spikes, bursts, overlaps, noise, and interference.<br>• Verified numerical reconstruction and supplied event references for later acquisition testing and measurement. |

### Impact Innovation Lab

| **Timeline** | **My Contribution** | **Outcomes** |
| --- | --- | --- |
| October 2026 | **Problem Statement and Project Scope:**<br>Coordinated the team's research and synthesized it into a problem statement connecting limitations of hand-motion capture with the need for usable robot-training demonstrations. | • Established a shared problem definition for the team, connecting tracking errors to unreliable robot commands and demonstrations.<br>• Gave subsequent requirements and comparisons a common purpose. |
| October 2026 | **Requirement Specifications:**<br>Organized and ranked the team's requirements across sensing, safety, wearability, and data handling, incorporating the findings into the presentation. | • Produced a ranked set of 14 requirements for comparing design choices.<br>• Made safety priorities and unresolved performance targets explicit for team discussion and faculty review. |
| October 2026 | **Value Proposition and Pain-Point Analysis:**<br>Connected the proposed glove's capabilities to robotics laboratories' needs, examining occlusion, magnetic distortion, and fit or calibration effort. | • Linked 3 engineering pain points to proposed design responses.<br>• Focused the value proposition on usable robot-training demonstrations, giving the team specific benefits to investigate before claiming improvements. |
| October 2026 | **Competitive Landscape Analysis:**<br>Organized supplier research on glove, optical, and exoskeleton capture systems into comparisons of sensing, outputs, purchasing requirements, and SWOT findings. | • Compared 10 capture packages in the research dossier and condensed key alternatives into presentation tables.<br>• Separated hardware prices from licensing and integration costs, making incomplete quotations visible. |
| November 2026 | **Regulations and Standards:**<br>Synthesized candidate safety, exposure, and electromagnetic compatibility standards with regulatory research into proposed activity checks and a compliance plan for the laboratory prototype. | • Organized proposed checks around 3 activities: bench operation, powered wear, and external transfer.<br>• Gave the team a structured review plan, with unresolved approvals and test evidence visible. |

### Smart Watch

| **Timeline** | **My Contribution** | **Outcomes** |
| --- | --- | --- |
| December 2025 | **Soccer Watch Prototype on Adafruit Feather 32u4:**<br>Built the first version of the watch around soccer information, using JSON to represent its data. | • Displayed soccer information using JSON-formatted data on the Feather prototype.<br>• Established the initial version of the watch before the later XIAO redesign and custom protocol. |
| October 2026 | **XIAO Hardware Integration and Watch Interface:**<br>Moved to the Seeed Studio XIAO and Round Display, integrating an LVGL analog face, touch navigation, RTC timekeeping, and accelerometer thresholds for waking and dimming the display. | • Integrated 3 applications: Clock, Weather, and Calendar into the watch interface.<br>• Physically verified touch navigation and orientation-controlled dimming on hardware, using separate wake and dim thresholds. |
| October 2026 | **Custom Binary Data Protocol and Phone Relay:**<br>Developed the XWR format with Python encoding, allocation-free C++ parsing, CRC validation, and a PC-to-phone-to-watch relay using Bluetooth. | • Delivered 24 hourly forecasts and 7 daily summaries in a 192-byte weather message.<br>• Restored delivery after page reloads and reconnection without deleting the saved pairing. |
| November 2026 | **Additional Data Feeds and Background Updates:**<br>Integrated soccer, task, Google Calendar, astronomy, and desktop telemetry feeds with the watch interface and extended the relay for continuous background delivery. | • Made soccer scores, tasks, calendar events, astronomy, and desktop status available directly on the watch.<br>• Enabled continuous background updates across these 5 additional information categories. |

### Coursework

| **Timeline** | **My Contribution** | **Outcomes** |
| --- | --- | --- |
| October 2025 | **Temperature Controller Using Closed Loop Feedback System (ECE-UY 4144):**<br>Implemented register-level temperature acquisition, PWM damper control, and staged heating against a temperature setpoint. | • The controller code supports independent damper commands for 2 rooms using averaged temperature readings.<br>• Heating stages respond to setpoint error, linking sensor feedback to actuator commands. |
| November 2025 | **Interrupt-Driven Pressure Sensor Interface (ECE-UY 4144):**<br>Developed an I2C driver with completion interrupts, status validation, pressure conversion, and serial reporting. | • The driver converts 24-bit pressure readings into mmHg for serial reporting.<br>• It distinguishes valid measurements from sensor faults and I2C errors before displaying a pressure value. |
| December 2025 | **Parkinson's Disease Tremor Monitoring Prototype (ECE-UY 4144):**<br>Contributed to the team's accelerometer acquisition, FFT processing, and touchscreen movement-state display. | • The prototype code analyzes 3-second accelerometer recordings using an FFT.<br>• Its touchscreen interface presents dominant frequency and movement categories, making signal-processing output visible for demonstration and review. |
| December 2025 | **Course Completion (ECE-UY 3054):**<br>Analyzed LTI systems, convolution, transforms, sampling, and stability; implemented and compared MATLAB filters and impulse-response reconstructions. | • Earned A; learned to analyze LTI responses using convolution and Fourier, Laplace, and z transforms.<br>• Connected sampling, frequency response, and stability when reasoning about analog and digital systems. |
| December 2025 | **Course Completion (ECE-UY 4144):**<br>Applied microcontroller programming, timers, ADC, PWM, interrupts, and serial interfaces; helped integrate and debug a paired-controller UART system. | • Earned A; learned to configure microcontroller peripherals and connect analog sensors with digital control.<br>• Developed understanding of timers, interrupts, ADC, PWM, and serial communication for embedded systems integration. |
| October 2026 | **Biometric SoC Interface and Heart-Rate Averaging (ECE-GY 6483):**<br>Designed the interface specification and C++ acquisition driver, including ARM assembly averaging and transaction validation. | • The driver preserves accepted history when an acquisition fails, preventing partial measurements from entering the record.<br>• Assembly computes fractional heart-rate averages from the latest 10 successful acquisitions. |

## 3 Qualities I Hope You Will Highlight

### Project Leadership

- In MaGlovin, I organize team meetings, coordinate research, and delegate responsibilities across the project's required components.
  - This gives the team a recurring structure for assigning work and bringing individual contributions together for faculty review.
- I maintain the team's feedback loop and follow research contributions through to the presentations you see every two weeks.
  - This connects assigned work, feedback, and recurring deliverables, with my responsibility extending from coordinating the research to preparing it for review.

### Engineering and Research Initiative

- After the fireside chat with Dr. Mammis, I approached him about working together, exchanged contact information, and continued the conversations that led to the dorsal root ganglion research collaboration with him, you, and Professor Davidson.
  - I turned a personally meaningful interest into an active research relationship and an opportunity to contribute to an interdisciplinary investigation.
- I expanded my Smart Watch project beyond its original soccer display to learn more about embedded design, including how to integrate touch interfaces, sensor input, and Bluetooth communication. I developed a custom binary protocol with Python encoding and C++ parsing for the phone-to-watch relay.
  - This brought Clock, Weather, and Calendar into a working interface and enabled 24 hourly forecasts and seven daily summaries to reach the watch in a 192-byte message.
- I also started a personal microcontroller project to learn how processors, memory, and peripherals work together inside embedded devices.

### Technical Synthesis

- In MaGlovin, I organize teammates' findings and personally create the [presentation](https://www.figma.com/slides/c10xQFPdNY0VoMLJlYBMDC/MaGlovin), bringing the problem statement and 14 ranked requirements into a shared account of the project.
  - This makes the project's technical goals, priorities, and initial scope available for faculty and team review together.
- I bring research on six competing capture packages, the proposed value for robotics labs, and regulatory considerations into the same presentation.
  - This allows the proposed approach to be examined alongside existing alternatives, intended uses, and constraints, providing a common basis for technical discussion and feedback.
