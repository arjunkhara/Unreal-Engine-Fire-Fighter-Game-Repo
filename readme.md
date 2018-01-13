# FireFighterGame: Project Management Log
This is a group project for Arjun Khara, Daniel Nicholson, and Sarah Chalk (Goldsmiths College - University of London) 2017 – 2018 for our game project: Fire Fighters. This new repo was created to manage and refine our game project for Introduction to Modelling and Introduction to Programming. The due date for this project is 10 December 2017. Several tasks have been identified and are in the pipeline. By Thursday, 23 November 2017, Arjun and Dan will have finished modelling the fire tanks, pipe, nozzles, and gloved hands, which contribute more than 75% of the modelling assets required for this project.

<h4>Progress Report</h4>:For this project we will be using blueprints in Unreal to create a game where the player fights fires of different varieties (Gas, Electric, wood). The player will have to manage which extinguishing materials they have to use to put out the fire. The incorrect extinguisher will make the fire grow, the correct one will shrink until it is extinguished.

<h4>Project Team:</h4>
This project has three members. While all members' responsibilities will overlap with the others, each has been assigned a role for responsibility and oversight for this project. Role assignment is: Project Manager; Project Programmer; Project Modeller. 

The Project Manager is responsible for the overall concept of the game, keeping the project on time and within resources, overseeing the effectiveness of all project meetings and decisions, and ensuring the team meets all deliverables towards the final vision of the game.

The Project Programmer is responsible for the integrity of the codebase and debugging, and will check on the Blueprints in Unreal Engine. The Project Programmer will also be responsible for the final delivery of the code, and conduct code quality assurance audits.

The Project Modeller is responsible for the integrity of the models and assets that will be included in the game, and ensure that the models perform as required during animation and procedural development. The Project Modeller will also be responsible for the final delivery of the look and feel of the game.

• Project Manager: Arjun Khara<br/>
• Project Modeller: Daniel Nicholson<br/>
• Project Programmer: Sarah Chalk<br/>

<h4>Progress Report</h4>: The project team will meet this Thursday (30 November 2017) and again on Saturday (2 December 2017) to combine all the assets we have modelled so far, and begin to integrate these into Blueprints. We are expecting all modelling to be completed by Thursday evening, 30 November 2017. Saturday, (2 December 2017) will be spent building out the main sequences of the project and for rapid prototyping of the game to address any discrepancies and concerns, as well as to evaluate what works and what needs to be changed. 

<h4>Progress Report</h4>: Dan has figured out how to use GitLFS with GitBash to store files and upload them, in Blueprint format. Dan will teach the rest of the team how to make this work across the entire project during our weekly Saturday meeting on 2 December 2017. We will use this method together with existing procedures to begin committing and sharing our file contributions across the project.

<h4>Progress Report</h4>: We have managed to use Blueprints to create a number of effects for our game. Dan has worked out the AI to make objects come towards the player, which is an essential part of gameplay. Arjun has managed to work out the fire effects and colours, and integrated the dousing effects for when the object is sprayed with a suppressant. Arjun and Dan are now working off Dan's computer to integrate the separate Blueprints into a single logic flow that will control game play. We have  created a successful mock up of the environment with placeholders for the FBX assets. We are working on importing and integrating these assets, once the Blueprints codes and logic flows are in place. We are aiming to have a demo ready in time for the next presentation on Friday, 9 December 2017, where we will showcase the basic game play as an MVP, complete with dynamics, mechanics, and interaction options. We are also working on an introduction movie before the game begins, to familiarise players with the game rules and expectations.

<h4>Progress Board</h4>: The progress board (image below) contains all of the project's tasks, categorised into the various components of the game-build. As of 2 December 2017, the tasks that have been completed are marked with a green scratch line. The tasks remaining are marked with a red asterisk. Our next progress meeting is on 7 December 2017 where the group will come together to revisit our current state and evaluate the extent of work required to complete this game. ![alt tag](https://github.com/arjunkhara/Unreal-Engine-Fire-Fighter-Game-Repo/blob/master/weekly-progress-pitch/Progress-Board-2-December-2017.JPG "Progress Board Review: 2 December 2017")

<h4>Progress Report</h4>: Based on the use of a variable to switch between suppressants, the need for multiple nozzles in the game is now moot. Dan has figured out a way to use a variable to switch between the three suppressants, therefore eliminating any animation required to demonstrate the switching action. Therefore only one nozzle will be used within the game, from which the different suppressant types will flow. The tanks will continue to remain in the game and will be positioned on either side of the player rather than behind the player. Initial demos of the game reflect this as an advantage to gameplay.

