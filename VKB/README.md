# VKB Gladiator NXT EVO Joysticks Setup for Space Engineers

## Details

Designed for 2x VKB Gladiator NXT EVO Joysticks

## Setup

1. Download and install [vJoy](https://github.com/njz3/vJoy/releases/tag/v2.2.1.1)
2. Download and install [Joystick Gremlin](https://whitemagic.github.io/JoystickGremlin/download/)
3. Download the [`VKBControllerScheme.sbc`](./VKBControllerScheme.sbc) from this folder and put it in `C:\Program Files (x86)\Steam\steamapps\common\SpaceEngineers\Content\Data`
4. (Optional) Download the [`SETwoSticks.xml`](./SETwoSticks.xml) file from this folder (Joystick Gremlin config file)

## Launch

1. Launch vJoy and set the POV Hat Switch to Continuous and POVs to 4 - [Settings](https://i.imgur.com/FzUmlFc.png)
2. Launch Joystick Gremlin and load the [`SETwoSticks.xml`](./SETwoSticks.xml) config (optional). Otherwise, setup a custom config. Activate Joystick Gremlin (top left)
3. Launch Space Engineers and load into a world
4. Navigate to Options -> Controls -> Controller Selection (vJoy Device) -> Controller Scheme (GamepadScheme_FlightJoystick)
5. (Optional) Adjust the sensitivity and deadzone for a responsive feel - [Settings](https://i.imgur.com/bs58DVD.png)

## Notes

- The [`SETwoSticks.xml`](./SETwoSticks.xml) is personalized for a "HOTAS" feel. The left stick controls thrust and the right stick handles most rotation. Hold the left trigger to reverse thrust
- [`VKBControllerScheme.sbc`](./VKBControllerScheme.sbc) has flight controls and some menu controls, but can be expanded
- Ensure that the POV sticks are in joystick mode (red light on) for 6DOF control 
- Use the highest strength springs (30N) and minimal smoothing for the most responsive feel