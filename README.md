# Beaglebone_AI64
Repository for CCS and Eclipse Beaglebone AI-64
BBAI-64 PRU0 application and support for velocity control of a DC bursh motor equiped with a quadrature encoder.

Zip file "motor_control_msg.tar.xz" Is a Linux app designed to run on the BBAI-64.  This app communicates through the
"/dev/rpmsg_pru30" messaging interface.  It facilitates the loading to the "MotorControlPru0.out" app running on the
BBAI64 using the /dev/remoteproc interface.  The PRU app is contained within the "pru0_motor_control.tar.xz" file which
is built using Code Composer Studio.

The Linux app was built using Eclipse and Cross Compiled on a Desktop PC using debian 11 uploaded and debugged on the BBAI-64.
