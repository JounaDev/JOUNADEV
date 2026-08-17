<!-- ============================================================
     NEPTUNO CORE
     JounaDev — Embedded Systems / C++ / Arduino
     
     Visual identity:
     NeoGlass × Industrial × Rock × Embedded Engineering
     ============================================================ -->

<!-- ╔══════════════════════════════════════════════════════════╗
     ║                         HERO                             ║
     ╚══════════════════════════════════════════════════════════╝ -->

<p align="center">
  <img
    src="https://raw.githubusercontent.com/JounaDev/JOUNADEV/main/descarga.png"
    width="100%"
    height="300"
    alt="NEPTUNO CORE — Embedded Systems"
  />
</p>

<p align="center">

<img
 src="https://img.shields.io/badge/NEPTUNO_CORE-00BFFF?style=for-the-badge&logo=arduino&logoColor=white"
 alt="Neptuno Core"
/>

</p>

<h1 align="center">
  NEPTUNO CORE
</h1>

<p align="center">
  <strong>Embedded Systems Architecture</strong>
</p>

<p align="center">
  C++ · Arduino · PlatformIO · State Machines · Hardware Control
</p>

<p align="center">

  <img src="https://img.shields.io/badge/SYSTEM-ONLINE-00BFFF?style=flat-square" />
  <img src="https://img.shields.io/badge/KERNEL-ACTIVE-00BFFF?style=flat-square" />
  <img src="https://img.shields.io/badge/STATE_MACHINE-READY-00BFFF?style=flat-square" />
  <img src="https://img.shields.io/badge/HARDWARE-SYNCED-00BFFF?style=flat-square" />

</p>

<br>

<!-- ROCK DECALS -->

<p align="center">

  <img src="https://img.shields.io/badge/⚡_BUILD-00BFFF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/★_ROCK_R%26D-111820?style=for-the-badge&labelColor=05070A" />
  <img src="https://img.shields.io/badge/⚙_HARDWARE-00BFFF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/☠_DEBUG-111820?style=for-the-badge&labelColor=05070A" />

</p>

> **NEPTUNO CORE** is a personal embedded-systems architecture focused on deterministic execution, explicit machine states, hardware control and maintainable firmware.

---

# `01` · SYSTEM INFORMATION

<p align="center">

| SYSTEM           | STATUS          |
| :--------------- | :-------------- |
| **Name**         | `NEPTUNO CORE`  |
| **Developer**    | `JounaDev`      |
| **Status**       | `ONLINE`        |
| **Kernel**       | `1.x`           |
| **Architecture** | `State Machine` |
| **Execution**    | `Deterministic` |
| **Lifecycle**    | `Managed`       |

</p>

```yaml
system:
  name: NEPTUNO CORE
  developer: JounaDev
  status: ONLINE

kernel:
  version: 1.x
  architecture: State Machine
  execution: Deterministic
  lifecycle: Managed

software:
  language: C++
  framework: Arduino
  build_system: PlatformIO

hardware:
  target: Microcontrollers
  communication:
    - Digital I/O
    - Serial
  control: Real-Time

engineering:
  architecture: Layered
  philosophy: Hardware + Software
  priority:
    - Predictability
    - Modularity
    - Reliability
    - Maintainability

interface:
  visual_system: NeoGlass
  accent: Electric Cyan
  secondary_style: Industrial Rock
  environment: Dark
```

<p align="center">

  <img src="https://img.shields.io/badge/NEOGLASS-05070A?style=flat-square" />
  <img src="https://img.shields.io/badge/ELECTRIC_CYAN-00BFFF?style=flat-square" />
  <img src="https://img.shields.io/badge/INDUSTRIAL_R%26D-111820?style=flat-square" />
  <img src="https://img.shields.io/badge/EMBEDDED-00BFFF?style=flat-square" />

</p>

---

# `02` · CORE MODULES

<p align="center">

<img
src="https://skillicons.dev/icons?i=cpp,arduino,linux,git,github,vscode,bash"
alt="Core technologies"
/>

</p>

<p align="center">
  <sub>
    C++ · Arduino · PlatformIO · Linux · Git · GitHub · VS Code · Bash
  </sub>
</p>

<br>

