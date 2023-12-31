
![image](https://github.com/WillowSaysWhat/Enid-Tracker/assets/126318401/4203defd-96ba-4c41-8e61-babffebc2c95)

# Enid Tracker
##### Medicine Consumption Tracker
## Table of Contents 
* [Description of the Application](#description-of-the-application)
* [Software Elements](#software-elements)
* [Understanding the user Interface](#understanding-the-user-interface)
* [Important Widgets](#important-widgets)
  * [Medicine panel](#medicine-panel)
  * [Adding a New Medicine](adding-a-new-medicine)
* [SoftwareDocumentation](#software-documentation)
  * [Software Stack](#software-stack)
  * [Widget Design](#widget-design)
## Description of the Application
Enid Tracker is a cross-platform mobile aplication that monitors medicine consumption.

Enid's user-friendly interface provides a hassle-free experience for users of all ages. The app allows individuals to effortlessly input and manage their medication schedules, setting reminders for each dosage to ensure timely and accurate intake. Leveraging Flutter's cross-platform capabilities, Enid Tracker offers a consistent and smooth experience on both Android and iOS devices.

#### Key Features
* **_Push Notifications_** to remind the user to take their medicine daily, morning, lunch, dinner, and bedtime. The alert will pop up in the same way a Instagram, Telegram, or any other app send push notifications to the user. This will give a familiar feel to Enid Tracker. All push notifications can be set by the user via the app. 
* **_Add New Medicine button_** will be a floating button on the home screen which will allow the user to ceate a new medicine notification/alarm for any new medication they have been prescribed. This option is always availble.
* **_Refil Notifications_** are prompts that remind the user that their medicine stock is getting low and that a visit to the pharmacy is required. This is symbolised by the change in widget color from the theme color to an amber when medicice is low, and red when the medicine is critically low. There will be a reset option for when the user has visited the pharmacy.
* **_Easily Edit Remiders_** so that updates to the user's medicine regime can be quickly adjusted on Edit tracker to reflect those changes. This will be done with a simple click on the medicine panel and the user will be given the option to edit.

_Enid Tracker is currently under construction and will be revealed in it's first iteration in March 2024._

# Software Elements

![image](https://github.com/WillowSaysWhat/Enid-Tracker/assets/126318401/f7ec722b-3418-428f-b868-e69dba35a6f0)


## Understanding the User Interface
The image above is the current famework for the home screen in its the current stage of production. It can be broken down into 2 sections. the circlular icon bar will hold filtering option in the first iteration, but can be changed to hold settings icons and/or other user options. The larger cards display the users medicine information and will have an onPressed action that will allow the user to make changes to the medicine information.
## Important Widgets
There is a few simple widgets that have been constructed suing the available widgets in Flutter. This encompasses the Medicine panel which is the rounded-rectangle found on the Home Screen. It visualises the different medication within the user's regime. The image selection list on the 'Add a New Medicine' page is another prominent widget and was created using a horizontal scrolling ListView builder and an asset folder full of images. The app uses the Provider state management concept to manage the change in image state. 
### Medicine Panel
The Medicine Panel is built using the Medicine object and ListView.Builder. Multiple Medicine objects are held in a List<Medicine>. The builder uses this List to build a scrollable vertical ListView filled with a panel that holds the medicine's name, the strength in milligrams, the amount left in the user's pack, and the pill/tablet icon.
This can be manipulated to reveal an edit and a delete button.
### Add a New Medicine
Add a new medicine is currently a floating action button that takes the user to the corresponding page. 
## Software Documentation
### Software Stack
### Widget Design
### Page Design
### Medicine class
### Adding new pages
### Adding New Widgets

## Future Improvements


