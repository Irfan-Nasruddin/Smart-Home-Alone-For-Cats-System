# _Smart Home Alone For Cats System_
## Description

This project was my final year project for my computer science study at the University of Malaya. Since I majored in Software Engineering, proper 
methods was adhered througout the project. I have documented the whole project and the document can be found within this repository. If you wish a more detailed 
explanation of the project, you may refer to the document.

This project involves studying the concept of remote cat care, the development of a system that allows cat owners to remotely care for their cats, and the formal evaluation 
of the qualities of the developed system.

Lastly, I picked this topic because I think it is the most interesting topic out of all the other topics that was suggested by the project supervisors. I think it is the 
most interesting topic because it also invovles hadware instead of just software (despite me majoring in SOFTWARE engineering). Besides that, it also invovles the 
development of a mobile application, of which I never had any experience with. So, that's just how I am. I like trying out new stuff, even if it is something to my 
detriment (I suffered greatly trying to learn new things while producing this industry grade software).

## Technologies
- Firebase
- Flutter
- Raspberry Pi with Raspberry Pi OS
- Generic bluetooth low-energy beacon (BLE), generic camera, servo motor
- Remote.It

## Features
- The system shall provide the ability for cat owners to create an account
- The system shall provide the ability for cat owners to sign in into their account
- The system shall provide the ability for cat owners to sign out of their account
- The system shall provide the ability for cat owners to remotely access installed cameras to monitor their cats
- The system shall provide the ability for cat owners to remotely control installed dispensers to dispense food and water for their cats
- The system shall provide the ability for cat owners to remotely track the location of their cats wearing Bluetooth beacon
- The system shall provide the ability for cat owner and product owner to install the hardware at the cat owner’s location
- The system shall provide the ability for cat owners to recover their account
- The system shall provide the ability for cat owners to reset their account’s password
- The system shall provide the ability for cat owners to delete their account
- The system shall provide the ability for cat owners to view the usage of their installed hardware
- The user interface of the system shall be easy to be learnt by cat owners
- The user interface of the system shall be easy to be used by cat owners
- The system shall not allow unauthorized access of an account
- The system shall have minimal error
- The total unreliability of the system shall be less than 0.05
- The vital reliability of the system shall be greater than 0.85

## Installation
It is quite a stretch to setup this system as it requires configurations of many technologies. Nonetheless, following is the general sequence of configuration that you can
follow:
1. Setup the Firebase application and provide the firebase_options.dart into the Flutter project
2. Download the apk file for the mobile application and install it
3. Sign up an account through the mobile application
3. Setup a Raspberry Pi and install the hub application on the Raspberry Pi
4. Download necessary libraries into the Raspberry Pi
5. Install the Remote.It client on the Raspberry Pi
6. Setup the application on the Raspberry Pi

This is the general sequence of setting up the system. If you encountered any problem trying to setup this system, feel free to reach out to me for help. You can reach 
me through muhammadirfannasruddin@gmail.com
