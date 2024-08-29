

## How to set-up ros2 + gazebo Fortress + Apple Silicon Chip + Ubuntu 22 on Parallel Desktop



- Get parallel Desktop for mac

- Create a new Ubuntu with x86_x64 emulation virtual machine.
- Update it to 22.04.04 LTS:

Internal:
```
sudo apt update && sudo apt upgrade
sudo reboot
```

- after reboot, enter the following command in the terminal to check for version Ubuntu 22.04.4 LTS

```
lsb_release -a
```

- Proceed as from Step 1 as per the article https://medium.com/spinor/getting-started-with-ros2-install-and-setup-ros2-humble-on-ubuntu-22-04-lts-ad718d4a3ac2


### Installing gazebo fortress

- FYI, I couldnt install gazebo classic on apple silicon chip.

- Install gazebo fortress binary: https://gazebosim.org/docs/fortress/install/
`sudo apt install ros-humble-joint-state-publisher-gui`
