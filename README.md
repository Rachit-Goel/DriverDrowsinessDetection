# Diver's Drowsiness Detection
The purpose of this project is to investigate the development of a system for
detecting the likelihood that a driver is about to fall asleep in control of the vehicle,
and to sound an alarm or carry out some other function if this occurs. The system will
be primarily based on the use of a small camera mounted on the vehicle dashboard
which will locate and "track" the driver's eyes, and on this basis attempt to detect if
the driver is about to fall asleep.

For example, if the eyes close and remain closed for a certain period of time, this may
indicate that the driver has fallen asleep and that a crash is imminent. Alternatively, if
the eyes start to fall towards the bottom of the image (in a video sequence), this
might suggest that the driver's head is starting to droop. At the sometime, the
system should not react inappropriately to "natural" movement of the driver's eyes,
e.g. if the driver turns his/her head to look out the side window.

Built by processing images of the driver's face at a high frame rate.  
Technologies: Eye Aspect Ratio, Hough Transformation in Dlib, Haar Cascade Classifier in OpenCV library.
