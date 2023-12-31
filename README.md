# BITS_Flutter_Back4App_Integration_Assignment

# TaskList App

## Description
* A Flutter TaskList App with [Parse](https://parseplatform.org/) ([Back4app](https://back4app.com)) as the backend demonstrating CRUD operations.
* Getx State Management
 
## Objective
 This repo will be useful to developers looking for an alternative to backend services like Firebase as they will enjoy building apps without any third party libraries when they switch to using RestFUL APIs provided by the Back4App platform.

## ScreenShots
<table>
    <tr>
        <td><a href="https://ibb.co/DDgj2K1"><img src="https://i.ibb.co/d0JHYKf/Screenshot-20231118-024645.png" alt="Screenshot-20231118-024645" border="0"></a></td>
        <td><a href="https://ibb.co/gWcbVBD"><img src="https://i.ibb.co/R6JGyVC/Screenshot-20231118-023734.png" alt="Screenshot-20231118-023734" border="0"></a></td>
        <td><a href="https://ibb.co/sRGy9Ck"><img src="https://i.ibb.co/W5wgv0q/Screenshot-20231118-025721.png" alt="Screenshot-20231118-025721" border="0"></a></td>
    </tr>
</table>

## Features
* Splash screen
* Search tasks
* Save tasks as well as Update tasks
* Delete tasks.

## How to run
* Sign Up or Sign In on [Back4app](https://back4app.com)
* Once signed in click “Build a new app” and give a name to your app
* You will be taken to the console where by default there are 2 classes Under **Database** present namely Role and User. Create a new class named `task` which will store the data for each Task item.
* Proceed to 2 columns namely: `title` and `content` to the class which will store the actual task.
* Clone this repo
* Navigate to the code `lib\app\constants\api_constants.dart`
* On the console go to **App Settings** >> *Security & Keys*
* Copy the **Application ID** and paste in place of `YOUR_PARSE_APPLICATION_ID`
* Copy the **REST API key** and paste in place of `YOUR_PARSE_REST_API_KEY`
* Run `cd`
* Run `flutter pub get`
* Run `flutter run`
