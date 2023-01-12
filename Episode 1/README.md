# Unreal-Engine-Tutorial-Series
This series will include the basic necessities to learn Unreal Engine. 

<html>
 <body>


### Step 1

  <p1> Select the "Input" Tab. Add 4 Axis Mapping (MoveFoward, MoveRight, Turn, LookUp) <p1>
 
![step 1](https://user-images.githubusercontent.com/122535848/212132243-03505a6c-5562-4ac1-a061-9894fa16ea5c.png)
 
 
 
 
 ### Step 2
 
 <p2> Add the values for the following (MoveFoward, MoveRight, Turn, LookUp). <p2>
 

 ![step2](https://user-images.githubusercontent.com/122535848/212133982-b71389bb-3372-4178-b969-e5118d56f887.png)

 
 ### Step 3
  
  <p3> Add the input "Function" To the "MyCharacter.h" File. </p3>
  
  
 
 ![step 3 ](https://user-images.githubusercontent.com/122535848/212134723-29e62a4f-298f-422b-99d6-a7d3de24e06d.png)

 
 
 
 ### Step 4
  
  <p4> Add the following code to your "MyCharacter.cpp" File. This tells the engine to use those keybinds to control the players movement and turn rate. </p4>
  
  
 
 ![step4](https://user-images.githubusercontent.com/122535848/212135226-5db750dc-d8b1-4c82-9dcc-f72778e16a11.png)

  
  
  
  
  ### Step 5
  
  
  <p5> Add this code to your "MyCharacter.cpp" This code tells the engine to apply the input to the "Player"   </p5>
 
 
 ![step5](https://user-images.githubusercontent.com/122535848/212136202-7233daa5-d27a-4799-87fa-c51faeec5f3b.png)
  
  
  
  ### Step 6
  
  
  
  <p6> Build your source from the "Unreal Engine editor". Right click on the C++ Class "MyCharacter" and select "Create Blueprint class based on the C++ File. This gives us more customizationn and it is easier managing our Player Character from a blueprint rather a C++ file. Do the same with the "ThirdPersonCPPGameMode" </p6>
  
  
  
  ![step6](https://user-images.githubusercontent.com/122535848/212137191-c4a1e696-1ba8-4300-b5d8-8d1f9274f40d.png)

  
  
  ### Step 7
  
  <p7> Nmae the blueprint class "BP_MyCharacter" So you wil NOT get mixed up with the  C++ Class, also create a sepreate folder named "Blueprints" inside your Content Folder. </p7>
  
  

 ![step7](https://user-images.githubusercontent.com/122535848/212137546-f44c4212-8c53-4cbf-bcdf-8a5ece6ecb08.png)
  
  
  
  
  ### Step 8
  
  
  <p8> Select Your default pawn using the panel on the right hand side. select "bp_MyCharacter" This is the blueprint class we created in "Step 6" This class is the "Blueprint" Off the "MyCharacter" C++ file. 

 
 
 ![step8](https://user-images.githubusercontent.com/122535848/212138106-d70e6407-fe1e-40e8-ab33-7bd86f24d200.png)
   
   
   
   
   ### Step 9
   
   
   <p9> Go to the Top of the Editor, select the "Edit" Button on the left hand side and select "Project Settings" Now go to the "Map & Modes" Tab and select the game mode "bp_ThirdPersonCPPGameMode". </p9>
    
   
   ### Step 10
    
    <p> Go to the Left panel in your "bp_MyCharacter" blueprint class. Select your "Skeletal mesh" As desired and an animation Blueprint </p>

 
 
 ![STEP 10](https://user-images.githubusercontent.com/122535848/212139256-2615558a-d5bd-4dc3-95e7-eb5a88d72dd4.png)


 
 
 </body>
 
 </html>
