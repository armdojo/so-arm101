# Plug Wrist Camera (MF) Installation Guide for SO-100

<img height="300" src="https://github.com/user-attachments/assets/139be1c3-d446-4304-b0f4-c90a996789d6" />
<img height="300" src="https://github.com/user-attachments/assets/6c2f0f47-9663-4224-ac4e-220d1d71c162" />

## Overview
This guide provides step-by-step instructions for installing a **Wrist Camera** (alternate "McGartoll-Fung" design) on the SO-100 robot using a **Camera Module** and a 3D-printed **Plug-in Camera adapter**.

This an adapatation of [Wrist Camera (MF) UVC Module](../Wrist_Cam_Mount_32x32_UVC_Module/)

## Comparison to Main Design
#### Advantages:
- smaller
- fewer parts
- no additional screws/hardware needed to attach camera
- no removal/replacement of existing pieces
- easy removal/replacement

#### Disdvantages:
- still require to adapt to new camera

## Required Components
### Hardware:
- **USB Camera Module** (1) - for example the [ArmDojo 32 mm USB camera module](https://armdojo.com/products/usb-camera-module-1080p-wide-angle-lerobot?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=camera-mount), but any 32mm x 32mm USB camera module with min 720p / 30 fps spec will likely work
- [3D-printed Plugin camera attachment](stl/SO-ARM100_Plug_camera.stl) (1)
   - I recommend printing it as oriented in the STL using tree supports. 40% infill is recommended to increase sturdiness and avoid wobbling
- **M2 Screws** (8) - these are the smaller screws that came with your Feetech servos.


<img height="200" alt="Screenshot 2025-03-04 at 7 43 33 PM" src="https://github.com/user-attachments/assets/18099e1d-754c-4877-871f-9113a0dff062" />

## Assembly Instructions
### Step 1: Plug the new camera module to the Gripper
   
2. 3D print the **Plugin camera attachment**.

3. Attach the **Plugin camera attachment**.
    1. The hole fit into the [Gripper hole](../../STEP/Follower_specific/Moving_Jaw_08d%20v1.step)

4. Secure it with the M2 screws




### Step 2: Install the Camera
1. Take out the **Camera Module**.
2. Align the 4 holes of the **Camera Module** with the **Moving Jaw Replacement**, and attach using 4 **M2 Screws**.

<img height="300" src="https://github.com/user-attachments/assets/ea5af652-9311-44c7-8ae8-525f42cb4703" />


### Step 3: Configure Software and Adjust Focus
1. In your software, set your resolution and FPS. 
- **Note**: You will likely want to set your resolution to *640 x 480* and FPS to *30* even if the camera module's max resolution/frame rate is higher, as most models work with lower resolutions and any higher will just be data bloat.
2. Turn on your arm.  Look at the video feed from your newly installed camera (On Mac, you can also use *QuickTime*->*New Movie Recording* to see this feed).  
- **Note**: The focus on the camera is manual and will look very blurry initially. Adjust the focus by twisting the lens counterclockwise or clockwise until the video feed is clear.
