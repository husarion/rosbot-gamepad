# rosbot-gamepad

A GitHub template for ROSbot 2 PRO or ROSbot 2R: a gamepad control 

Clone this repository in the ROSbot's terminal:

```
git clone https://github.com/husarion/rosbot-gamepad.git
```

> **Firmware version**
>
> Before running the project, make sure you have the correct version of a firmware flashed on your robot.
>
> Firmware flashing command (run in the ROSbot's terminal)
>
> ```
> docker stop rosbot microros || true && docker run \
> --rm -it --privileged \
> husarion/rosbot:humble-22-11-25 \
> /flash-firmware.py /root/firmware.bin
> ```

Connect a [gamepad](https://husarion.com/tutorials/other-tutorials/rosbot-gamepad/) (tested on Logitech F710) to the **USB port of ROSbot**.

In the ROSbot's terminal execute (in `/home/husarion/rosbot-gamepad` directory):

```
docker compose up
```

## Controlling the robot

![ROSbot control with gamepad](.docs/gamepad-legend.jpg)
