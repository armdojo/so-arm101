> **ArmDojo SO-ARM101 kit — simulation model and design files.** This repository is ArmDojo's fork of the open-source SO-100 / SO-101 arm project (Apache-2.0, see [LICENSE](LICENSE)). The files are kept as in the original project.
> - **URDF / MuJoCo simulation model of the SO-101:** [`Simulation/SO101`](Simulation/SO101) — download everything with **Code → Download ZIP**.
> - **Kits, servos and spare parts:** [armdojo.com](https://armdojo.com/?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo) · [SO-ARM101 LeRobot kit](https://armdojo.com/products/so-arm101-lerobot-robot-arm-kit?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo)
> - **Tutorial videos & downloads:** [armdojo.com/pages/so-arm101-downloads](https://armdojo.com/pages/so-arm101-downloads?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo)
> - **Help:** info@armdojo.com · [ArmDojo Discord](https://discord.gg/MdyRuJVFAm)


## Video tutorials & downloads (ArmDojo SO-ARM101 kit)

- **16 step-by-step English videos:** software setup on Windows or Ubuntu, follower and leader arm assembly, cameras, wiring, servo IDs, calibration, teleoperation, dataset recording and training on a cloud GPU, plus the user manual and every download: [SO-ARM101 Tutorials & Downloads](https://armdojo.com/pages/so-arm101-downloads?utm_source=github&utm_medium=readme&utm_campaign=so-arm101-tutorials)
- **Written step-by-step version** with all 16 videos embedded: [SO-ARM101 setup tutorial](https://armdojo.com/blogs/guides/so-arm101-setup-video-tutorials-assembly-calibration-lerobot?utm_source=github&utm_medium=readme&utm_campaign=so-arm101-tutorials)
- **The kit used in the videos:** [SO-ARM101 LeRobot robot arm kit](https://armdojo.com/products/so-arm101-lerobot-robot-arm-kit?utm_source=github&utm_medium=readme&utm_campaign=so-arm101-tutorials)

<div align="center">

   <h1>Standard Open SO-100 & SO-101 Arms</h1>
   <div style="display: flex; gap: 1rem; justify-content: center; align-items: center;" >
   <img
      src="media/SO101_Follower.webp?raw=true"
      alt="SO-101 follower arm"
      title="SO-101 follower arm"
      style="width: 40%;"
    />
   <img
      src="media/SO101_Leader.webp?raw=true"
      alt="SO-101 leader arm"
      title="SO-101 leader arm"
      style="width: 40%;"
    />
</div>

<h2>
    <p>Build Your Own SO-101 Robot!</p>
</h2>

The SO‑101 is the next‑generation version of the SO‑100 robot arm, originally designed by the [RobotStudio](https://github.com/TheRobotStudio/SO-ARM100) in collaboration with [Hugging Face](https://huggingface.co/lerobot). It has improved wiring, is easier to assemble (no gear removal) and uses updated motors for the leader arm.

These arms are designed to work seamlessly with the open‑source 🤗 LeRobot library. Join the [ArmDojo Discord](https://discord.gg/MdyRuJVFAm) to collaborate on both hardware and software, and help make end‑to‑end AI for robotics more accessible.

</div>

### Documentation 📖
- For the SO‑101 docs, follow this page further.
- Here you can find the [SO‑100 docs](SO100.md) which is deprecated.

### Getting Your Own SO‑101 
You have two options:
- **Build it Yourself**
   - Source the components from the [Bill of Materials](#sourcing-parts).
   - 3D print the parts (or order the 3D printed parts), explained in [Printing the Parts](#printing-the-parts).
   - Follow our [Assembly Guide](https://huggingface.co/docs/lerobot/so101).
- **Buy a Kit**
   - Buy an assembled kit or a parts kit from ArmDojo, see [Kits](#kits).
   - Optionally follow our [Assembly Guide](https://huggingface.co/docs/lerobot/so101).

### Setup with LeRobot 🤗
After sourcing all parts you can setup your SO-101 with LeRobot [tutorial](https://huggingface.co/docs/lerobot/so101). 

### Optional Hardware 🔧
This repository also includes a range of optional hardware designs such as a raised leader base and different camera mounts. Here you can explore the [full list](#optional-hardware).


## Kits

SO-101 kits and parts kits from [ArmDojo](https://armdojo.com/?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=kits):

- [SO-ARM101 LeRobot robot arm kit](https://armdojo.com/products/so-arm101-lerobot-robot-arm-kit?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=kits): leader + follower arms, from a servo set or DIY kit up to assembled arms with wrist and overhead cameras (the kit used in our [video tutorials](https://armdojo.com/pages/so-arm101-downloads?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=kits))
- [SO-ARM101 First Training Kit](https://armdojo.com/products/so-arm101-first-training-kit?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=kits): the arm kit plus 100 colored wooden cubes and a tray for your first pick-and-place dataset
- [SO-101 DIY electronics kit, leader + follower](https://armdojo.com/products/so-101-diy-electronics-kit-feetech-leader-follower?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=kits): 12 Feetech STS3215 servos, 2 bus servo adapters, cables and clamps (print your own parts)
- [SO-101 single-arm electronics kit](https://armdojo.com/products/so-101-single-arm-electronics-kit-feetech?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=kits): 6 STS3215 servos + bus servo adapter + cables, follower (12 V) or leader (7.4 V)
- [SO-101 builder's pack (no servos)](https://armdojo.com/products/so-101-builders-pack-hardware-no-servos?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=kits) and [joint spares kit](https://armdojo.com/products/so-101-joint-spares-kit-horns-cables?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=kits): adapter board, metal horns, cables and clamps
- [LeRobot camera kit](https://armdojo.com/products/lerobot-camera-kit-wrist-overhead-usb-cameras?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=kits): wrist + overhead USB cameras for data collection

## Sourcing Parts

The follower and leader arm for this teleoperation setup use almost the same off-the-shelf parts (except for the motors). If you plan on creating the classic teleoperation setup to be used with the `LeRobot` library, get the Parts for Two Arms below. Every part in these tables is available from the [ArmDojo store](https://armdojo.com/?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom).

> [!IMPORTANT]  
> The STS3215 motors for the follower arm come in two versions. The 7.4V has a stall torque of 16.5kg.cm at 6V (and likely slightly less for a 5V power supply). The 12V version (C018) has a stall torque of 30kg.cm. While we found the 7.4V to be sufficient, if you would like more powerful motors you can get the [12V version](https://armdojo.com/products/feetech-sts3215-serial-bus-servo?variant=50758001230063&utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom). Note if you do this, you will also need a [12V 5A power supply](https://armdojo.com/products/servo-power-adapter-12v-5a-dc-5-5x2-1?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom) instead of a 5V one. The leader arm is always 7.4V for the SO101.

#### Parts For Two Arms (Follower and Leader Setup):

| Part | Amount | Buy |
| --- | --- | --- |
| STS3215 Servo 7.4V, 1/345 gear (C001) **<sup>[2](#leaderbundle)</sup> | 7 | [ArmDojo](https://armdojo.com/products/feetech-sts3215-serial-bus-servo?variant=50758001262831&utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom) |
| STS3215 Servo 7.4V, 1/191 gear (C044) **<sup>[2](#leaderbundle)</sup> | 2 | [ArmDojo](https://armdojo.com/products/feetech-sts3215-serial-bus-servo?variant=50758001295599&utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom) |
| STS3215 Servo 7.4V, 1/147 gear (C046) **<sup>[2](#leaderbundle)</sup> | 3 | [ArmDojo](https://armdojo.com/products/feetech-sts3215-serial-bus-servo?variant=50758001328367&utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom) |
| Motor Control Board (bus servo adapter) | 2 | [ArmDojo](https://armdojo.com/products/waveshare-bus-servo-adapter-board?variant=50874126893295&utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom) |
| USB-C Cable | 2 | [ArmDojo](https://armdojo.com/products/usb-a-to-usb-c-cable-6a-1m?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom) |
| Power Supply (adjustable, set to 5 V for 7.4V servos) | 2 | [ArmDojo](https://armdojo.com/products/servo-power-adapter-7-4v-8-4v-3a-dc-5-5x2-1?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom) |
| Table Clamp 4pcs | 1 | [ArmDojo](https://armdojo.com/products/g-clamps-heavy-duty-4-pack-robot-arm-mount?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom) |
| Screwdriver Set<sup>[1](#myfootnote1)</sup> | 1 | any precision set with Phillips #0 and #1 |

<a name="leaderbundle">2</a>: All six STS3215 servos needed for the SO-101 leader arm  
(3 × 1/147 gear (C046), 2 × 1/191 gear (C044), 1 × 1/345 gear (C001)) come as one [leader arm set](https://armdojo.com/products/so-101-single-arm-electronics-kit-feetech?variant=50885385781487&utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom), with the bus servo adapter and cables. For a 12V follower plus leader, the [SO-ARM101 12-servo set](https://armdojo.com/products/feetech-sts3215-serial-bus-servo?variant=50758001361135&utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom) has 6 × 12V C018 and the 6 leader servos.

#### Parts for One Follower Arm:

| Part | Amount | Buy |
| --- | --- | --- |
| STS3215 Servo 7.4V, 1/345 gear (C001) | 6 | [ArmDojo](https://armdojo.com/products/feetech-sts3215-serial-bus-servo?variant=50758001262831&utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom) |
| Motor Control Board (bus servo adapter) | 1 | [ArmDojo](https://armdojo.com/products/waveshare-bus-servo-adapter-board?variant=50874126958831&utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom) |
| USB-C Cable | 1 | [ArmDojo](https://armdojo.com/products/usb-a-to-usb-c-cable-6a-1m?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom) |
| Power Supply (adjustable, set to 5 V for 7.4V servos) | 1 | [ArmDojo](https://armdojo.com/products/servo-power-adapter-7-4v-8-4v-3a-dc-5-5x2-1?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom) |
| Table Clamp 2pcs | 1 | [ArmDojo](https://armdojo.com/products/g-clamps-heavy-duty-4-pack-robot-arm-mount?utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=bom) (4-pack) |
| Screwdriver Set<sup>[1](#myfootnote1)</sup> | 1 | any precision set with Phillips #0 and #1 |

<a name="myfootnote1">1</a>: You do not need to use this exact screwdriver set, but it is highly recommended to have phillips head screw driver sizes #0 and #1 for easiest screw installation and removal. These are both standard sizes which will likely appear in most small screwdriver sets.

## Printing the Parts

A variety of 3D printers are acceptable to print the parts necessary of the follower and leader arm. Follow the steps below to ensure a good print.

### Step 1: Choose a Printer
The STL files provided are ready to print on many FDM printers. Below are the tested and suggested settings though others may work.
   1. Material: PLA+
   2. Nozzle Diameter and Precision: 0.4mm nozzle diameter at 0.2mm layer height or 0.6mm nozzle at 0.4mm layer height.
   3. Infill Density: 15%
   4. Sample Printers: Prusa MINI+, UP Plus 2, Creality Ender 3, Bambu Lab A/P/X-series

### Step 2: Set up the Printer
   1. Ensure that the printer is calibrated and the bed level is correctly set using the printer specific instructions.
   2. Clean the print bed, making sure it is free from dust, or grease. If cleaning the bed using water, or other liquid, dry the bed.
   3. If your printer recommends it, use a standard glue stick and apply a thin, even layer of glue across the print area of the bed. Avoid clumping or uneven application.
   4. Load the printer filament using printer specific instructions.
   5. Ensure the printer settings match the ones suggested above (most printers have multiple settings so choose the ones that most closely match).
   6. Set for supports everywhere but ignore slopes greater than 45 degrees to the horizontal.
   7. There should be no supports in the screw holes with horizontal axes.
### Step 3: Check Printer Accuracy
   1. In the [Gauges](STL/Gauges) folder, there are two types of gauges, one to check the size of print against a standard 4x2 lego block and one against a STS3215 servo.
      1. If you have a STS3215 servo, print:
         1. [Gauge Zero](STL/Gauges/Gauge_0.STL)
         2. [Gauge Tight](STL/Gauges/Gauge_tight_1.STL)
      2. If you have a standard lego block, print:
         1. [Gauge Zero](STL/Gauges/Lego_Size_Test_02_zero.STL)
         2. [Gauge -0.1](STL/Gauges/Lego_Size_Test_02_minuspoint1.STL)
   2. Test the gauge 0 against your given object (Lego or Servo). The fit should be similar to this [tutorial](https://youtu.be/dss8E3DG2rA).
   3. If the fit is appropriate, go onto Step 4, otherwise, change your printer settings and try again or create an issue.
### Step 4: Print the Parts
All the parts for the leader or follower are for easy 3D printing already contained in a **single file**, correctly orientated for z upwards to minimize supports.
   1. For printer bed sizes of 220mmx220mm (such as the Ender), print these files:
      - [Follower](STL/SO101/Follower/Ender_Follower_SO101.stl)
      - [Leader](STL/SO101/Leader/Ender_Leader_SO101.stl)
   2. For printer bed sizes of 205mm x 250mm (such as the Prusa/Up):
      1. [Follower](STL/SO101/Follower/Prusa_Follower_SO101.stl)
      2. [Leader](STL/SO101/Leader/Prusa_Leader_SO101.stl)

This table contains all individual files:
<details>
<summary>Individual Part Files</summary>

#### Common Parts

| Part                                | Link                                                             |
|-------------------------------------|------------------------------------------------------------------|
| Base_motor_holder_SO101.stl         | [Base_motor_holder_SO101.stl](STL/SO101/Individual/Base_motor_holder_SO101.stl)       |
| Base_SO101.stl                      | [Base_SO101.stl](STL/SO101/Individual/Base_SO101.stl)                                 |
| Motor_holder_SO101_Base.stl         | [Motor_holder_SO101_Base.stl](STL/SO101/Individual/Motor_holder_SO101_Base.stl)       |
| Motor_holder_SO101_Wrist.stl        | [Motor_holder_SO101_Wrist.stl](STL/SO101/Individual/Motor_holder_SO101_Wrist.stl)     |
| Under_arm_SO101.stl                 | [Under_arm_SO101.stl](STL/SO101/Individual/Under_arm_SO101.stl)                       |
| Upper_arm_SO101.stl                 | [Upper_arm_SO101.stl](STL/SO101/Individual/Upper_arm_SO101.stl)                       |
| Rotation_Pitch_SO101.stl            | [Rotation_Pitch_SO101.stl](STL/SO101/Individual/Rotation_Pitch_SO101.stl)             |
| Wrist_Roll_Pitch_SO101.stl          | [Wrist_Roll_Pitch_SO101.stl](STL/SO101/Individual/Wrist_Roll_Pitch_SO101.stl)         |
| WaveShare_Mounting_Plate_SO101.stl  | [WaveShare_Mounting_Plate_SO101.stl](STL/SO101/Individual/WaveShare_Mounting_Plate_SO101.stl) |

#### Leader‑Specific Parts

| Part                  | Link                                     |
|-----------------------|------------------------------------------|
| Handle_SO101.stl      | [Handle_SO101.stl](STL/SO101/Individual/Handle_SO101.stl)     |
| Trigger_SO101.stl     | [Trigger_SO101.stl](STL/SO101/Individual/Trigger_SO101.stl)   |
| Wrist_Roll_SO101.stl  | [Wrist_Roll_SO101.stl](STL/SO101/Individual/Wrist_Roll_SO101.stl) |

#### Follower‑Specific Parts

| Part                            | Link                                                         |
|---------------------------------|--------------------------------------------------------------|
| Moving_Jaw_SO101.stl            | [Moving_Jaw_SO101.stl](STL/SO101/Individual/Moving_Jaw_SO101.stl)                 |
| Wrist_Roll_Follower_SO101.stl   | [Wrist_Roll_Follower_SO101.stl](STL/SO101/Individual/Wrist_Roll_Follower_SO101.stl) |
</details>

### Step 5: Remove Supports
   1. After the print is done, use a putty knife to scrape the the parts off the print bed.
   2. Remove any support material from parts.

### Don't Own a 3D printer?
Go here: [Printing services](./3DPRINT.md), or get the arms already assembled in the [SO-ARM101 kit](https://armdojo.com/products/so-arm101-lerobot-robot-arm-kit?variant=50757999755503&utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=3dprint).

## Optional Hardware
<!--Note: no hardware emoji here so links work correctly-->
Extend your SO‑100/SO‑101 with these add-ons.
<details>
<summary>Add‑ons</summary>

#### 1. Mount Helper  
Print the handy mount jig for easier alignment during assembly.  

[→ View README](Optional/Mount_Helper/README.md)

<img src="media/mount_helper.png" alt="Mount Helper" width="150">

#### 2. Overhead Camera Mount 

For bird’s‑eye views in single or bi‑manual setups.  
(SO100/101)

| Webcam  | 32×32 Cam Module |
|:---------------------:|:-------------------:|
<img src="https://github.com/user-attachments/assets/a652e133-8672-448d-baa0-bdd494a0a515" height="200"> | <img src="media/overhead_cam_two_followers.png" height="200"> 
| [Instructions](Optional/Overhead_Cam_Mount_Webcam/README.md) | [Instructions](Optional/Overhead_Cam_Mount_32x32_UVC_Module/README.md) 

#### 3. Base Mounts

| Raised Leader Base | 4040 Aluminum Profile Mount |
|:-------------------:|:---------------------------:|
<img src="media/Raised_Base.jpeg" height="150"> | <img src="media/4040_base_mount.jpg" height="150">  
[Download STL](Optional/Raised_Base/Raised_Base_Extension.stl) | [Instructions](Optional/4040_Base_Mount/README.md)

#### 4. Tactile Sensing (AnySkin)  
Add touch sensing to your gripper.  


<img src="media/tactile_sensor_anyskin.png" alt="AnySkin Sensor" width="150">


#### 5. Wrist‑Mount Cameras

| 32×32 UVC Hex Nut (SO101) | 32×32 UVC Integrated (SO100/101) | 32×32 UVC Plug‑on | RealSense D405 | RealSense D435/D435I | Webcam (Vinmooog) |
| --- | --- | --- | --- | --- | --- |
| <img src="media/UVC_cam_mount_so101.jpg" height="100"> | <img src="media/Wrist_Cam_Mount_32x32_UVC_module_1.jpg" height="100"> | <img src="media/UVC_cam_mount_plugin.jpg" height="100"> | <img src="media/d405_mount.jpg" height="100"> | <img src="media/d435_mount.jpg" height="100"> | <img src="media/cam_mount2.jpg" height="100"> |
| [Instructions](Optional/SO101_Wrist_Cam_Hex-Nut_Mount_32x32_UVC_Module) | [Instructions](Optional/Wrist_Cam_Mount_32x32_UVC_Module/README.md) | [Instructions](Optional/Wrist_Cam_Plug_Mount_32x32_UVC_Module) | [Instructions](Optional/Wrist_Cam_Mount_RealSense_D405) | [Instructions](Optional/Wrist_Cam_Mount_RealSense_D435) | [Instructions](Optional/Wrist_Cam_Mount_Vinmooog_Webcam) |



#### 6. Compliant Gripper
Add some flexibility to your gripper by downloading the compliant gripper parts and printing them using a flexible filament like TPU 95A. 

[→ View README](Optional/Compliant_Gripper/README.md). 

<img src="https://github.com/user-attachments/assets/26de0b8c-8bd6-4651-867f-1358532e2cc6" width="150">

</details>

## Debugging Motors
For debugging, any Windows PC can connect over USB to program the servos and to debug or do tests. To do so, use Feetech's FD debug software. For Ubuntu, you can use [FT_SCServo_Debug_Qt](https://github.com/Kotakku/FT_SCServo_Debug_Qt). Note: This step is not necessary as motors can be configured using the LeRobot Library, but this can be helpful for debugging.

