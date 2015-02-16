# Quad Tuning Guide

### TLDR

1. Calibrate ESCs. See here.
2. Setup RC Controller. Mixers and subtrim on RC controller.
3. CG Balance. Get CG correct and balanced with the battery in position.
4. Default PIDS. Load default naze32 pids. 
5. Begin Rate Mode Tuning. This is gyro assisted only and must be done first.

### Step 1 - Calibrate ESCs

See here.

### Step 2 - Setup RC Controller

See here.

### Step 3 - CG Balance

CG must balance both in the roll and pitch movements. Take note of exactly where battery must be for multicopter to balance and ensure this is the position battery is in when you equip the quad.

### Step 4 - Default naze32 PIDs

Load default naze32 PIDs into the board. This can be done with a clean erase if you have already changed these (ensure you re-enable other settings if wiping). Default PIDs will allow to tune from a relatively clean slate.

### Step 5 - Begin Rate Mode Tuning

Always start with rate mode tuning as it doesn't use any sensors/functions other than the gyroscope. This allows us to isolate any issues with CG and RC mixer trims and get those locked in. 
  - Begin by calibrating the gyro using stick commands. 
  - Once done - arm the quad and slowly attempt to take off. Few things can happen -
    - if the quad banks to the left/right/forward/backwards - you have an issue with CG and/or RC trims.