```text
┌──────────────────────────────────────────────────────────────┐
│                         CORE TOOLCHAIN                       │
├──────────────────────────────────────────────────────────────┤
│                                                              │
│  LANGUAGE        C++                                         │
│  PLATFORM        Arduino / Microcontrollers                  │
│  BUILD           PlatformIO                                  │
│  VERSIONING      Git / GitHub                                │
│  DEVELOPMENT     VS Code                                     │
│  ENVIRONMENT     Linux / Bash                                │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

---

# `03` · ENGINEERING MODEL

NEPTUNO CORE follows a deterministic event-processing model.

```text
┌──────────────────────────────────────────────────────────────┐
│                      NEPTUNO CORE                            │
├──────────────────────────────────────────────────────────────┤
│                                                              │
│   INPUT              PROCESS              OUTPUT             │
│     │                   │                   │                │
│     ▼                   ▼                   ▼                │
│  ┌───────┐          ┌─────────┐         ┌──────────┐         │
│  │Sensor │ ───────► │ Kernel  │ ──────► │Actuator  │         │
│  └───────┘          └────┬────┘         └──────────┘         │
│                           │                                  │
│                           ▼                                  │
│                    ┌─────────────┐                           │
│                    │ State Model │                           │
│                    └─────────────┘                           │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

### Design Principle

```text
Hardware generates events.

Software interprets events.

The state machine determines behavior.

The hardware executes the resulting action.
```

The objective is to keep system behavior:

```text
EXPLICIT
TESTABLE
PREDICTABLE
RECOVERABLE
MAINTAINABLE
```

<p align="center">

  <img src="https://img.shields.io/badge/EXPLICIT-00BFFF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PREDICTABLE-00BFFF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MODULAR-00BFFF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RECOVERABLE-00BFFF?style=for-the-badge" />

</p>

---

# `04` · CORE ARCHITECTURE

## Machine State Model

```cpp
enum class SystemState {

    OFF,
    BOOT,
    STANDBY,
    ACTIVE,
    RESET

};
```

## Kernel Interface

```cpp
class Kernel {

public:

    void boot();
    void shutdown();
    void standby();
    void reset();

private:

    SystemState state;

};
```

---

## State Lifecycle

```text
                         ┌──────────────┐
                         │     OFF      │
                         └──────┬───────┘
                                │
                                ▼
                         ┌──────────────┐
                         │     BOOT     │
                         └──────┬───────┘
                                │
                                ▼
                      ┌──────────────────┐
                      │     STANDBY      │
                      └────────┬─────────┘
                               │
                               ▼
                         ┌──────────────┐
                         │    ACTIVE    │
                         └──────┬───────┘
                                │
                         fault / reset
                                │
                                ▼
                         ┌──────────────┐
                         │     RESET    │
                         └──────┬───────┘
                                │
                                └──────────────► BOOT
```

---

# `05` · SYSTEM PIPELINE

```text
┌──────────────┐
│   HARDWARE   │
└──────┬───────┘
       │
       │ Events
       ▼
┌──────────────┐
│    INPUT     │
│    LAYER     │
└──────┬───────┘
       │
       │ Normalized data
       ▼
┌──────────────┐
│    KERNEL    │
│    ENGINE    │
└──────┬───────┘
       │
       │ State transition
       ▼
┌──────────────┐
│    STATE     │
│    MACHINE   │
└──────┬───────┘
       │
       │ Command
       ▼
┌──────────────┐
│    OUTPUT    │
│    LAYER     │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│   ACTUATORS  │
└──────────────┘
```

---

# `06` · SYSTEM BOOT

```text
NEPTUNO CORE :: BOOT SEQUENCE
────────────────────────────────────────

[ 01 ] Initializing kernel.............. OK
[ 02 ] Loading system modules.......... OK
[ 03 ] Synchronizing hardware.......... OK
[ 04 ] Validating power states......... OK
[ 05 ] Initializing state machine...... OK
[ 06 ] Checking system integrity....... OK
[ 07 ] Mounting runtime................ OK
[ 08 ] Starting control loop............ OK

────────────────────────────────────────

KERNEL      :: ONLINE
HARDWARE    :: SYNCHRONIZED
STATE       :: STANDBY
CONTROL     :: READY
SYSTEM      :: OPERATIONAL
```

<p align="center">

<img src="https://img.shields.io/badge/BOOT-OK-00BFFF?style=for-the-badge" />
<img src="https://img.shields.io/badge/HARDWARE-SYNCED-00BFFF?style=for-the-badge" />
<img src="https://img.shields.io/badge/KERNEL-ONLINE-00BFFF?style=for-the-badge" />

</p>

---

