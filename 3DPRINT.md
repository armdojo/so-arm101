# 3D Printing Services

No printer? There are two ways to get the printed parts:

- **Order prints from a 3D printing service.** Any online or local FDM printing service can make these parts from the STL files in this repository.
- **Get the arms already assembled.** The Starter, Standard and Advanced versions of the [SO-ARM101 LeRobot kit](https://armdojo.com/products/so-arm101-lerobot-robot-arm-kit?variant=50757999755503&utm_source=github&utm_medium=referral&utm_campaign=so-arm101-repo&utm_content=3dprint) come with assembled leader and follower arms.

### What to order from a printing service

- Upload the individual part files from `STL/SO101/Individual/`. There are 14 distinct parts (9 shared parts plus the leader- and follower-specific parts). See the [Individual Part Files](README.md#step-4-print-the-parts) table in the README for the full breakdown.
- **Do not** upload `SO101 Assembly.stl`. It is a reference model of the whole arm, not a printable part.
- Upload only **one** mounting plate, `WaveShare_Mounting_Plate_SO101.stl` **or** `Seeedstudio_Mounting_Plate_SO101.stl`, matching your servo driver board.
- The 9 shared parts are used on **both** arms, so set their quantity to **2** if you are building a leader + follower pair.
- Services that print from all-in-one plates can use `STL/SO101/Leader/Ender_Leader_SO101.stl` and `STL/SO101/Follower/Ender_Follower_SO101.stl` instead.

### Settings to ask for

- Process: FDM
- Material: PLA+
- Infill: 20%
- Finish: standard
- Color: your choice

Once the parts arrive, follow the assembly guide and you are ready to build your SO-101.
