
## Masonry
okay now lets add a new Building which is Masonry create a placement button function and tell me the on click setup. then the Masonry will work like this one masonry max capacity will be 6 and their work will be if the Building Health get reduce below 40 then go and play the construction loop i.e. the Builders count based on the building size will go to the building play the Hammering the construction smoke will play and the NPC Scroller will play the time taken will be the Half of the Building construction time and once complete the no fire risk will go to the max 100% and building health will also become 100%

## Bakery
Okay now i want to Create a Bakery where the NPC Farmer will create Bread for the Home.

The process will be:-  
  
- First we will setup the Bakery Building just like other Buildings this will require 2 NPC Builder and 60 Second to be completely build and split tile accordingly means if 2 workers reach they will take half of remaining time.  

- The NPC Now no longer will store wheat to the Home they will store the wheat in the Bakery. The bakery will use the wheat and create the Bread.  

- Use the Main Panel in which we have UpKeep which we alredy had assigned in the StatsPanelUI that will show the Wheat = Bread Image card and there will be a count down of 5 second to create a Bread create a bool and make this process automatic so the the NPC will keep creating the Bread.  

- When i will place a bakery the Builder will Build it and create a new job in priority list as 2 NPC Job Create a new Job "Chef" in the Job Priority Panel 1 bakery will have 2 chef and they will create 2 bread in 5 second means 1 bread each increase the Total Number of Breads. the Bakery Panel will show the Total count in the UI Panel the Current bakery Building is holding(2 NPC will go inside the Bakery and stay there playing the IsDoing animation don't hide the NPC sprite).Also Create a Delivery Girl Job also their work will be to take the Bread from the Bakery and store it to all the Required houses each shop can have 2 Delivery Girls(this will be handled by the same carrying animation) one the work has been assigned as Delivery Girl thet cannot do farming or any other work except Fire Extinguisher.  
  
- The UI Panel Thing when the player Click the Building then it will show the main Panel. it will also zoom in to the Bakery using the Chinamachine camera to 2 and fade the Building by reducing its alpha so the we can see inside the Bakery The Chef playing the Doing Animation.

This is my Plan now i want you to analyses my plan and make a Plan that can Fit in my game. keep all the required variables like the chef count in bakery the Delivery Boy Count per Bakery, The time it will take to Create Bread and the Number of wheat it require to create one Bread keep 1 wheat 1 Bread as default for now. Do not do any coading this is a very big task we should plan it and breake it into multiple steps so that game don't break.




## Animator Setup

lets First Create animator again here is my animation clips for both the Types of my NPC now help me create an animator with same type Clips for both NPC which we are going to use in our Game  
  
we are going to use the Clips  
- Walk - for walking  
- Running - 
- Watering -
- Swimming
- Roll - role with some delay when is in hurry. rolling will make the movement speed to normal walking speed *3* when rolling true else the normal speed which is already assigns
- casting - when throwing the fishing rope to the water.
- Waiting - for Fishing Waiting with fishing rope inside the water
- reeling - when pulling the fishing rope 
- caught - when fish caught
- mining - will be used for farming
- Jump- This will be played when the moving from the one level floor to another level floor 
- idle 
- attack - for fighting
- hurt - we will add the fight in the future
- hammering - To Build or destroy anything 
- doing - for the chef
- carry -
- dig - for planting
- Death - when NPC Dies
- axe - for chopping the wood.


attack 
mining
reelong 
roll
walk