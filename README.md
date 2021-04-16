# Driver Assistance System (DAS)
This Repository contains all files related to Driver Assistance System Project.This is a Internally funded Project

## Need for the Project
The role of DAS is to prevent deaths and injuries by reducing the number of car accidents and the serious impact of those that cannot be avoided.The main reasons for accidents to occur are <b> alcohol consumption and drowsiness</b>.The research mainly focuses on developing a cost-efficient integrated driver assistance system which alerts the driver using buzzer and notifies the owner if he is drunk or drowsy.In case of an accident the system sends the location of the vehicle to the concerned persons.

## Propsed System
This system consists of three inter-linked modules which are firstly, driver drowsiness detection, followed by alcohol content detection and accident/crash detection alongside control to constantly monitor the driver’s physiological condition which will affect the stability of the vehicle. To implement this, a variety of software algorithms and input extraction hardware tools have been employed in a collaborative way. For the industrial implementation of this project a prototype has been developed. To detect the onset of fatigue or loss of vigilance of the driver, within the close vicinity of the driver multiple sensors are embedded on this prototype.

## Softwares and Hardwares used:
* Python
* OpenCv
* Firebase
* Android
* RaspberryPi
* MQ3 sensor
* Piezoelectric sensor

## Some of the Important details to be noted:
1.The SMTP protocol which is used to send mail works only on JIO network. <br>
2.The Raspberry pi is connected to laptop using remote desktop connection app on windows 10.<br>
3.Both the laptop and raspberry pi are connected to same JIO network.<br>
4.While using the Android App , permissions such as sms and location should be enabled.<br>
5.Settings has to be changed for the email id which is used to send the alert.<br>

### Hardware of the System
<img src="https://github.com/NachammaiPooja/Driver_Assistance_System/blob/main/Output%20Images/hardware.PNG" height=500px>

### Use of Haar Cascade Algorithm to Monitor facial interactions of the driver.
<h4> Eyes Open:</h4>
<img src="https://github.com/NachammaiPooja/Driver_Assistance_System/blob/main/Output%20Images/192.168.43.100%20-%20Remote%20Desktop%20Connection%20(eye%20open).png">

<h4> Eyes Close:</h4>
<img src="https://github.com/NachammaiPooja/Driver_Assistance_System/blob/main/Output%20Images/192.168.43.100%20-%20Remote%20Desktop%20Connection(eye%20close).png">

### Alerting phase consist of 2 different modules
<h3> i) Mail </h3>
<h4> For accident Occured:</h4>
 <img src="https://github.com/NachammaiPooja/Driver_Assistance_System/blob/main/Output%20Images/mail(accident%20occured).jpeg">
<h4> For Drunken:</h4>
 <img src="https://github.com/NachammaiPooja/Driver_Assistance_System/blob/main/Output%20Images/mail(drunken).png">
<h4> For sleeing:</h4>
 <img src="https://github.com/NachammaiPooja/Driver_Assistance_System/blob/main/Output%20Images/mail(sleeping).png">

<h3> ii) Msg </h3>
 <img src="https://github.com/NachammaiPooja/Driver_Assistance_System/blob/main/Output%20Images/msg.jpeg" height=400px>
  
### Steps to Run the Prototype
 1.Connect the Raspbery pi to Computer. (I used Remote Desktop Connection App in Windows 10)<br>
 2.Run the Python Program.(Main.py)<br>
 3.After Detection of any of the proposed event , an alert is raised.<br>
 4.Check your Email and Phone number for Alert message. <br>
 
 
 ### My Teammates 
 1.<a href="https://github.com/praveenkumar0211">Praveen Kumar</a><br>
 2.<a href="https://github.com/Aravind1411">Aravind P</a><br>
 3.<a href="https://github.com/prathyush2510">Prathyush S</a><br>
