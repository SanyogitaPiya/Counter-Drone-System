# Counter-Drone-System
The system detects drones and sends back information of detected drone to users. System is designed to perform in an open space with 360 camera detection. The system is designed to address general drone safety concerns. By providing feedback on drones located in the area, customers can be informed of drone behavior around sensitive locations. A live video feed is captured by an external camera hooked up to the system, acting as the system’s Computer Vision. The captured frame is then dewarped and processed for compatibility. Once the image is compatible, it is processed by an object-tracking library called YOLOv7; YOLOv7 will then
draw on frame lines with labels onto identified objects. The image with frame lines will then be sent to the application and then the results will be displayed.
## Requirements:
#### System will be to actively track an individual drone
<img width="251" alt="drone" src="https://user-images.githubusercontent.com/85206339/223569670-5f2bc3e1-da44-44c6-95f3-7854e148570f.png">

#### The system will show atleast 60% accuracy in detection of the drone
<img width="254" alt="drone1" src="https://user-images.githubusercontent.com/85206339/223569746-a095d290-9156-41b0-86b3-6af3e87709bf.png">

#### System will maintain false positive below the rate of 15%

#### Product will be delivered by the end of MAY 2023

#### The system shall be developed with prouction budget of $800

#### The system will show the current location of the device places
