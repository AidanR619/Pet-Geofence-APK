# Pet Geofence

Pet Geofence is a convenient system designed for pet owners to monitor and confine their pets within a designated area, either as a standalone solution or in conjunction with a physical fence. This is ideal for pet owners who desire outdoor freedom for their pets without the hassle of fence installation or containment challenges.

This is a project created by Aidan Rotz, Blaise Corcoran, Dustin Kramer, and Owen Fowles for the Software Engineering course from Kutztown University.

## Video Demo

[Pet Geofence Video Demo](https://www.youtube.com/watch?v=jD74VAgSTXE&t=1s&ab_channel=PGF)

The video showcases various features of the Pet Geofence app and was created as part of a presentation that went over the process of creating this project.

## APK

For those who want to test out the app on their own devices there is an APK included in this repository. This APK can only be downloaded on Android devices as it was created using Android Studio, so it is recommeded to follow the instructions below on a mobile device.

### Installation of APK

1. Navigate to APK

    Select the APK 
  ![readme1](https://github.com/user-attachments/assets/0f70d90a-fd00-4fad-97b1-4855b3518b3c)

2. Download APK

    Press the three dots and select download
   ![readme2](https://github.com/user-attachments/assets/d7f6f23b-1e18-4434-ab37-04ee78ad485b)

3. Download and Open

     Proceed to download the APK and then open it

4. Install

     Install the app onto the device and when installation is done the app should be able to be accessed

## Usage

The ability to view the location of a pet is not available as the information for the created collar will not be shared. The Video Demo above showcases the features of pet location.

1. When the app is first opened, the user will be met with the sign in screen. If the user has not already and wants to create their own account they may press the “Create Account” button and follow the directions below. If the user has already created their account, they may skip to step 2.
   - Type in desired email
   - Type in desired password, then type that password again to confirm
   - An email will be sent to confirm the account
2. After the user has created their account, they will enter their email and password and press “Sign In” to enter the map activity of the app.
3. In the map activity the user can use pinch and swipe features to navigate throughout the map.
4. The user should then go to the bottom UI and select the “Collar” tab and follow directions below to add a pet. ***This part will not work due to the user not having an IMEI to enter but the instructions will be left in to show how a pet would be added.***
   - Press the “+” button
   - When prompted, enter the IMEI from the collar and the name of your pet
   - Press “Add” and your pet should show up in the UI and the location should be appearing on screen. The battery level of the collar and the ability to delete the pet from the app should be available as well
   - Repeat the above directions to add another pet to the app
5. To create a fence for their pet to stay within, the user must navigate to the “Borders” tab on the bottom UI and follow the directions below to add a border.
   - Press the “+” button to be sent to a border creation activity
   - The user can then tap on the screen to place points and must place up to at least 3 points for a fence to be created
   - If needed, the user can tap and drag points to change their positions and if they want to completely remove all points they can press the “⟲” button on the top right of the screen
   - Once the user has created a fence that they are satisfied with, they should press the “✓” button on the top right of the screen where they will be prompted to enter a name for the fence and must press “OK” for the fence to be saved
   - Repeat the above directions to add another fence to the app
6. Once a boundary has been created, on the “Borders” tab the user will be able to activate the fence by pressing the slider next to the fence name. The user will also be able to delete the fence if needed.
7. With both a pet added and a fence activated, the user can start using the app to track the location of their pet and keep it within the boundaries set. Useful information about the pet location and fences are below. ***The user will not be able to view the location of the pet due to not having a collar set up.***
   - The circle seen around the pet is the margin of error calculated by the board and depends on the GPS or LTE connection that the board is receiving. This means that the pet is within the circle shown
     - The board primarily uses a GPS signal to get location, but if it cannot receive a GPS signal it will switch to LTE
   - When a pet goes past a fence, the board will make a noise to tell them that they have passed the fence. The user will also get a notification to their phone that tells them which one of their pets has left a fence and where they are
8. The user can also press the “≡” button on the top left of the screen to open up an information menu. This menu has buttons that you can click on to view the Location History, Privacy Policy, Training Guide, How To Use, and Logout. They may also press the “←” button to return to the maps activity. 
