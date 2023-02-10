# Automated-Attendance-System

This project aims to implement automated attendance system which combines the RFID verification and face recognition . The proposed system will have a camera to capture the faces of people and a RFID reader to check the ID numbers. If both of the verifying processes return a “Pass” signal, then a successful entrance signal is generated and attendance is marked. The conceptual diagram of the automated attendance system is shown below :

![RFID](https://user-images.githubusercontent.com/117595548/218154393-04223533-e7a2-436a-8ca9-c2b3bc4895ab.png)

AUTOMATED ATTENDANCE SYSTEM OVERVIEW

The system contains three main components :
1) Camera
2) RFID Reader
3) RFID Card

The main goal is to build a recognition system that uses an RFID reader to verify a user's ID number and a biometric system that uses an HD camera to recognize the user's face.

In the first step, an RFID reader reads the user's RFID tag to obtain the user ID. These ID numbers are converted to binary data and sent to the computer via the RS232 interface.

In the next step, the computer searches the received user number in its database. Once the ID number is validated, the computer activates the camera and captures the user's face. The user's image is then sent back to the computer for face recognition and facial recognition via the USB interface.

This user's face is carefully analyzed by an algorithm called 'EigenFaces' using the built-in OpenCV library. The verification process is completed by confirming the User Identity results on general useer interface in website.
