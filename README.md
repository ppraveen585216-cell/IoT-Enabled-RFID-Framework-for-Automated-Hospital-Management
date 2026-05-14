# IoT-Enabled-RFID-Framework-for-Automated-Hospital-Management
This project is an RFID-Based Hospital Management System developed using ESP32 and RC522 RFID module. The system helps manage patients, doctors, staff, and administrators using RFID cards for secure and efficient identification and monitoring.
## Features
- RFID-based user identification
- Patient and staff management
- Real-time data monitoring
- LCD display integration
- Access control using servo motor
- Web dashboard support
- Secure user authentication
## Technologies Used
- ESP32
- RC522 RFID Module
- Arduino IDE
- HTML (Frontend and UI Design)
- Python/Flask (Backend)
- Supabase
## Hardware Components
- ESP32
- RC522 RFID Reader
- RFID Cards/Tags
- Servo Motor
- 16x2 LCD Display
- Buzzer
- LEDs
- Jumper Wires
## System Architecture
<img width="561" height="343" alt="Screenshot 2026-05-14 134042" src="https://github.com/user-attachments/assets/32950c69-2ab4-4e52-9caf-463a70db66a6" />
This block diagram represents the working architecture of the RFID-Based Hospital Management System. The system begins with an RFID card or tag, which is assigned to users such as patients, doctors, staff, or administrators. When the card is scanned, the RFID Reader (RC522) reads the unique identification data through wireless communication and sends it to the ESP32 microcontroller for processing. The ESP32 acts as the main controller of the system. Based on the received RFID data, it controls different output devices such as the 16x2 LCD display to show user information, LED indicators (green/red) to indicate valid or invalid access, a servo motor for access control, and a buzzer for alerts or unauthorized access warnings. 
The ESP32 also uses its built-in Wi-Fi module to send data to the central database/server. The server stores important information such as user details, attendance logs, and records. This data is then connected to the web dashboard, which allows real-time monitoring and management of hospital activities. 
The user management section handles different user roles including admin, doctor, staff, and patient, ensuring secure access and proper control of hospital data. Overall, the block diagram shows how RFID technology, wireless communication, and web-based monitoring are integrated to create an efficient and secure hospital management system. 

## Future Enhancements
- Face recognition integration
- Mobile application
- AI-based monitoring
## Contributors
- AKSHAY MALLIKARJUN ANDELI (Worked as documentation team we have done the report were responsible for the Result and Conclusion and Reference and suggested changes on web design)
- DALIA JAHAN LIZA (Worked as part of the data engineering team I have shared base paper or research paper and I have also shared initial code for the webpage.)
- DHANUSHREE C H (Worked on a literature survey and also sent three survey papers. I worked on the market analysis and market growth to identify gap between our project and current market demand. I also worked on proof of concepts of our project. I have sent the html code for doctor dashboard and receptionist dashboard. Doctor dashboard contains information of doctor. Receptionist dashboard contains information about staff, doctor and patient.)
- EVANGELIN (Worked on backend development and dashboard management of the RFID-based Hospital Management System using Python with the Flask framework. She worked on creating and handling the local host server environment, enabling smooth communication between the ESP devices, database, and web dashboard. Her work included managing backend functionalities, handling data flow, and supporting real-time monitoring features within the system.)
- MOHAMMED AFNAN SAYEED (Worked as model team i have worked with the hardware part me Suzain and Auf met offline and rishab was in virtual we worked the hardware part checked the cpmponents tested and completed the integration of components and the model was also prepared by us three and i have give the code for app integration to dump in esp32)
- MUHAMMED AUF (Worked on assisting in web design, ESP coding, and system architecture. As part of the model development team, he developed ESP-server communication code and integrated hardware with software for smooth functionality. He also implemented features such as LCD display, pathway lighting, and automated door control, and successfully integrated the complete hardware model.)
- NAGALING NEMATI (Worked as data engineer team and i  worked on searching problem Statement and production server starting we did in railway for server but it is not compatible with every project areas as we were facing issues with this. So changed to render base this server was managed by sujay Also worked on database in supabase.)
- NOOR ZAIBA (Worked as Data Engineering. I have worked on sharing and integrating the code for both frontend and backend development. Along with that, I also contributed to designing the user interface to make it more interactive and user-friendly. My focus was on ensuring smooth data processing and efficient system performance.)
- PRAVEEN PATIL (Worked as documentation team, I worked on the report in that I am responsible for the Abstract and Introduction and literature survey and provided suggestions over ui part)
- RISHAB H KADAM (Worked on the modeling part of the project “IoT-Enabled RFID Framework for Automated Hospital Management.” I researched project papers and studied components like the RFID scanner, I2C module and ESP32 dev kit. I also participated in virtual meetings to support the system design. My work helped in understanding how the system can automate hospital management efficiently)
- SANJANA B S (Worked on shared the project ideas, then I shared the research papers & also I worked on poc.when it comes to software part I had shared the HTML code for the staffs and patients.Which displays the patient’s name,disease,assigned ward and complete medical history.)
- SANJU P (Worked as documentation team I  have done the synopsis and In Report the organisation and writing of contents and also helped in data engineer at beginning of the webdesign Part And With testing the production server)
- SUJAY S (Worked as a Data Engineer, focusing on backend development and production deployment. I used Render to build and manage live server environments, including server setup, configuration, and performance optimization. I ensured efficient data handling and carried out basic monitoring to maintain system reliability. Additionally, I suggested improvements in web design to enhance usability and better integration between frontend and backend components.)
- SUZAIN KHAN S (Worked as a part of the model development team, where I actively participated in offline meetings and contributed to the overall development process. I was involved in testing hardware components to ensure proper functionality and system reliability. I also assisted in developing the prototype model and contributed to the core idea through my own research. Additionally, I supported the team by sharing and implementing code for IR sensors, which helped in improving the system’s functionality.)
- SWATHI K (Worked as 11. data engineering team, I worked on database integration using PostgreSQL through pgAdmin 4. I supported handling user data storage and retrieval as part of the application workflow. I also shared and updated code whenever changes were required during development. Apart from development work, I contributed to two research papers that were shared as part of the project.)
- USMAN KHAN (Worked on 9. conducted research on the project and understood its requirements. Then, I collected datasheets for all the components used. In the synopsis, I worked on the methodology, block diagram, and flowchart. In the final phase, I completed the hardware components and compiled all the required data.)
