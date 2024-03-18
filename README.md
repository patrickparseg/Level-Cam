# Level-Cam
With the proliferation of embedded systems and the increasing demand for efficient processing of multimedia data, there
is a growing interest in utilizing FPGA technology for realtime image processing tasks. In this project, we leveraged the
capabilities of Basys3 FPGAs to develop a camera stabilization
system. The system aims to assist users in maintaining stable
camera footage by analyzing data from the inertial sensors
(accelerometer and gyroscope).
Our fully-functioning camera conjoined with a built-in level
provides a feature that handheld digital filming equipment in
this budget does not. When steady and leveled camerawork is
required in filming, it is crucial for the director or cameraman
to be in tune with the camera. While modern cameras can
recognize these changes in inertial movement, they are both
prohibitively expensive and unnecessarily complicated. Our
goal in designing this camera was to create a simple camera
with this inbuilt functionality using an accelerometer and
gyroscope. We have also cut out any latency issues with
wireless communication between cameras and monitors, thus
utilizing the VGA output from the Basys3 board.

Using this device would work as follows:

• The User turns on the device and the camera feed displays
to the monitor through a VGA connection.

• If the camera is tilted too far in any direction, a light is
turned on based on whether the camera is tilted along the
X or Y axis to notify the user to stabilize the camera.

• If the camera is too far tilted on both the X and Y axis,
both lights are turned on.
