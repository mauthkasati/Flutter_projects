# Resto HR System

Note: This is my first real application for an actual customer.</br>
Note: I cannot share the project's code to protect the owner's privacy.</br>

The Resto HR System is a mobile application designed to streamline attendance management and break tracking for multi-branch restaurants using advanced face recognition technology. This README overviews the project, its features, and instructions for getting started. </br>

Note: The app is designed to be used by the admin or owner of the restaurant. and other employees can use the app only to record their attendance and breaks.</br>


## Table of Contents
- [Features](#features)
- [Technologies Used](#Technologies_Used)
- [App Demo](#App_Demo)

## Features

- **Face Recognition Attendance:** Employees can easily clock in and out using face recognition, eliminating the need for traditional time clocks.
- **Multi-Branch Support:** Ideal for restaurant chains, this system supports multiple branches with centralized management.
- **Easy to use:** Employees can record their attendance easily. Also, the admin can add employees' FaceIDs easily.
- **Break Management:** The app helps employees and managers track break times, ensuring adherence to labor regulations.
- **User-Friendly Interface:** An intuitive and user-friendly design makes it easy for employees and managers to use.
- **Efficiency:** Streamlines HR tasks, reduces errors and ensures accurate attendance records.
- **Data Security:** Robust security measures protect employee data and attendance records.


## Technologies_Used

- **Provider State Management**
- **RestFul APIs** for authentication, get restaurants, get employees, register FaceIDs, recognize faces, and add selected options.
- **Easy Localization** for supports English and Arabic for the hall App.
- **Using camera and   flutter_image_compress packages**
- **Shared Preferences**


## App_Demo

- **Login Screen:** This is a login screen, it supports choosing the language of the app.</br></br>
- <img src="https://github.com/mauthkasati/Flutter_projects/blob/main/Resto_App/images/Login_Screen_Arabic.jpg" width="250" alt="Login Screen"></br></br>
- After the user enters the correct username and password, the app routes him to **Restaurants Screen** to choose the needed branch.</br></br>
- <img src="https://github.com/mauthkasati/Flutter_projects/blob/main/Resto_App/images/Restaurant_Branches_Screen.jpg" width="250" alt="Login Screen"></br></br>
- After the Admin chooses the branch, he goes to **Main Screen**, a screen used by employees, they click on the scan icon to scan their face and enter to options screen if the face matches the registered one.</br></br>
- this is a Main Screen
- <img src="https://github.com/mauthkasati/Flutter_projects/blob/main/Resto_App/images/Main_Screen.jpg" width="250" alt="Login Screen"></br></br>
- and this is a scan screen
- <img src="https://github.com/mauthkasati/Flutter_projects/blob/main/Resto_App/images/Scan_Face_ID_Screen.jpg" width="250" alt="Login Screen"></br></br>
- This message appears if the face is not correct, or does not exist</br></br>
- <img src="https://github.com/mauthkasati/Flutter_projects/blob/main/Resto_App/images/Wrong_In_Face_Recognition_Message.jpg" width="205" alt="Login Screen"></br></br>
- This is the options screen where an employee can register his attendance and breaks.</br></br>
- <img src="https://github.com/mauthkasati/Flutter_projects/blob/main/Resto_App/images/Options_Screen.jpg" width="250" alt="Login Screen"></br></br>
- if the user selects an option this confirming message will appear.</br></br>
- <img src="https://github.com/mauthkasati/Flutter_projects/blob/main/Resto_App/images/Confirm_Selected_Option_Message.jpg" width="250" alt="Login Screen"></br></br>
- This image shows a description text of the last done option.</br></br>
- <img src="https://github.com/mauthkasati/Flutter_projects/blob/main/Resto_App/images/Options_Screen_After_Selecting_An_Option.jpg" width="250" alt="Login Screen"></br></br>
- Now we returned to the main screen, exactly to appear of the main screen, where the admin can go to the employees' screen and register their faces, he has to enter his password again.
- <img src="https://github.com/mauthkasati/Flutter_projects/blob/main/Resto_App/images/Main_Screen_AppBar.jpg" width="250" alt="Login Screen"></br></br>
- <img src="https://github.com/mauthkasati/Flutter_projects/blob/main/Resto_App/images/Required_Password_For_Enter_To_Register_Employees_Screen.jpg" width="250" alt="Login Screen"></br></br>
- Then the admin goes to the employee screen, and when he clicks on an employee a confirmation message appears, once it is confirmed a camera opens to receive an image of the employee.
- <img src="https://github.com/mauthkasati/Flutter_projects/blob/main/Resto_App/images/Employees_Screen.jpg" width="250" alt="Login Screen"></br></br>
- <img src="https://github.com/mauthkasati/Flutter_projects/blob/main/Resto_App/images/Confirm_Adding_Face_ID_For_Selected_Employee.jpg" width="250" alt="Login Screen"></br></br>
- <img src="https://github.com/mauthkasati/Flutter_projects/blob/main/Resto_App/images/Scan_Face_ID_Screen.jpg" width="250" alt="Login Screen"></br></br>
- Finally, a message appears to confirm adding or showing an error occurred.
- <img src="https://github.com/mauthkasati/Flutter_projects/blob/main/Resto_App/images/Face_ID_Added_Successfully.jpg" width="250" alt="Login Screen"></br></br>
- **For sure there is a validation of the existence of the face.**




