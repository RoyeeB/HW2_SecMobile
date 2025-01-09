# APK Fix and Upgrade  

## Project Description  
This project involves fixing and upgrading an Android application.  
The app is a game where the user must press arrows based on the result of `modulo 4` for each digit in their ID number.  

---

## Changes Made  
- Fixed an incorrect URL in the application.  
- Fixed an issue with displaying **Toast** messages in the "Game" activity.  

---

## Game Rules  
1. For each digit in the ID number, calculate `modulo 4`.  
2. Based on the result, press the corresponding arrow:  
   - **0**: Left arrow  
   - **1**: Right arrow  
   - **2**: Up arrow  
   - **3**: Down arrow  

3. After successfully surviving the game, a **Toast** message will display the name of the city reached.  
   - The city name is fetched from a list of cities stored at a specific **URL**, using the 8th digit of the ID number as an index.  

---

## How to Use  
1. Install the fixed APK on an Android device.  
2. Launch the game.  
3. Enter your ID number and follow the arrow instructions.  
4. Try to survive and reach your destination!  


