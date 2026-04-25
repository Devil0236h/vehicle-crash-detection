1. Introduction:-

The Vehicle Crash Detector is an innovative project that aims to enhance road safety by actively detecting Vehicle Crash Accidents on the road using CCTV footage and alert
mechanisms. The system employs object detection technology based on TensorFlow to accurately identify accidents involving vehicle crashes and promptly notify the nearest hospitals police stations and RTO with detailed accident information. The core of the system relies on CCTV data as a source to function The Vehicle Crash Detector project is a Vehicle Crash Detection and Alert System which could be integrated with existing systems. By leveraging video surveillance systems the focus of this system is to actively detect vehicle crash accidents and promptly respond to ensure the safety of individuals involved. The system utilizes advanced detection algorithms for crash detection based on TensorFlow which enables it to identify vehicle crashes in real time. By analysing the CCTV footage the system can detect potential accidents involving vehicle crashes. When an accident is detected the system captures a snapshot of the accident scene and generates an alert in the form of Email and SMS with necessary information. Upon detection, the Vehicle Crash Detector automatically notifies the nearest hospitals, police stations and RTO providing them with the accident location snapshot and initial details about the vehicle crash accident. This rapid alert mechanism ensures that emergency services can be dispatched promptly to the accident location potentially reducing response times and improving the chances of saving lives. Overall the Vehicle Crash Detector offers a comprehensive solution to enhance road safety through proactive accident detection and swift response. By leveraging CCTV technology, advanced algorithms and integration with emergency services the system aims to minimize the impact of vehicle crash accidents and provide timely assistance to those in need.


2. Installation:-
*Install Python (version 3.10 or Other Versions may work depending on compatibility) from the official website: Python.
*Install a Python IDE preferably PyCharm or VS code.
*Install the required dependencies ( check the imports in the code).
*Run the Application from the main.py file in the IDE.


3. Features of the System:-

Detect accidents using:
a. Recorded video files
b. Live camera feed

Sends automatic alerts through:
a. Email
b. SMS

Different messages are sent to:
a. Hospital
b. Police
c. RTO

Saves accident images in records section:
a. Original image
b. Labeled image
c. User-friendly GUI made with Tkinter.

4. Implementation:-

The project is developed using:
a. Python – Main programming language.
b. OpenCV – Image and video processing.
c. TensorFlow 2 – AI model training and detection.
d. Tkinter – GUI design.

Model Training Process:
a. Collect vehicle accident images.
b. Label images manually using bounding boxes.
c. Convert data into TFRecord format.
d. Use TensorFlow Object Detection API.
e. Train the model using a pre-trained model .

Training Details:
a. Dataset used: 4000+ accident images.
b. Batch size: 32.
c. Training steps: 50,000.

Detection Process:
When the model detects a crash
a. Alert appears in application
b. SMS is sent
c. Email is sent
d. Accident image is saved

APIs Used:
a. Fast2SMS – SMS service
b. Gmail API – Email service

**Please Note**: The Alert System will not work without setting up SMS and Email APIs with the necessary credentials. for further information visit 

https://www.fast2sms.com/

https://developers.google.com/gmail/api/guides


5. Acknowledgments:-

We thank: Python developers, OpenCV developers, TensorFlow team, All contributors and supporters .
Special thanks to icon creators from Flat Icon.

6. Limitations:-

Some limitations of the project:
*Accuracy depends on training data quality.
*Poor CCTV footage may reduce detection quality.
*Some accidents may not be detected correctly.
*GPU is recommended for faster real-time performance.
*Without good hardware, system may run slower.

7. Project Disclaimer:-

This project is made for educational and demonstration purposes.
It may contain bugs or errors and needs further improvement before real-world use.

Users are encouraged to:
*Improve the project
*Fix bugs
*Add new features
*Use it as a learning project
