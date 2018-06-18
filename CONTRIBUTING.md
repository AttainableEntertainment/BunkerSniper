# Contributing Guide 



### Getting started 
You can fork the project on your repository, clone it to your computer and open it in unreal engine.


## Working in the issues tab
Issues are the main communication and organizing system we use in are projects. They are used to contribute new ideas to the project, organizing tasks for people to do, ask questions and learning.   
* Check exsisting issues before creating a new issue 
* If issue is a new feature make sure it confirms with the vision of the game or the game design document 
* Use labels to help orgranize issues
* Using search filters for labels can be really helpful, such as searching for all the issues for blueprint programming 



## Non-Development contributions  
You can help out the project with no game development experience. Heres some of the things you can do.
* Spread the word out about us, get more people involved helping us, tell your friends, write blog posts.
* Contribute to the documentation, you can edit files in the repository such as the readme, contributing and game design document.  
* Play testing the software, submitting issues, problems, bugs, ideas 
* Submitting new ideas, questions or new tasks through issues 



## Development contributions 

### How to contribute to the code 
* Go to the issues tab to find issues/tasks you want to work on. 
* Create pull request when your able to solve an issue 

### Creating a pull request 
* Each pull request should be focusing on solving an issue 
* Check to make sure pull request is unique 
* Make sure to follow the standards for organizing files and folders

### Standards for organizing the repository 
* All files will be put in the folder of its type example would be blueprints in the blueprints folder or meshs in the meshs folder
* Folders may be created inside the main type folder to help organize large amount of files into sub folders. Example in folder blueprints, added a folder named Blueprints_AI for the ai blueprints or BP_AI for short 
* Naming conventions for folders and files must follow the standard type_subtype_nameOfFile examples BP_Gun or BP_Weapons_Gun

### Standards for working within levels 
* Name convention for levels are Level_nameOFLevel_LevelComponent example Level_theTemple_Lighting 
* Each level has its own folder in the main levels folder named Level_nameOFlevel 
* Each main level has a blank file level named Level_nameOFLevel_main, this is used as the main persistant level which is completely blank except that it contains all the level components inside of it. Note main level must have proper level streaming settings to load level components 
* Each component of a level must be organzing inside its own level dedicated to all simular types examples lighting, sound, blueprints, bspLayout, meshs. Each will follow the standard naming conventions and will be added to the main Level in which it belongs to with the proper level streaming 
* For large levels such as open world games, the main level can contain another main level for further organization example, Level_nameOFWorld_nameOFSection_SectionComponent 