# `07` · SYSTEM LAYERS

```text
┌──────────────────────────────────────────┐
│              APPLICATION                 │
├──────────────────────────────────────────┤
│             STATE MACHINE                │
├──────────────────────────────────────────┤
│                KERNEL                    │
├──────────────────────────────────────────┤
│        HARDWARE ABSTRACTION              │
├──────────────────────────────────────────┤
│                DRIVERS                   │
├──────────────────────────────────────────┤
│                HARDWARE                  │
└──────────────────────────────────────────┘
```

```text
APPLICATION
     │
     ▼
STATE MACHINE
     │
     ▼
KERNEL
     │
     ▼
HARDWARE ABSTRACTION
     │
     ▼
DRIVERS
     │
     ▼
HARDWARE
```

This separation keeps hardware-dependent behavior isolated from higher-level system logic.

---

# `08` · SYSTEM COMPONENTS

| Component      | Responsibility                        |
| :------------- | :------------------------------------ |
| `Kernel`       | System lifecycle and orchestration    |
| `SystemState`  | Explicit machine-state representation |
| `Boot`         | Initialization and validation         |
| `Standby`      | Safe idle operating state             |
| `Active`       | Primary execution state               |
| `Reset`        | Recovery and controlled restart       |
| `Hardware`     | Physical system interface             |
| `Sensors`      | External event acquisition            |
| `Actuators`    | Physical system output                |
| `Control Loop` | Continuous runtime execution          |

---

# `09` · TECHNOLOGY ARCHITECTURE

```text
                         NEPTUNO CORE
                              │
             ┌────────────────┼────────────────┐
             │                │                │
             ▼                ▼                ▼
           C++             ARDUINO          PLATFORMIO
             │                │                │
             └────────────────┼────────────────┘
                              │
                              ▼
                     EMBEDDED RUNTIME
                              │
                              ▼
                       KERNEL ENGINE
                              │
                              ▼
                       STATE MACHINE
                              │
                  ┌───────────┴───────────┐
                  │                       │
                  ▼                       ▼
               SENSORS                ACTUATORS
                  │                       │
                  └───────────┬───────────┘
                              │
                              ▼
                           HARDWARE
```

---

# `10` · HARDWARE / SOFTWARE CONTRACT

```text
┌──────────────────── SOFTWARE ────────────────────┐
│                                                  │
│  STATE          LOGIC          CONTROL           │
│    │              │               │              │
│    └──────────────┼───────────────┘              │
│                   │                              │
└───────────────────┼──────────────────────────────┘
                    │
                    │ COMMAND
                    ▼
┌──────────────────── HARDWARE ────────────────────┐
│                                                  │
│  INPUTS         MCU / BUS         OUTPUTS       │
│                                                  │
│  SENSORS  ───►  PROCESSING  ───►  ACTUATORS     │
│                                                  │
└──────────────────────────────────────────────────┘
```

---

# `11` · REPOSITORIES

<p align="center">

<a href="https://github.com/JounaDev/NeptunoCore">
<img
  src="https://img.shields.io/badge/NEPTUNO_CORE-00BFFF?style=for-the-badge&logo=github&logoColor=white"
  alt="Neptuno Core"
/>
</a>

<a href="https://github.com/JounaDev">
<img
  src="https://img.shields.io/badge/GITHUB_PROFILE-111820?style=for-the-badge&logo=github&logoColor=white"
  alt="GitHub Profile"
/>
</a>

<a href="https://github.com/JounaDev?tab=repositories">
<img
  src="https://img.shields.io/badge/ALL_PROJECTS-111820?style=for-the-badge&logo=github&logoColor=white"
  alt="All Projects"
/>
</a>

<a href="https://jounadev.github.io/">
<img
  src="https://img.shields.io/badge/PORTFOLIO-00BFFF?style=for-the-badge&logo=googlechrome&logoColor=white"
  alt="Portfolio"
/>
</a>

</p>

---

# `12` · GITHUB METRICS

<p align="center">

<img
height="180"
src="https://github-readme-stats.vercel.app/api?username=JounaDev&show_icons=true&hide_border=true&theme=transparent&bg_color=0D1117&title_color=00BFFF&icon_color=00BFFF&text_color=8B949E"
alt="GitHub Statistics"
/>

<img
height="180"
src="https://github-readme-stats.vercel.app/api/top-langs/?username=JounaDev&layout=compact&hide_border=true&theme=transparent&bg_color=0D1117&title_color=00BFFF&text_color=8B949E"
alt="Top Languages"
/>

