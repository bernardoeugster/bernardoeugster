# Bernardo Eugster

Electrical Engineering student at ETH Zurich with a strong interest in embedded systems, electronics, robotics, and real-world engineering projects.

I enjoy building technical systems where software, hardware, mechanics, and practical constraints meet. My projects usually involve debugging, prototyping, soldering, repair, documentation, and iterative improvement until a system works reliably in a real environment.

## ⚡ Focus

- Embedded systems
- Electronics and circuit debugging
- Hardware/software integration
- Low-power systems
- Prototyping and repair
- Practical system integration
- Technical documentation of real engineering decisions

## 🔧 Selected Work

### [TeleBell - ESP32 Telegram Doorbell Receiver](https://github.com/bernardoeugster/TeleBell)

ESP32-based indoor doorbell receiver with Telegram control, role-based access, Wi-Fi setup portal, persistent configuration, WAV voice prompts, presence mode, and I2S audio output through a MAX98357A amplifier and speaker.

<details>
<summary>What this project demonstrates</summary>

- ESP32 firmware development for a practical home retrofit system
- Telegram bot integration with reply-keyboard menus
- remote doorbell triggering through a custom Telegram interface
- role-based access control with owner, admin, user, and unknown-user handling
- invite-based onboarding and pending access requests
- anti-spam protection with cooldowns and escalating timeouts
- configurable volume, repeat count, mute state, and doorbell melodies
- multilingual Telegram interface with English, German, and Spanish messages
- local Wi-Fi setup portal for configuration and recovery
- persistent configuration storage using ESP32 Preferences/NVS and LittleFS
- WAV voice prompts and optional presence-simulation audio
- I2S audio output using a MAX98357A amplifier and 4 ohm speaker
- 3D-printed enclosure design with mechanical and acoustic considerations
- replacement of an unreliable vibration-sender concept with a simpler receiver-only architecture
- reliability-driven engineering decisions under real deployment constraints

</details>

### [ESPSECCAM - ESP32-CAM Security Camera](https://github.com/bernardoeugster/espseccam)

Battery-powered ESP32-CAM security camera with Telegram control, PIR motion detection, deep sleep, Wi-Fi setup portal, role-based access control, persistent configuration, sunrise/sunset-based flash control, and a custom 3D-printed enclosure.

<details>
<summary>What this project demonstrates</summary>

- ESP32-CAM firmware development
- Telegram bot integration for remote control and image delivery
- multilingual Telegram user interface with English, German, and Spanish messages
- PIR-based motion detection and wakeup from deep sleep
- power-aware operation with scheduled online windows
- runtime Wi-Fi and user configuration through a local setup portal
- role-based Telegram access control with command, notify, and audit users
- sunrise/sunset-based automatic flash control
- persistent configuration storage using ESP32 Preferences/NVS
- stripboard-based hardware integration
- 3D-printed enclosure design with Mark I, Mark II, and Mark III design iterations
- practical engineering trade-offs between reliability, assembly effort, and available hardware

</details>

### [Sony WH-1000XM4 ANC Repair](https://github.com/bernardoeugster/sony-wh1000xm4-anc-repair)

Diagnosis and repair of unstable ANC behavior in Sony WH-1000XM4 headphones.

<details>
<summary>What this project demonstrates</summary>

- structured fault diagnosis
- datasheet-based component selection
- precision soldering
- technical documentation
- practical troubleshooting in a mixed analog-digital consumer device
- repair-oriented engineering instead of simple part replacement

</details>

## How I Work

I like projects that combine structured engineering thinking with hands-on implementation.

That usually means understanding the problem, building a first prototype, testing it, finding weak points, improving the design, and documenting the result clearly. I try to show not only the final result, but also the engineering decisions, failed approaches, trade-offs, and reliability improvements that led there.

I am especially interested in embedded and system integration work where code, electronics, mechanical design, and real-world constraints all matter.

## Contact

Project-related questions are best handled through GitHub Issues.

For professional contact, you can reach me on [LinkedIn](https://www.linkedin.com/in/bernardo-eugster-42aab3340/).
