David Méndez
Jose Megret

KirbyVariants

Using primitive 3D objects to recreate the famous Kirby and 4 of its variants. Recreate a zone from the Puerto Rico Map and assign a zone of our terrain to each Kirby Variant. 

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

Step 1: Creating Class for Kirby land
![CreatingTerrain1](https://github.com/MegretMendez/KirbyVariants/assets/142510070/f6ff702c-0a0f-4399-9994-42d43650ece1">)
Description:  Let's start by creating an Empty Object with the purpose of having some sort of class for our Kirby map. This is optional, but we named it Kirby land so we can easily identify our objects.

Step 2: Creating the terrain
![CreatingTerrain2](https://github.com/MegretMendez/KirbyVariants/assets/142510070/0a1ddc4c-ac68-46df-a1d9-9ba637ec927d">)

Description: To create the terrain, we will go to GameObject > 3D Object > Terrain. Once the Terrain is created, left-click on Terrain in the Hierarchy panel, this should be located on the left side of your screen, and drag and drop under Kirby land. After doing so, the Terrain should appear right below the empty object and indented. This indicates that the Terrain belongs to the class Kirby land.

Step 3: Re-sizing the Terrain
![CreatingTerrain3](https://github.com/MegretMendez/KirbyVariants/assets/142510070/22ff1aab-7ab4-4fc1-976d-d422ae7bd889">)

Description: To resize the Terrain, click on your Terrain in your Hierarchy panel, and there one will be prompt with the components of the Terrain, this is located in the right part of the screen. Then click on Terrain settings. Scroll down to where it says “Mesh Resolution” (On Terrain Data) and edit the Terrain Width to 250, Terrain Length to 250, Terrain Height 250. After that, scroll a little bit more to where it says “Texture Resolution” (On Terrain Data) and click on Heightmap Resolution drop down box and put it to 257x257.

![CreatingTerrain4](https://github.com/MegretMendez/KirbyVariants/assets/142510070/daa0e644-ac90-42b8-8a03-7d8e69f6026d">)

Step 4: Editing the Terrain
![CreatingTerrain5](https://github.com/MegretMendez/KirbyVariants/assets/142510070/f106e495-b598-4a10-9590-a07affe7bdeb">)

Description: Go back to the Terrain component on the right of the page and click on Paint Terrain. Then go to the drop down right below it and click “set Height” and where it says “Height” put it in 50 and select “Flatten All”, this way we can lower the Terrain to make rivers, etc.. 
![CreatingTerrain6](https://github.com/MegretMendez/KirbyVariants/assets/142510070/355c91ee-617c-4626-a550-f549af6b93ad">)
![CreatingTerrain7](https://github.com/MegretMendez/KirbyVariants/assets/142510070/84e9e313-e8e3-48b1-b150-92c4e7d2031a">)

Now go back to the drop down box and click on “Raise or Lower Terrain”.
![CreatingTerrain8](https://github.com/MegretMendez/KirbyVariants/assets/142510070/42b6033c-73c6-41de-b52d-acee549aef47">)
![CreatingTerrain9](https://github.com/MegretMendez/KirbyVariants/assets/142510070/a5a73b51-6dd9-45dc-b358-e6880cba4f24">)
Note: You can change the brushes to add more texture to the Terrain and you can adjust the Brush size and Opacity for larger or smaller areas.

![CreatingTerrain10](https://github.com/MegretMendez/KirbyVariants/assets/142510070/2bccd788-8d97-4a5e-a40e-75efd970d938">)
Note: Once you click on "Raise or Lower Terrain" you can create mountains, hills, etc. by pressing the left click on the Terrain. Then to make rivers, caves, lagoons, etc. hold shift and left click to lower the Terrain. 

Step 5: Use a reference Image 
![ReferencePicture](https://github.com/MegretMendez/KirbyVariants/assets/142510070/1b68c847-0cc0-4fa3-b031-dc3ea04fe923)
Description: The first action is select a portion of height map of Puerto Rico from this website: https://tangrams.github.io/heightmapper/#9.908/18.2965/-66.1842. The aim is to interpret the geological configuration in order to represent it with the Terrain object.  
A general rule of thumb is that lighter or whiter areas on a map typically indicate higher elevations, such as mountains and hills, whereas darker areas often represent lower elevations, such as rivers and lagoons.

Kirby Land!
![CreatingTerrain11](https://github.com/MegretMendez/KirbyVariants/assets/142510070/24bb3e6a-a8a5-4063-a5b2-6a6de0af6b78">)
Description: After applying all configurations and following the instructions, feel free to unleash your creativity and express yourself, just make sure to stay true to the reference image.

![CreatingTerrain12](https://github.com/MegretMendez/KirbyVariants/assets/142510070/cef8e92f-d15e-493f-b472-a8873e18e021">)
Note: We added 4 platforms to put our Kirby variants in but, this is Optional.

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
![KirbyPackages9](https://github.com/MegretMendez/KirbyVariants/assets/142510070/8ca7f41b-8dd9-48d9-98ab-7425fa20a8fd)

Description: To apply textures to our terrain, we will select the terrain and in the Inspector panel, go to the Terrain section, select the icon with a mountain and a paint brush. In the dropdown menu, below the previously metioned icon, select the Paint Texture option. Below that Dropdown menu select Edit Terrain Layers->Add Layers. From there the 'Handpainted Grass & Ground Textures" Package will open, select the terrain texture you prefer. By default, the texture you choose will cover the whole terrain, but simply add another layer and paint how you desire. 
By adding new layers and using the paintin brush, you can paint the terrain to make it look as you want. 
![KirbyPackages10](https://github.com/MegretMendez/KirbyVariants/assets/142510070/d53ab344-f7f2-4e43-93b8-61b7a782d79d)

Step 5: Add water package
![KirbyPackages11](https://github.com/MegretMendez/KirbyVariants/assets/142510070/55bccd56-aa19-4517-96bb-c1d94b4f2876)

Desscription: For the water, we imported a package called "Simple Water Shader URP" from Unity's Assets store. Once imported go to Assets folder and select IgniteCoders->Simmple Water Shader->Prefabs. Then add the two prefabs in the Prefab Folder. One of the prefabs is an additional camera for the water's reflectiveness and the other is the  water texture. The water texture is plane you can move, scale and rotate. We will manipulate this plane so the water seems like rivers flowing through the terrain.

![KirbyPackages12](https://github.com/MegretMendez/KirbyVariants/assets/142510070/6a0f7218-3195-436f-860a-7735d6bda422)

Final Product:
![FinalProduct](https://github.com/MegretMendez/KirbyVariants/assets/142510070/41cb1a46-e957-400f-943e-647755062d9d)

Personal Memory: David Méndez
Kirby’s Adventure debut was 10 years before I was even born. With that said, I have very little memory of playing Kirby or how Kirby impacted my childhood. The only vivid memory I have of Kirby is the day I played Kirby for the first time. I was around 8 years old and I was staying with my grandparents for the summer. I remember being bored out of my mind and complaining, which gave my grandpa the idea of looking for my uncle’s old Nintendo Entertainment System(NES). After he found the Nintendo console in his storage, he installed it. But my grandfather had no idea how to turn it on or even set the game for me.So I had to investigate how the NES worked on my own. Since the console was old I remember having to blow on the cassette because the console was not reading it. The only game my grandfather found was Kirby’s Adventure. The main memory I have of Kirby from that day was Kirby’s ability to inhale enemies and spit them out as bullets which I found so awesome and amazing.

Personal Memory: José Megret
As a lifelong gamer, I've always been aware of Kirby's iconic presence in the gaming world, even though I hadn't had the chance to play any of his dedicated games until recently. My introduction to Kirby was through Super Smash Bros., where his unique abilities immediately caught my attention. Playing as Kirby in the game was an absolute blast. I loved experimenting with his special attacks and discovering how to outwit my opponents using his copy ability. Kirby's charming and simplistic design makes him instantly recognizable and endearing. However, the most memorable Kirby moment for me was a fierce battle against my roommate. He chose Kirby as his character, and to my surprise, he completely dominated me with Kirby's versatile moveset. It was a humbling experience that left me with a newfound respect for this lovable pink puffball and a desire to explore his dedicated games in the future.