</p>

---

# `13` · SYSTEM TELEMETRY

```text
┌──────────────────────────────────────────────────────────────┐
│                     SYSTEM TELEMETRY                         │
├──────────────────────────────────────────────────────────────┤
│                                                              │
│  KERNEL            ████████████████████  ONLINE              │
│  HARDWARE          ████████████████████  SYNCED              │
│  STATE MACHINE     ████████████████████  READY               │
│  I/O SUBSYSTEM     ████████████████████  READY               │
│  CONTROL LOOP      ████████████████████  ACTIVE              │
│                                                              │
├──────────────────────────────────────────────────────────────┤
│  SYSTEM HEALTH                                     100%      │
└──────────────────────────────────────────────────────────────┘
```

<p align="center">

<img src="https://img.shields.io/badge/KERNEL-ONLINE-00BFFF?style=flat-square" />
<img src="https://img.shields.io/badge/HARDWARE-SYNCED-00BFFF?style=flat-square" />
<img src="https://img.shields.io/badge/I%2FO-READY-00BFFF?style=flat-square" />
<img src="https://img.shields.io/badge/CONTROL-ACTIVE-00BFFF?style=flat-square" />

</p>

---

# `14` · OPERATIONAL STATUS

```diff
+ Kernel initialized
+ Hardware synchronized
+ State machine loaded
+ I/O subsystem ready
+ Control loop active
+ Recovery path available
+ NEPTUNO CORE operational
```

<p align="center">

### `SYSTEM :: OPERATIONAL`

</p>

---

# `15` · ENGINEERING PRINCIPLES

```text
01  Deterministic execution
02  Explicit state transitions
03  Hardware-aware design
04  Modular system boundaries
05  Predictable failure handling
06  Maintainable firmware
07  Clear separation of responsibilities
```

<p align="center">

<img src="https://img.shields.io/badge/01-DETERMINISTIC-00BFFF?style=flat-square" />
<img src="https://img.shields.io/badge/02-STATEFUL-00BFFF?style=flat-square" />
<img src="https://img.shields.io/badge/03-HARDWARE_AWARE-00BFFF?style=flat-square" />
<img src="https://img.shields.io/badge/04-MODULAR-00BFFF?style=flat-square" />

</p>

---

# `16` · ROCK / R&D DECALS

<p align="center">

<img src="https://img.shields.io/badge/⚡_BUILD_HARD-00BFFF?style=for-the-badge&labelColor=05070A" />
<img src="https://img.shields.io/badge/★_ROCK%20%2F%20R%26D-FFFFFF?style=for-the-badge&labelColor=111820" />
<img src="https://img.shields.io/badge/☠_DEBUG_FIRST-FFFFFF?style=for-the-badge&labelColor=111820" />

</p>

<p align="center">

<img src="https://img.shields.io/badge/C%2B%2B-ENGINEERING-00BFFF?style=for-the-badge&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/HARDWARE-NO_SHORTCUTS-00BFFF?style=for-the-badge" />

</p>

```text
       ╭──────────────────────────────────────────────╮
       │                                              │
       │       NEPTUNO // HARDWARE R&D               │
       │                                              │
       │       BUILD  ·  TEST  ·  DEBUG  ·  REPEAT   │
       │                                              │
       ╰──────────────────────────────────────────────╯
```

---

# `17` · FINAL DIRECTIVE

```text
NEPTUNO CORE
────────────────────────────────────────

ENGINEER THE STATE.
CONTROL THE SYSTEM.
RESPECT THE HARDWARE.

Deterministic firmware.
Explicit transitions.
Hardware-aware architecture.
```

<p align="center">

<img
 src="https://img.shields.io/badge/NEPTUNO_CORE-ONLINE-00BFFF?style=for-the-badge"
 alt="Neptuno Core Online"
/>

</p>

---

<p align="center">

<img
 src="https://capsule-render.vercel.app/api?type=waving&color=0:05070A,45:071923,75:003B5C,100:00BFFF&height=160&section=footer"
 width="100%"
 alt="NEPTUNO CORE footer"
/>

</p>

<p align="center">

  <sub>
    NEPTUNO CORE · Embedded Systems Architecture · JounaDev
  </sub>

</p>

<p align="center">
  <sub>
    C++ · Arduino · PlatformIO · Hardware Control · State Machines
  </sub>
</p>
