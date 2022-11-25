# rosbot-gamepad

A GitHub template for ROSbot 2R: a gamepad control 

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

Connect a gamepad (tested on Logitech F710) to USB port of your PC/laptop. 

```
docker compose up
```