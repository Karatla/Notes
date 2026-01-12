How EMBEDDED fits into the same 12 months (correct version)

Here is the correct, realistic combined roadmap.

Months 1–2 — Embedded foundation (STM32)

THIS was missing before

You learn:

GPIO, PWM

servo / motor control

encoder reading

IMU (I2C)

UART to PC

timer-based control loop

👉 Outcome:

STM32 controls a joint safely and reports position.

This corresponds to real jobs titled:

Embedded Software Engineer

Controls Engineer

Firmware Engineer

Months 3–4 — Vision on PC (parallel)

Now you add:

OpenCV

YOLO

camera input

send commands to STM32

👉 Outcome:

Camera → PC → STM32 → motor moves

This is vision-to-motion integration.

Months 5–6 — ROS2 integration (NOT motor control)

ROS2 now:

sends high-level commands

does NOT touch motors directly

You learn:

ROS2 nodes & topics

hardware interface concepts

simulation

👉 Outcome:

ROS2 tells STM32 what, STM32 decides how.

Months 7–8 — Manipulation (split responsibility)

MoveIt plans motion (PC)

STM32 executes joint control

You learn:

motion planning (PC)

trajectory following (STM32)

👉 Outcome:

Robot arm moves smoothly & safely.

Months 9–10 — Humanoid simulation (control logic split)

Simulation replaces hardware

Same logic split still applies

STM32 logic → simulated controller
ROS2 logic → autonomy layer

Months 11–12 — Portfolio (THIS is where jobs connect)

You present projects as:

“I built a robotic joint controller (STM32) and integrated it with perception and ROS2 autonomy.”

That is exactly how companies describe the role, even if the title is generic.