<hr/>

<h2>Introduction to Audio</h2>

In a game we want to communicate sound from a virtual world a real human listener. Therefore a monoaural sound (not stereo) is required within a 3D location. A virtual microphone called a listener (usually attached to a character) is what creates the changes in sound a 3D-simulated world.To create sound, a sound clip is required. These clips are cut into smaller pieces and pieced together to create a smooth output.

The basic components of sound are: 3D position; velocity (Doppler effect); ear separation; ear geometry; and the speaker system in use (e.g. 5.1 speaker system, Dolby Surround Sound, headphones etc.). How one is experiencing / hearing the sound affects how the sound is designed. Sound travel in waves and these waves move in phases, which regulates how the sound is experienced. 

Sounds coming from up or down are experienced differently. Sound coming from top comes directly to the listener whereas sound coming from down is absorbed into the ground. In games, this effect is created by using filters. Similarly, sound spaces create different experiences. In a church the sound is different from that in cupboard. The time delay is an important factor, which is why church music is played slower. Likewise, a football stadium will have a different sound speed and will correspondingly affect the acoustic.

Sound spaces are measured using chirps and clicks. Once these chirps and clicks have been configured, the point audio effects can be applied. The high pass filter are the high sounds that can be heard (for example listening to someone's headphones in a train). The low pass filter are the low sounds that can be heard (for example the old telephone conversations). A chorus effect makes a single voice sound like many. The echo or reverb effect is a the same sound played back with a deliberate delay. Changing from one sound to another is never a hard cut. A cross-fade slowly blends one sound into another. Likewise, a pitch-shift slowly changes the pitch. Cutting off a sound abruptly creates a click, which is not appropriate for games.

The Doppler effect is the relative compression and expansion of sound waves juxtaposed with the position of the listener. The Doppler effect is essential for realistic sound effects and audio composition. 

Audio composition: to make a range of sounds, lots of blending is required. Engines at 1000 RPM and engines at 1500 RPM can be blended. Different filters are used with different microphones attached to all the points around, say a car. Ambient sounds create mood in the game. Subtle changes in the ambient sound work as signals for players. Ambient sounds are particularly important for horror and survival game genres.

In Unreal Engine, there are special objects for dialog construction, example the speaker or the target. Cinematics are also used to create these sound effects in Unreal Engine. Subtle sounds filling an environment are typically a good way to make gameplay more interesting. Sound sources and listeners can be placed around the scene to let the player experience a more realistic gameplay.

<hr/>

<h4>Project Team</h4>: Sarah Chalk has officially withdrawn from the group project and module, owing to personal reasons. The project will continue under the direction of Daniel and Arjun, who will manage the modelling assets and Blueprints in Unreal. We are aiming to complete the entire game project by 13 December 2017, then leave a time lead for further refinements and add-ons.

<h4>Progress Report</h4>: The group (consiting of Dan and Arjun) has managed to establish complete GitHub integration for all files (including Blueprints, images, FBX assets, and records and documentation). Both members now have access to each other's individual Blueprint files and contributions and are working together to schedule who works when and on what part of the project, to prevent overlap or overwriting of contributions. The essential 'don't break the build mentality' has set in. This group meeting was on 9 December 2017. So far the group is on track to have a working prototype / MVP for the 13 December 2017 target deadline.

<h4>Progress Report</h4>: The group (consiting of Dan and Arjun) has built the first working prototype of the Fire Fighter game. We are also considering the final name for the game - Haunted Hose. The working prototype features the player with the hose firing a specific projectile (the suppressant) at an object that is coming towards the player. In five hits (indexed from 0 to 4) the object will be destroyed. The prototype works perfectly. The next stage will be to substitute the real FBX assets (already uploaded) with the object placeholders. Report filed on 13 December 2017.

<h4>Progress Report</h4>: Owing to challenges with the GitHub LFS repo and consequent conflict of files and permission restrictions, a separate repo is also being maintained for the blueprint files. Current repos of each team member, i.e. Arjun and Dan, are in tact and working fine but each has sporadic permissions issues which cannot be resolved in the limited timeframe and number of members in this team, i.e. 2. As a result, the team opted to pay for and create a second repo with LFS capability and restrict back up development files (including blueprints) to that repo as well as to this current one.
