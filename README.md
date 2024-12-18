
![banner-animated](https://user-images.githubusercontent.com/41008899/194069763-4cd89979-7ae3-403a-96f0-e99c8c714215.png)

### Hi there 👋

:wrench: - I'm Hugo, an **engineering graduate from [Telecom Sudparis](https://www.telecom-sudparis.eu), (game dev specialisation)**. There I got to learn about many aspects of telecommunications along with programming languages such as Bash, Java, C#, PHP and so on. But truth be told, I went there to learn about video game making and take part in game jams. Right now, I work as a backend developer at **Ankama** as part of the **Dofus TOUCH** team. 

---
#### What I do

🦦 - I have been working on my video game project for over a year. I recently started sharing my journey through [blog articles](https://seaotter.games/).

:alarm_clock: - I absolutely love taking part in **Game Jams**. The objective is to form a team and develop a video game from scratch in 48 hours. Have a look at the games I took part in the making:
- [Clown Comedy Care](https://biscuitprime.itch.io/clown-comedy-care) | Global Game Jam 2024 | **Graphic designer**
- [Lost in the Depths](https://skizaat.itch.io/lost-depths) | Unijam 2022 | **Developer** 
- [Steppe by Step](https://akasuna.itch.io/steppe-by-step) | Archeological Game Jam - Etiolles 2022 | **Developer**
- [Geckolot](https://mathieu-coutant.itch.io/geckolot) | Global Game Jam 2022 | **Graphic designer & developer**
- [Neon Dice](https://flegmatik-surf.itch.io/neon-dice) | GTMK Game Jam 2022 | **Graphic designer**
- [Sort'it 'till you make it](https://skizaat.itch.io/sortit-till-you-make-it) | Unijam 2021 | **Developer**

:pencil2: - I also do **Pixel Art** when I have time. I've been part of a lot of awesome video game projects lately, be it as a graphic designer or developer. Come have a look, I post most of my drawings [here](https://www.reddit.com/user/K0huro/posts/).. I'm using [Aseprite](https://www.aseprite.org/) which is a fantastic tool for Pixel Art.

:video_game: - Passioned about video games, [check it out](https://ggapp.io/Kohuro/collection)!

# **Overview of my experience**

<br/>

I joined the team working on [Mockoon](https://mockoon.com/) twice for internships during the Summers of 2021 and 2022. **Mockoon** is an open-source dev tool that helps you design and mock APIs in seconds. This was the opportunity to give a hand to this promising project and deliver major features (like data buckets) to thousands of developers worldwide.

After a successful six months internship, I was hired at Ankama, as part of the server team on the game Dofus TOUCH. amongst other things, I have been in charge of the -long-awaited- revamp of our Player versus Player feature which resulted in more than a hundred thousand matches on launch day. Through this task, I tackled subjects such as matchmaking and ranking algorithms.

Aside from developing features and fixing bugs, I as a backend dev also have the responsibility of maintaining servers and shipping new changes. As such, I have been regularly running dev ops processes on servers hosting tens of thousands of unique players daily. 

# **My video game projects**

### **Top Secret File, Master's final project**

![clip (6) (1)](https://user-images.githubusercontent.com/41008899/204225375-31dedd04-91ac-44fc-a277-ca30a1d3a0db.gif)

Top Secret File is a game in the making for the sake of our end-of-the-year project. You are a Jovian investigator, sent to an infamous Megapolis on Triton. You are sent there to stop an ex-military who has been abusing his reality-altering powers. Use your powers to see through the lies of the city and fulfil your mission. Your powers allow you to bend reality at your will, by modifying game files in your file explorer.

The objective of this academic project is to **showcase the technical capabilities** mastered during our formation in the **Video Games and Digital Interaction** Master. In this project, I take the role of technical artist/art director and developer: I am in charge of the production and integration of our 2D-pixel art assets and get to make the decisions regarding the art choices. In parallel, we also aim at sharing the development tasks equally and, as such, I have also taken some technical tasks such as Tilemap-driven movement, 2D Collision mechanics and so on. 

> **Half-project Update - November 2022**

At this point, we managed to set up the base gameplay for our game. As of now, the player can wander around in our world, interact with his environment and modify/delete/create files in his file explorer to modify his surroundings. 

I started the project by working on the player movement. I wanted the player to remain aligned with the tilemap to mimic the feeling of 2D Pokemon games. I thought it would be set and done in a few hours but it actually took some thinking: I wanted the player to be able to input a direction, then another and, when releasing the second direction, resume going in the first direction. That forced me to introduce a pile system in which I would store inputs in chronological order and retrieve which key was released to remove the corresponding input. In a way, I guess that doesn't make it a real pile as I can remove any item I want regardless of its position. Does that exist? Most likely. It is maybe called a FIMOASP Pile.... FIMOASP standing for **First in, Maybe out at some point** obviously.

In the meantime, I achieved to draw the assets for the office, our starting scene. I tinkered a bit with post-processing and dynamic 2D lighting to achieve the office scene. Every piece of furniture is separated and interactable! I have also the first assets for the spaceport but this part isn't completed yet so I will work on it some more before posting it. 

![player-movement-front](https://cdn.discordapp.com/attachments/1045427891430752276/1046481469746462740/player.gif)

Right now, I am working on an interesting piece of game design and code: we have struggled a bit on the question of what to do when a player deletes a file linked to an important gameObject. We thought that just restoring the files would be frustrating to the player. I suggested creating a scene where all the deleted gameObjects would appear and where the player could wander and interact with items to restore them to their pre-deletion state. Just like the bin in your OS! We called it the Cosmic Bin! I'll share more when it is implemented. 

> **Second project Update - January 2023**

The Cosmic Bin is up and running! I am particularly fond of the aesthetics of the scene! I'll let you judge it by yourself! 

![cosmicbin](https://user-images.githubusercontent.com/41008899/221442823-319c5daf-559b-4ef3-ad22-b6c907a38889.gif)

The ripple effect was realised in shadergraph by adapting a tutorial found online. The main difficulty was to set the player as the epicentre of the ripple but also to find a way for the ripple to flow through the whole viewport and not simultaneously on each tile of the tilemap. 

You may wonder why a dog is wandering in the unending void. Play the game to find out! 

We are closing in on the end of the project. At this point, our classes are almost over and we will have a few weeks to work on the project full-time.

> **End of project Update - February 2023**

After three weeks of intensive full time on the project, the game is playable [here](https://akasuna.itch.io/the-neptune-records)! The whole team is quite exhausted but we are proud of the work behind us. During this last rush, I worked as a full-time artist. Indeed, by the end, the project needed too many assets for me to help my colleagues with the development. There is not much to talk about in this field so I will let a few screenshots do the talking for me.

Note that while I say I did not take part in the development of the game during this final rush it is not exactly true. I was, in a way, responsible for the artistic coherence of the environment, and to add some depth to our work, I developed some tools. Amongst others, I created a custom fader (see below) that hides part of the environment behind which the player might go.

![fader](https://user-images.githubusercontent.com/41008899/221443892-140ed57e-6c8d-49df-977e-210a06273850.gif)  
*The entrance of the office, with the use of our fader as a way to preserve the integrity of the building design while remaining comprehensible*

![image](https://user-images.githubusercontent.com/41008899/221443443-0bfd54ea-43cd-48a3-85ac-c30f4bb3907e.png)
*Kannath's bar, the first place you will got o start your investigation (go enjoy its musical atmosphere)!*

![image](https://user-images.githubusercontent.com/41008899/221443504-9f4aff02-00ec-4d73-b7ed-3f91f677b344.png)
*The dark alley you come out of when first arriving in the Plaza, our biggest environment, working as a hub*

![image](https://user-images.githubusercontent.com/41008899/221443587-3506d792-ef92-41e3-ba3f-20d3de360cb0.png)
*A little piece of a room in the factory*

By the way, we also found a name for the game! **The Neptune Records - a folded reality**   
Sounds cool doesn't it? Did you get the *subtle* play on words with folded meaning modified, and manipulated but also referring to us using folders and files to modify reality ?? Yeah, we are quite proud! 

*Also a subtitle makes it more convenient for a sequel...*

> **Technologies used:** Unity/C#, Miro, Aseprite, Git  
>**Team size:** 5  
>**Project duration:** 6 months    
>**Tasks:** Tilemap management, 2D collision, file surveying and processing, 

### **Lost in the Depths, Unijam 2022 submission (won the Ubisoft sponsored jury's price 🥳)**

<br/>

<img src="https://img.itch.zone/aW1hZ2UvMTc5ODcxMi8xMDU3NTEwMC5wbmc=/original/Jlx9dP.png" width="50%" height="50%">

Lost in the Depths is a single-player game where your objective is to dig deep into the ground of an unknown planet to find its gem. You will have to dwell in the depths of a **procedurally generated** map, discover its biomes and collect tons of different ores. As you dig your way down, oxygen will soon become an issue and you will have to plan accordingly. To do so, you can go back to your base and put your ores to use to upgrade your gear and craft oxygen relays.

This project won the **jury price of the Unijam** and team members received rewards from **Ubisoft Annecy**, one of the sponsors of the event.

I took part in this jam as **developer**, and I essentially developed the procedural generation of the map. In a way, our game takes from **Terraria** as you evolve in a 2D world and do things such as mining and crafting. But it also takes from 3D cubic/voxel games such as Minecraft as our 2D world is really a flat 3D scene. 

**Development insights**

It has been an absolute blast to work on the procedural generation! Seeing our flat map gradually be filled with details: biome variations depending on the depth, unbreakable limits, ore generation, ore generation as veins, ore blending depending on the biome etc.

<img width="628" alt="Capture d’écran 2022-11-23 174751" src="https://user-images.githubusercontent.com/41008899/203604819-808d4f66-c131-43e3-9a23-8c7a22cbff46.png">

As you can see, the map is divided vertically into biomes. All three types of ore can be found in pretty much any biome. Yet, their apparition rate follows a Gaussian probability centred on the average height of the biome. There is also a script that group the ores together as veins with variable sizes.

We discussed adding caves and thought that if not done properly, caves would pretty much look like generation errors. Yet, when we added the elevator, it appeared that having a small cavity at the bottom of the elevator shaft would offer the player some space. As such, I implemented a method to dig out cavities based on several properties.

<img width="624" alt="Capture d’écran 2022-11-23 180129" src="https://user-images.githubusercontent.com/41008899/203606153-060a9e4e-421e-4d89-952e-bfc0c0d6ef84.png">

>**Technologies used:** Unity/C#, Git  
>**Team size:** 7  
>**Project duration:** 48h    
>**Tasks:** Procedurally generated 3D map with biomes, ore veins and caves, 3D assets integration, Shaders ...   

### **Adventures under the sea, a C++ school project**

<br/>

<img src="https://user-images.githubusercontent.com/41008899/188661302-7964cf80-6fd9-4c19-91b1-cd6c5ce0ec22.png" width="50%" height="50%">

Adventures under the sea was a **school project** made to learn the basics of c++. This project was a co-realised with [Henri Nomico](https://github.com/BiscuitPrime). This game is heavily inspired by [Into the Breach](https://store.steampowered.com/app/590380/Into_the_Breach/) and uses librairies such as SFML and ImGUI. All the sprites are handmade. 

Early in the project, I chose to go with an isometric pixel art style for our game. We tried using TMX to load our tilemap but it did not support isometric tilemaps. As such, I had to develop **a homemade system to convert orthographic to isometric coordinates** consistently. After a few hours of headhake, going through all the documentation available on the matter, I managed to get a convincing formula ! 

<img src="https://clintbellanger.net/articles/isometric_math/images/screen_coordinates.png" width="50%" height="50%">

It worked particularly well and even left me some time to work on a **xml serialization our the tilemaps for our levels**. In the end, all you had to do was write a short xml stating which coordinates had to be drawn with which type of tile, add some tags for enemies and the level was automatically generated !  

I also worked my way out of my comfort zone and experimented with the **Strategy design pattern**. It wasn't obvious to implement at first, but after reading some articles on the subject it became more instinctive. Now our ennemies exhibit different behavior depending on the state of the game. We did not have time to implement more than the basic strategies (fleeing, rushing to attack the player and so on.) but the system was designed to take into account as many possible strategies as we wanted. 

Check out the game [here](https://github.com/BiscuitPrime/Adventures-Under-The-Sea).

>**Technologies used:** C++ (yep, no game engine this time! 😎), Git   
>**Team size:** 2  
>**Project duration:** 2 weeks    
>**Tasks:** Isometric tilemap generation, strategy design pattern for enemy behavior,pixel art assets production and integration  

<br/>

### **Steppe by step, Etiolles Archeologic Game Jam submission**

<br/>

<img src="https://user-images.githubusercontent.com/41008899/194828151-81457301-b07a-49a2-ae49-9b22ab2412d9.png" width="50%" height="50%">

Steppe by Step is a single player game where you control a tribe of hunter-gatherers through the prehistorical steppe in search of traces that could lead you towards the herd of reindeer roaming this place. This game was made during the Archeological Game Jam that took place in the C19 incubator in Evry, France in partnership with the excavation site of Etiolles, France. 

I took part in this Jam as **developer** this time. As expected, the weekend was not exactly smooth sailing and we encountered many hurdles from trying to work with [FMOD](https://www.fmod.com/) to using data issued by the archeologists to add realistic details. FMOD has been an absolute nightmare to integrate into our project and brought the dreaded git issues. I swear, sometimes, it feels like Git has been built on a cursed graveyard. However, FMOD turned out to be an impressive tool! It allowed our sound designers to produce adaptative sounds and music, and, on our end, to integrate them very intuitively. 

This Game Jam was also an opportunity for me to get ahold of the basics of pathfinding. I was in charge of making our characters move in a 3D world generated using real topographic data. I would have loved to have more time to polish my system but it clearly did the job! 

During the Game Jam, I got to meet and befriend two amazing sound designers and an archaeologist. This was a truly rich human experience! 

Play the game on [Itch.io](https://akasuna.itch.io/steppe-by-step)!
Check out the game [here](https://github.com/Hugo-Carbiener/Steppe-by-step).

>**Technologies used:** Unity/C#, FMOD, Git     
>**Team size:** 6  
>**Project duration:** 48h  
>**Tasks:** Pathfinding, FMOD and sound integration, 3D asset integration, mathematics and geometry in a 3D space  

<br/>

### **Geckolot, 2022 Global Game Jam submission**

<br/>

<img src="https://user-images.githubusercontent.com/41008899/153009120-aeb54a6e-a5ba-48bc-9e63-17574a7d7fa1.png" width="50%" height="50%">

Geckolot is a two-player platformer inspired by the theme **Duality** for the 2022 Global Game Jam. You can either control an extroverted axolotl with attraction powers or an introverted gecko that tends to push others away. 

As lead graphist, I produced most of the pixel art assets you can see (including the logo I am so proud of 😝). But while that was nice and rewarding, I also got the opportunity to introduce a friend, in junior year, to pixel art and to give her some tips and tricks. She loved it and I was able to assist her with some old examples of work and pieces of advice. In the end, she produced amazing assets that made our game even better-looking!

Play the game on [Itchi.io](https://mathieu-coutant.itch.io/geckolot) or check out our project in more detail [here](https://github.com/Hugo-Carbiener/Geckolot)!

(No but really... go check it out... it's really cool! :eyes:)

>**Technologies used:** C#/Unity, Aseprite, Git     
>**Team size:** 7   
>**Project duration:** 48h    
>**Tasks:** 2D asset production and integration, project management in the graphist team     

<br/>

### **Dungeon Speaker, java school project**

<br/>

<img src="https://user-images.githubusercontent.com/41008899/193330976-6a4008de-39e4-4b4e-b760-c111f5825708.png" width="50%" height="50%">

**Dungeon Speaker** is a *text-based* dungeon crawler inspired from [AI Dungeon](https://play.aidungeon.io/). We worked on it as a team of four junior students at Telecom Sudparis for our **oriented object programming** class. Sadly, being our first game, the build was somewhat messy and is not playable anymore. 

the first thing I implemented was the dungeon generation system. Without really knowing it, I coded a procedural generation algorithm to generate our dungeon. It took the form of a non-binary tree where each room could lead to other rooms and so on. Room were also procedurally seasonned with monsters, loot and random events with which the player could interact. The achievement I was the most proud of was the map display system. As mentioned, the game was text-based, so, in text, I managed to display the procedurally generated tree of rooms and corridors.

Our game also relied on **Natural Language Processing** (NLP), to process the sentence the player would write and translate them into actions to influence the world. We struggled a lot to get any results at first, but by slowly working our way up, dividing our task, we managed to get more and more bricks done. In the end, we had a convincing system that processed the player sentences, isolated the verbs and objects and could accurately starting the corresponding gameplay sequences.

>**Technologies used:** Java, Python, Git  
>**Team size:** 4  
>**Project duration:** 4 months  
>**Tasks:** Natural Language Processing, Dungeon, monster and weapon procedural generation  

<br/>

### **Neon Dice, 2022 GMTK Game Jam submission**

<br/>

<img src="https://user-images.githubusercontent.com/41008899/188655584-762db231-84c5-4257-bd18-8f34a10e9bef.gif" width="50%" height="50%">

Neon Dice is a two-player **hack n' slash** inspired by the theme **Roll of the Dice** for the 2022 GMTK Game Jam. Each player controls one of the two dice. Each face of your dice corresponds to a particular weapon with a fixed amount of ammunition. If you run out of ammo, you will have to regroup with your teammate so they can roll you. But beware, if you get rolled, your weapon will most likely change as well, so be prepared!   

Despite a few issues during the development, the game turned out according to our expectations and I am particularly proud of the art and of the workflow I managed to achieve. 

It is fantastic to discover new tools that drastically enhance your **workflow**. Well, that is a particularly good example. I am using **Aseprite** to draw my pixel-art assets and amongst many fantastic tools, aseprite offers a **scripting API**. Browsing itch.io, I found a script which, for a few dollars, would allow me to export parts of my drawing in a single click (and as a sprite sheet if I was drawing animations)! No more need to single out every asset and its variations in a separate file and then export it, now this whole process is instant. Even better, Unity keeps a reference of your sprite and the modifications applied and links it to the sprite file. So as long as your export with the same name as previously, all the modifications will be instantly applied and all the objects and prefabs will have the new sprite. What does all this paragraph mean? I can redraw some assets, make some slight modifications, anything ... and in a single click, all my sprites are updated and remain in the right place in Unity, I am super proud of my pipeline. 

Play the game on [Itchi.io](https://flegmatik-surf.itch.io/neon-dice).

>**Technologies used:** C#/Unity, Aseprite, Git     
>**Team size:** 7   
>**Project duration:** 48h    
>**Tasks:** 2D asset production and integration  

<br/>

### **Sort'it 'till you make it, 2021 Unijam project submission**

<br/>

<img src="https://img.itch.zone/aW1hZ2UvMTI3NjU4Ny83NDM4NjQyLmpwZw==/original/qgxAdK.jpg" width="50%" height="50%">

Sort'it 'till you make it was the game made during my first ever Game Jam, 2021 **Unijam**. The aim is to sort trash properly while putting aside some items to sell them on the black market for extra cash. Still, you must not get caught by your boss while stealing trash.   

The first thing I implemented was a 3D drag-and-drop system. It was real math-heavy and took me a little while, but the result was satisfying and held the base of our whole game.

While the scope was very optimistic, we still managed to produce a playable game. It lacks polish but taught us to define a clear and concise scope when starting a Jam.

Play the game on [Itchi.io](https://skizaat.itch.io/sortit-till-you-make-it).

>**Technologies used:** C#/Unity, Blender, Git   
>**Team size:** 6   
>**Project duration:** 48h      
>**Tasks:** 3D Drag and drop system, 3D physics, Camera management 

<br/>

--- 

# **I also do some Pixel Art ! - Here is some of my [work](https://www.reddit.com/user/K0huro)**


<br/>

### **The conclusion to a three-piece work as a tribute to the game [Othercide](https://store.steampowered.com/app/798490/Othercide/)**

<br/>

<img src="https://user-images.githubusercontent.com/41008899/153001891-8f25ea75-5064-4e42-8d0a-a68eb1f20d07.gif" width="50%" height="50%">

<br/>

### **An attempt at *sub-pixel animation*** 

<br/>

<img src="https://user-images.githubusercontent.com/41008899/193759328-2726432d-dc33-43d1-8511-0932a414efd4.gif" width="50%" height="50%">

<br/>

 ### **Some character designing**

<br/>

<img src="https://user-images.githubusercontent.com/41008899/193759600-35e97ce7-7466-4a56-97b8-c07234dc3846.png" width="50%" height="50%">
