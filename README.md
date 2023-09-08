# KirbyVariants
Using primitive 3D objects recreate the famous Kirby and 4 of its variants

#######################################################################################################

PART 1. Creating Traditional Kirby

Step 1: Creating class for Kirby
![CreatingKirby1](https://github.com/MegretMendez/KirbyVariants/assets/142510070/8e7439ff-ca1d-470e-aeb2-2926b03b2d1f)
Description: Let's start by creating an Empty Object with the purpose of having some sort of class for our Traditional Kirby. This is optional, but we named it TraditionalKirby so we can easily identify our objects.

Step 2: Creating Kirby's Body
![CreatingKIrby2](https://github.com/MegretMendez/KirbyVariants/assets/142510070/f53d983b-2ca2-43f1-a0bc-9f9a381e5ee8)
Description: Create a sphere that will represent Kirby's body. Modify as you wish so it is similar to kirby. After editing our sphere, left-click on its name in the Hierarchy panel, this should be located on the left side of your screen. While left-clicking on the new sphere, drag it inside of your empty object previously created. After doing so, the sphere should appear right below the empty object and indented. This indicates that the sphere belongs to the class TraditionalKirby.
![CreatingKirby3](https://github.com/MegretMendez/KirbyVariants/assets/142510070/8c5711b2-d8d4-493a-aaa4-1f9278f517b8)

Step 3: Completing Kirby
![CreatingKirby4](https://github.com/MegretMendez/KirbyVariants/assets/142510070/b11229b7-dd32-4469-8af1-fd96f679645d)

Description:Using the different 3D Objects, we will add arms,legs and eyes to our Kirby class. Use the manipulative tools(move,rotate,scale) to make Kirby as you wish. Add every object you create to Kirby's class by repeating the click and drag method. Additional: Name every object in relation of what part of Kirby's body it is representing so that it is easieer to understand and read. Plus this adds tidiness to our designs.

Note: Observe how every object we created is labeled with a different body part and most importantly, they are indented below TraditionalKirby.

Step 4: Kirby Prefab
![CreatingKirby5](https://github.com/MegretMendez/KirbyVariants/assets/142510070/df68200b-d691-4a13-b5fa-7f528a10b093)

Description: After we have finished customizing our Kirby, we will left-click on the entire class,TraditionalKirby, and drag it to the Assets folder in the Project panel on the bottom of our screen. This will create a "Prefab" of our Kirby. A prefab is basically the same as a class. 

![CreatinmgKirby6](https://github.com/MegretMendez/KirbyVariants/assets/142510070/f0525277-3904-4ae3-88e8-78e5b493bb98)
Note: Observe that the TraditionalKirby object now appears in blue with a cube besides it. This indicates that this is an object of a prefab.
![CreatingKirby6](https://github.com/MegretMendez/KirbyVariants/assets/142510070/c214463c-0df6-4ce6-b21c-fbfdd73f393b)

Description: In the Assets folder, click on the newly created prefab. Your Kirby model should appear in a blue plane. Here you can edit your Kirby as you wish and the changes will be reflected in the original Scene.
#######################################################################################################

PART 2. Using Traditional Kirby to create 4 variants
![CreatingKirby7](https://github.com/MegretMendez/KirbyVariants/assets/142510070/142a0938-3b5d-4cf8-a468-16194ecbf923)
Description: To create the 4 Kirby Variants, we will once again drag the original prefab to the Assets folder. This time a message will be displayed on the screen. 

![CreatingKirby8](https://github.com/MegretMendez/KirbyVariants/assets/142510070/20e150ac-748d-4aac-9692-840bf90bba63)
Description: The message will ask if we desire to create a new Prefab or if we prefer to create a Variant Prefab of our TraditionalKirby. We will choose to create a Variant Prefab. This creates a duplicate of the original prefab but is totally independant from the original. We can distinguish Original Prefabs from Prefab Variants because even though Prefab Variants are also displayed in blue with a cube, the cube has one of its faces shaded. Remember to change the name of the Prefab Variant to easily distinguish them. 

![CreatingKirby9](https://github.com/MegretMendez/KirbyVariants/assets/142510070/c8a9408d-c30d-426a-9003-4583077d9949)
Description: Inside the new prefab variant, edit your Kirby to make it resemble one of the variants you chose. 

The picture below shows an example of a Kirby Variant: 
![CreatingKirby10](https://github.com/MegretMendez/KirbyVariants/assets/142510070/dd2ed439-05c7-4d31-afdf-3b1718f92bcc)
Note: Adding colors is optional. But adding colors is an advantage because we can better appreciate the little details of our Variants. At the bottom of the page you will find and "Additionals" section, where how to add colors will be explained in addition to other optional features.

Repeat "Part 2. Using Traditional Kirby to create 4 variants" until you have all your Kirby Variants created and styled to the maximum accuracy you can achieve.

#######################################################################################################

PART 3. Creating Terrain for Kirbys

#######################################################################################################

PART 4. Optional(Adding color, water and texture to the terrain)
I. Adding Colors to our Kirby Models.
Step 1: Creating a folder for the colors
![KirbyColors1](https://github.com/MegretMendez/KirbyVariants/assets/142510070/25465d6b-f3ca-4be8-9b88-0a1e420d649b)

Description: On the top of your screen, select Assets->Create->Folder. Name as you wish. In this case we named it Colors. This new folder should appear in the Assets Folder in the bottom panel of the screen. 
![KirbyColors2](https://github.com/MegretMendez/KirbyVariants/assets/142510070/ce144417-c8fe-423a-9f07-cc07eebcb3a2)


Step 2: Open Colors folder and create a color
![KirbyColors3](https://github.com/MegretMendez/KirbyVariants/assets/142510070/6404604b-c2d7-479f-abfe-14a5c9df078e)
Description: Inside the Colors, select Assets->Create->Materials in the menu shown at the top of the screen. A new material should appear in your Colors folder. Change the name of the new material to the name of the color you are going to create.
![KirbyColors4](https://github.com/MegretMendez/KirbyVariants/assets/142510070/118d8230-a988-446b-be78-8497afa4440b)

Step 3: Editing new color
![KirbyColors5](https://github.com/MegretMendez/KirbyVariants/assets/142510070/7e52276e-b132-4d28-a702-350ba4f810d6)

Description: Select the newly created color and select the Base Map property in the Inspector panel on the right hand of your screen. A color palette should appear. Play with the color palette until you are satisfied with the tone of your color. 
![KirbyColors6](https://github.com/MegretMendez/KirbyVariants/assets/142510070/c5353a49-4525-46e6-aa0f-df96479c70a8)

Step 4: Adding the color to a 3D Object
![KirbyColors7](https://github.com/MegretMendez/KirbyVariants/assets/142510070/393395f5-391d-4166-a0f5-4700bba689cb)


Description: To add color to an object, simply left-click the color and drag it towards the object you wish to color. 

Note: Repeat "I. Adding Colors to our Kirby Models" for every color you wish to use.

II. Importing texture packages to make our terrain realistic.
Unity does not come with texture packages installed. However you can impport a variety of free packages from Unity's online Asset Store.
Step 1: Adding assets
![KirbyPackages1](https://github.com/MegretMendez/KirbyVariants/assets/142510070/fa41a7a1-0f48-4e86-b125-24f853e57c1e)
![KirbyPackages2](https://github.com/MegretMendez/KirbyVariants/assets/142510070/e0a4027a-ee3a-474f-bf60-e12cfc0f1d33)

Description: For styling our mountain we will import the "Handpainted Grass & Ground Textures" package from the Assets store. On your browser search "Unity Assets Store". Once in teh store search for "Handpainted Grass & Ground Textures". Click on the first texture package and select "Add to My Assets". 

Step 2: Importing packages to Unity
![KirbyPackages3](https://github.com/MegretMendez/KirbyVariants/assets/142510070/d4e68d1f-e3de-4957-b790-148bd3e0aefc)

Description: In the Unity app, from the top menu, select Window->Package Manager. A window titled Package Manger should appear on your screen.
![KirbyPackages4](https://github.com/MegretMendez/KirbyVariants/assets/142510070/a016d4d4-b978-48d6-a392-0eb2e0265086)

Step 3: Packet Manager
![KirbyPackages5](https://github.com/MegretMendez/KirbyVariants/assets/142510070/77cf7c0f-a8be-4716-a381-1315b2ba474d)

Description: In the top left of the Packet Manager window, select the "Package" drop down and select "My Assets". Select the "Handpainted Grass & Ground Textures"->Import->Import. The "Handpainted Grass & Ground Textures" package
should appear in the Assets folder. We will not do anything inside this folder. 

Step 4: Applying texture package to terrain
![KirbyPackages8](https://github.com/MegretMendez/KirbyVariants/assets/142510070/179ab9fa-2874-40bf-9bce-9c01474aa30a)

Description: To apply textures to our terrain, we will select the terrain and in the Inspector panel, go to the Terrain section, select the icon with a mountain and a paint brush. In the dropdown menu, below the previously metioned icon, select the Paint Texture option. Below that Dropdown menu select Edit Terrain Layers->Add Layers. From there the 'Handpainted Grass & Ground Textures" Package will open, select the terrain texture you prefer. By default, the texture you choose will cover the whole terrain, but simply add another layer and paint how you desire. 
