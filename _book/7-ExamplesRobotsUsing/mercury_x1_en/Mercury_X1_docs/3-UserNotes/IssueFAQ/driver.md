# Related

## 1 About python

**Q: Send_base_coords ([x, y, z, rx, ry, rz], Speed) What does the parameters in this API mean? What is RX, RY and RZ corresponding to Euler Kou? What is the rotation order of Euler Horn? What is the value range of each parameter?**

- A: The parameters in the previous array are the coordinates of the end of the Mercury X1, and the Speed ​​is the speed. RX, Ry, and RZ should correspond to the RPY, that is, correspondingly rolling, pitching, and offsets, respectively. The order of the Euler Horn is ZYX, and Zyx is its own coordinates. The value range of x, y, and z.为-350\~350，-350\~350，-41\~523.9（The value range is undefined, and if it is exceeded, the inverse kinematics no solution tip is returned），rx、ry、rz Is in the range of-180 ~ 180.

**Q: Is the Python API of different versions of the robotic arm the same?**

- A: The API is the same.

## 2 About ROS
**Q: Can you provide files and programming examples of the RVIZ model?**

- A: It can be found on our GitHub.
"Https://github.com/elephantrobotics/mercury_x1_ros"

**Q: Why did the error permissions "/dev/Tyusb0" when using ROS to start the RVIZ model file?**

- A: This is because the serial authority is not given. You should type the name of the Sudo Chmod 777 in the terminal.
  For example:
  `` `
  SUDO CHMOD 777 /DEV /TTYUSB0
  `` `

**Q: Why do the slider control and model running the ROS follow the command, the error \ _init_ () takes exactly 2 arguments (3 given)?**

- A: Pymycobot library is not installed and started.

**Q: When using ROS, why is the angle of Mercury_X1 after opening the RVIZ model is inconsistent with the model angle?**

- A: It is likely that the zero position of Mercury_X1 is not calibrated, and the zero position of Mercury_X1 needs to be calibrated.

[← Previous](./3.4-faqsandsolutions.md) | [Next page →](./software.md)