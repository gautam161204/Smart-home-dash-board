# Smart Home Dashboard

## Theory

The Smart Home Dashboard is a web-based application developed to simulate a smart home monitoring and control system. It is designed using Python Flask as the backend and HTML, CSS, JavaScript as the frontend.

The main objective of this project is to create an intelligent dashboard where users can monitor room sensor values, update sensor data, delete unwanted records, and view activity history with date and time.

In a real smart home environment, sensors such as temperature sensors, humidity sensors, motion detectors, and light sensors are installed in different rooms. These sensors continuously collect environmental data and send it to a central system like Raspberry Pi or server. The dashboard displays this data in an easy-to-understand format.

In this project, sensor values are simulated manually using user input. The user enters room name and sensor value through the dashboard interface. The backend stores the data in JSON files and updates it dynamically.

The project uses REST API methods:

GET Method – Used to fetch existing sensor data.  
POST Method – Used to add or update room sensor values.  
DELETE Method – Used to remove sensor records.  

Every update or delete action is recorded in the history section along with the current date and time. This helps users track previous changes.

The frontend of the project is designed with attractive CSS styling and JavaScript is used to communicate with backend APIs without refreshing the page.

This project demonstrates the practical implementation of:

Web Development  
Backend Integration  
API Communication  
Data Storage using JSON  
Smart Home Automation Concept  
IoT Dashboard Design  

The Smart Home Dashboard can be further enhanced by connecting real sensors such as DHT11 temperature sensors, motion sensors, or smart appliances for live home automation.

Overall, this project is a simple, effective, and educational model of a real smart home system.

## Conclusion

The Smart Home Dashboard provides an efficient way to monitor and manage room sensor data through a user-friendly web interface. It shows how IoT and web technologies can work together to create modern automation systems.
