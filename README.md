# Space-Game
This Game was created during MSSA as a collaboration project



<img width="840" alt="SPACEGAME" src="https://github.com/cjpleasant88/Space-Game/blob/master/Assets/Space%20Game%20Logo.png">

On a mission to save Earth from a devastating fate. One man must become a cosmonaut
 Traversing through the cosmic voids of space defying the odds in order to beat the clock an obtain the rarest of substances that is UnOBTANIUM!
 In order to save humanity from the cruelest of fates you must go further than any human would dare… Do you have what it takes?

 

FEATURES: 

  * Upgrade space ship
  * Scavenge planets for resources
  * Bargain/Trade goods
  * Universal currency 
  * Fuel status report
  * Storage Capacity

  

  


# Red-Federation-Space-Game-2

---Updated Version---
Space game developed by the Red Federation team during MSSA SD7. Project completed using C# and Visual Studio. Group members: Brandon Brookins, Caleb Pleasant, Josh Gaston, and Zachary Silvis

# Requirements

*Build a Space-trading game which includes the following:*

**Base Requirements**

-   Console, text based
-   Trade between planets for profit
-   Travel between the planets:
    -   Earth
    -   Alpha Centauri B
    -   +1 (your choice)
-   Include a distance / time relation based on Star Trek TNG Warp Factor
-   Trade any goods or services you wish

**Further Requirements**

-   Compelling story - includes "good ending"
-   "Bad" end conditions: 60 yo, or assets value <= 0
-   Start conditions: 18 yo character with ship or means to acquire
-   2D grid system for planet locations
-   Per-planet goods value
-   One universal currency
-   Minimum 5 items of trade

## 2/20/2020 Updated Requirements

*Include the following requirements and discuss their implications for the current implementation of the Space Game:*

- **Multiplayer**
 - A difficulty setting had already been considered as a future possible feature
   -  If implemented, the difficulty setting could act a multiplier for a "high score" system
   -  A rudimentary "multiplayer" experience could be achieved by different users competing against each other by comparing high scores
   -  The player's base score would be derived from the number of years taken to complete story

- **Add 4 planets**
 - The existing planets in the game are instantiated objects of a single planet class, so implementation of further planets would be fairly streamlined
   - A new method would have to be created to facilitate scavenging that particular planet, *or* 
   - To better facilitate future requirement updates, a new base scavenging method could be created to be reused for any planet

- **New Planet attributes**
 - Distance from sun
   - Could determined by an random number generator at time of planet instantiation
    - This number would determine the distance from the sun, which would in turn determine other planet attributes such as climate (the further the planet is from the sun the colder it will be)
   - Inhabitants
    - A new NPC ("non-player character") class could be created to serve as a blueprint for planet inhabitants such as vendors or quest givers

- **Structure of project classes/objs/etc**
 - Refine currently implemented object structure and add new classes and methods as determined by the above updated requirements

### Other Notes/Requirements:

*After receiving feedback from playtesting, it has been determined that the in-game instructions may be too vague.*

- Update in-game instructions to better articulate the overarching objective of the game 
- Provide more specific hints and instructions to better clarify the player's immediate goal
