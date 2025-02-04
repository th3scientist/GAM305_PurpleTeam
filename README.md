# GAM305_PurpleTeam Project Log Assignments

## Scenario: First Person Simulation

### Brainstorm:
* Theme: Dungeon Crawler Action Game
* Pickups: Bow, Sword, and arrow pickups in the level
* Mechanical Pulley Elevators
* Teleporters with fantasy magic theming
* Cast a spell to see Enemy locations
* Enemy slimes, skeletons, and rats
* Slimes will split apart when killed


## Team Roles

* Team Lead: Matt Fiske
* Game Programmer: Bug McCormick
* Game Programmer: Austen Carroll
* Level Design: Robert Clough
* Artist: Donald Long
* UI/UX Programmer: Matt Fiske
  
#### Schedule: Weekly meetings every Wednesday
#### Preferred Communcation: Discord

## Development Timeline:
1. Alpha Phase 1 to be completed by January 25th.
2. Alpha Phase 2 to be completed by February 1st.
3. Beta to be completed by Feabruary 8th.
4. Final release to be completed by February 15th.

### Alpha Build:
#### Phase 1: 
* Level Block Out
* Player Character Functionality
* Enemy Functionality
* Bow, Sword, and Arrow pickups functionality
#### Phase 2: 
* Teleporter Functionality
* Elevator Functionality
* Player UI/HUD
* Game Lighting Objects
* Vision Spell Functionality
* Slime Enemy Split Apart Feature
* Level Object and Enemy Placement
* Main Menu Functionality

### Beta Build:
* Enemy 3D Models
  * Skeleton Model
  * Slime Model
  * Rat Model
* Models for Sword, Bow, and Arrow pickups
* Level Lighting
* Level Texturing
* Elevator Models/art
* Teleporter Effects/art
* UI/HUD Art
* Vision Spell Effects

### Final Release:
* Player Animations 
* Enemy Animations
* Main Menu Art
* Level Lighting Pass 2
* Level Texturing Pass 2

## Test Plan Overview:
### Preproduction Play Testing:
To ensure a quality product, multiple stages of testing will take place for each feature. First, developers will take steps to test that the feature's functionality is working as intended before the feature is deemed "complete" and merged with the codebase. To test this, developers will spend 5-10 minutes, or however long is necessary, checking that the feature works as intended and there are no bugs which are readily apparent. If major bugs are found, the developer may need to fix them before they can deem the feature complete, depending on their discretion, the time restraints, and the severity of the bug. The next testing step will take place after the feature is merged. After a feature is merged, the team lead will conduct the same process. The team lead will check that the feature works as intended, no bugs are readily apparent, and that the feature functions correctly with any other features. Any bugs found at this step will be added to a separate bug sheet in the shared google sheet traceability matrix. These two steps constitute the testing that will take place during preproduction.

### Demo Testing:
Rigorous full length play tests will be conducted by the team lead and any other available developers to find bugs before a demo build is made available to the marketing team. To ensure a quality demo build, and with time restraints in mind, the team lead will have discretion over which bugs are "major" and need to be fixed before the demo is made available, and which are "minor" and could be left in for the demo build. These determinations will be tracked in the shared google sheet bug traceability matrix. Considerations for how the game may look to the public will be taken into account, bugs that some may consider to be minor, like typos or incorrect animations will be priority fixes for a demo release.

### Code Release Testing:
A similar process to demo testing will be followed for code releases, but instead of taking a marketing perspective into account, bugs that may restrict progress in the next stage of development will be considered "major." The goal of play testing and bug fixing for a major code release will prioritize the speed of future development. Bugs that are major and should be fixed are those which could restrict future development, such as issues with core features like the player or enemy behavior. Minor bugs such as typos or incorrect damage values will not need to be fixed unless the release in question is the final public release.

### Bug Reporting and Tracking, and Test Plan Updates:
Bugs will be tracked using a shared google sheet which contains our feature matrix. Each developer is responsible for adding any bugs they find to the sheet and informaing the team lead of their additions. The team lead will review the bug reports and ensure bugs are being worked on as development progresses. Developers and the team lead will update the sheet as bugs are fixed. The team is in constant communications, any changes made to features will be relayed to the team lead who will update the test plan accordingly.

### Feature Test Schedule (Tasks are In Order):
#### Prior to Alpha Build:
1. Player Attacks, Movement, Hitboxes, Pickup Interactions
2. Enemy Attacks, Movement, Hitboxes, Pickup Interactions
3. Level navigability for player and enemies, teleporter and elevator
4. Player HUD Functionality
5. Full game play test

#### Prior to Beta Build:
1. Enemy Models
2. Level lighting, texturing
3. Bow and Sword Model, integration with player
4. Main Menu
5. Full game play test

#### Prior to Final Release:
1. Enemy Animations
2. Player Animations
3. Level lighting
4. Full game play test

### Feature Checklist:
* Enemies:
  * Attacks
  * Movement
  * Behavior Tree
  * Perception
  * Animations
  * 3d Model
  * Slime split apart
* Pickups:
  * Player Functionality
  * Textures and Model
  * Level placement
* Level:
  * Lighting
  * Player navigability
  * Enemy navigability
  * Elevator movement
  * Teleporter functionality
* Player
  * Attack animations
  * Attack hitboxes
  * Damage enemies
  * Take damaege
  * Movement
  * Interact with pickups
  * HUD Functionality
    * Health
    * Ammo Count
    * Crosshair
    * Vision Spell
* Main Menu Functions
  * View Credits
  * Exit Game
  * Start Game


### Project Log Team Reflection:
#### What parts of the testing process did the team perceive to go well?
Communication between the level designer and game programmer in terms of player height went well. 
#### How were bugs identified and corrected?
The level designer was able to identify bugs with the player's height as they traversed the level. They were able to communicate with the game programmer to rectify those bugs swiftly and fix them so that the level design process could continue.
#### In terms of the QA and testing process, what would you do differently to improve the process?
To improve our QA and testing process, we could improve the communication between programmers to better understand each other's work schedules and deadlines. By improving our understanding of the work timeline, we could allocate more time for QA and testing.
#### What tools (chosen in Module Two) did you find successful in the development of your Alpha project? Why?
The feature matrix spreadsheet was a useful tool for tracking our progress as development progresses, as we go forward we should make sure it's updated frequently so that developers understand which tasks are complete and which are yet to be finished.
#### Were there any tools or techniques that you did not find helpful in the success of your project development? Why?
There weren't any tools we used that we found to be unhelpful, our only issue was making use of the tools we have successfully and to a full extent.
#### How did the team approach to the initial analysis of the game design document contribute to the decision to use these tools and techniques?
The team's approach was to plan out much of the game before work began using a feature matrix on google spreadsheets. This approach gave us a comprehensive overview of the project, allowing us to schedule and assign tasks for later development stages. Since we did not achieve our alpha goals, going forward we plan to more rigorously use these tools. By maintaining constant communication and scheduling our tasks we hope to achieve our production goals for the beta and final builds.
