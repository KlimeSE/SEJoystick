# Thrustmaster T16000M Joysticks Setup for Space Engineers

## Details

Designed for 2x T16000M joysticks (Thrustmaster)

## Steps

1. Download and install the TARGET GUI software from Thrustmaster: [TARGET_v3.0.21.910_rev1.exe](https://ts.thrustmaster.com/download/accessories/pc/hotas/software/TARGET/TARGET_v3.0.21.910_rev1.exe)

2. Download the [`SE.fcf`](./SE.fcf) file from this folder and put it somewhere convenient (Desktop, Documents etc)

3. Go to `C:\Program Files (x86)\Steam\steamapps\common\SpaceEngineers\Content\Data`

4. Make a copy of the `ControllerSchemas.sbc` and put it somewhere safe. You will need this to revert back from joystick mode

5. Delete the existing `ControllerSchemas.sbc` then download [`ControllerSchemas-Hosas.sbc`](./ControllerSchemas-Hosas.sbc) from this folder and put it in that folder

Setup is now complete. Here's how to run the joysticks:

1. Launch TARGET GUI, select "Run Configuration" in the top right, and select the [`SE.fcf`](./SE.fcf) file when prompted

2. Launch SE, navigate to Options -> Controls -> Select the Virtual Joystick (only needs to be done once)

3. 6DOF control should now be enabled

## Control List

LEFT STICK:
 - Joystick X: None
 - Joystick Y: Thrust forward / back
 - Joystick Z: Strafe left / right
 - Hat Up/Down: Ascend / Descend
 - Hat Left/Right: Strafe left / right
 
RIGHT STICK:
 - Joystick X: Roll left/right
 - Joystick Y: Pitch up/down
 - Joystick Z: Yaw left / right
 - Trigger: Left mouse click

## Extra

- If you lose your `ControllerSchemas.sbc` backup, delete the [`ControllerSchemas-Hosas.sbc`](./ControllerSchemas-Hosas.sbc) and verify local files on Steam
- The config can be edited in TARGET GUI including thrust curves