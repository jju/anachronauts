SRD Capital Ship Design
=======================

The Hull
--------

Capital ships range between 2,001 and 1,000,000 tons, and are designated by Hull Code.

  Tonnage   Code   Tonnage     Code
  --------- ------ ----------- ------
  3,000     CA     60,000      CN
  4,000     CB     75,000      CP
  5,000     CC     100,000     CQ
  6,000     CD     200,000     CR
  7,500     CE     300,000     CS
  10,000    CF     400,000     CT
  15,000    CG     500,000     CU
  20,000    CH     600,000     CV
  25,000    CJ     700,000     CW
  30,000    CK     800,000     CX
  40,000    CL     900,000     CY
  50,000    CM     1,000,000   CZ

The base cost of a hull is MCr. 0.1 per ton, plus a modifier based on the Hull Configuration.

### Configuration

  Configuration         Spinal Weapons   Bearing   Streamlined   Cost
  --------------------- ---------------- --------- ------------- ---------
  Needle/Wedge          Yes              80%       Yes           +20%
  Cone                  Yes              70%       Yes           +10%
  Standard (Cylinder)   Yes              80%       Partial       –
  Close Structure       Yes              70%       Partial       –10%
  Sphere                Yes              70%       Partial       –20%
  Dispersed Structure   No               60%       No            –50%
  Planetoid             Yes              50%       No            Special
  Buffered Planetoid    Yes              50%       No            Special


  Hull Code   Number of Sections   Section 1     Section 2   Section 3         Section 4         Section 5   Section 6
  ----------- -------------------- ------------- ----------- ----------------- ----------------- ----------- -----------
  CA to CE    2                    Engineering   Forward                                                      
  CF to CK    3                    Engineering   Main        Forward                                          
  CL to CQ    4                    Engineering   Amidships   Main              Forward                        
  CR to CV    5                    Engineering   Aft         Amidships         Main              Forward      
  CW to CZ    6                    Engineering   Aft         Upper Amidships   Lower Amidships   Main        Forward

Planetoid and Buffered Planetoid hulls cost Cr 4000 per ton to transport from the local planetoid belt and to drill out. Only 80% of the volume of a planetoid hull is useable and 65% of the volume of a buffered planetoid is useable.

A capital ship is divided into between two and six sections, depending on its tonnage. Attacks on a ship will hit one section or another. One section is always the Engineering section; sample names are given for different sections, but the section should be named when components are allocated to it.

### Armour

  Armour Type         TL   Protection   Cost               Max Armour
  ------------------- ---- ------------ ------------------ -----------------------------
  Titanium Steel      7    2 per 5%     5% of base hull    TL or 9, whichever is less
  Crystaliron         10   4 per 5%     20% of base hull   TL or 13, whichever is less
  Bonded Superdense   14   6 per 5%     50% of base hull   TL

Armour can be allocated on a per–section basis, in which case the cost is determined as if the two differently armoured sections of the ship were different vessels of the appropriate size. Armour does not need to be added in 5% elements, but it must be added in whole point values.

Dispersed structure ships can not be armoured.

Planetoids and Buffered Planetoids have integral armour of 2 and 4 points respectively. They may be additionally armoured as if they were a close structure vessel, but with the base hull already paid for. The maximum armour of a planetoid is 2 plus the limit from the technology or tech level of the armour. The maximum armour of a buffered planetoid is 4 plus the limit from the technology or tech level of the armour.

### Drives

To determine the tonnage of the drive required, consult the drive potential table, which gives the percentage of the ship’s total tonnage that must be allocated to the drive to give the designed Thrust or Jump.

#### Drive Potential Table

                      1     2      3     4      5     6
  ------------------- ----- ------ ----- ------ ----- ------
  Manoeuvre           1     1.25   1.5   1.75   2.5   3.25
  Jump                2     3      4     5      6     7
  Jump TL             9     11     12    13     14    15
  Manoeuvre MCr/ton   0.5   0.5    0.5   0.5    0.5   0.5
  Jump MCr /ton       2     2      2     2      2     2

For power plants, the required tonnage depends on both the tech level that the ship is built at, and the designed Power Number.

#### Power Plant Table

  Rating              1     2   3     4   5   6
  ------------------- ----- --- ----- --- --- ---
  % of displacement   1.5   2   2.5   3   4   5

Chemical power plants are 40% larger.

Fission power plants are 100% larger.

TL 8 to 10 fusion plants are 25% larger.

TL 15+ fusion plants are 25% smaller but cost twice as much.

Antimatter plants are the same size and are only available from TL 17.

Cost per ton is as follows:

Chemical power plants MCr 1.25

Fission power plants MCr 1

TL8–10 Fusion MCr 2

TL11–14 Fusion MCr 2.5

TL15 Fusion MCr 5

Antimatter plants MCr 2.5

The power plant rating must be at least equal to either the manoeuvre drive or Jump drive rating, whichever is higher, unless a chemical manoeuvre drive is fitted, in which case the rating must be 1 or the jump drive rating if this is higher. The power plant rating also determines what weapons and defensive screens of each type in each screen group the ship can carry. There is no limitation on the number of redundant screens fitted.

For example a 60,000 ton TL 15 ship with power plant rating of 5 may have up to 300 bay weapons and a spinal mount. Each of its screens groups can have up to 5 meson screens, 5 nuclear dampers or 3 black globe generators.

  P–Plant Rating   Turret Weapons       Bay Weapons        Spinal Weapons   Screens
  ---------------- -------------------- ------------------ ---------------- ---------
  1                Unlimited by power   1 per 1,000 tons   No               1
  2                Unlimited by power   2 per 1,000 tons   Yes              2
  3                Unlimited by power   3 per 1,000 tons   Yes              3
  4                Unlimited by power   4 per 1,000 tons   Yes              4
  5                Unlimited by power   5 per 1,000 tons   Yes              5
  6                Unlimited by power   6 per 1,000 tons   Yes              6

### Fuel

Manoeuvre Drive fuel is only needed if a reaction drive is fitted. The amount of fuel required is determined as the percentage of ship displacement = 2.5 per thrust hour.

**Jump Drive fuel** depends on the size of the ship and the length of the Jump, and is calculated as 0.1 x tonnage x Jump Number, and allows one Jump of the stated level.

**Power plant fuel** depends on the tonnage of the plant. For fusion plants an amount of fuel equal to two thirds of the tonnage of the power plant will power the starship for two weeks.

### Hyperspace Drive

Hyperdrives can be used in non-standard Traveller settings.

A hyperspace drive uses no fuel but requires double the space of a jump drive that can travel the equivalent distance.

### Hull & Structure

Like other starships, capital ships have one Hull Point and one Structure Point per 50 tons of displacement. However, as capital ships are so vast, these Hull and Structure points are divided into several groups, each group representing one section of the ship. If any section of the ship is reduced to zero Structure, the ship is destroyed.

Tons | Sections | TotalHull | TotalStructure | SectionHull | SectionStructure |
----:|:--------:|----------:|---------------:|------------:|-----------------:|
3,000 | 2 | 60 | 60 | 30 | 30 |
4,000 | 2 | 80 | 80 | 40 | 40 |
5,000 | 2 | 100 | 100 | 50 | 50 |
6,000 | 2 | 120 | 120 | 60 | 60 |
7,500 | 2 | 150 | 150 | 75 | 75 |
10,000 | 3 | 200 | 200 | 66 | 66 |
15,000 | 3 | 300 | 300 | 100 | 100 |
20,000 | 3 | 400 | 400 | 133 | 133 |
25,000 | 3 | 500 | 500 | 166 | 166 |
30,000 | 3 | 600 | 600 | 200 | 200 |
40,000 | 4 | 800 | 800 | 200 | 200 |
50,000 | 4 | 1,000 | 1,000 | 250 | 250 |
60,000 | 4 | 1,200 | 1,200 | 300 | 300 |
75,000 | 4 | 1,500 | 1,500 | 375 | 375 |
100,000 | 4 | 2,000 | 2,000 | 500 | 500 |
200,000 | 5 | 4,000 | 4,000 | 800 | 800 |
300,000 | 5 | 6,000 | 6,000 | 1,200 | 1,200 |
400,000 | 5 | 8,000 | 8,000 | 1,600 | 1,600 |
500,000 | 5 | 10,000 | 10,000 | 2,000 | 2,000 |
600,000 | 5 | 12,000 | 12,000 | 2,400 | 2,400 |
700,000 | 6 | 14,000 | 14,000 | 2,333 | 2,333 |
800,000 | 6 | 16,000 | 16,000 | 2,666 | 2,666 |
900,000 | 6 | 18,000 | 18,000 | 3,000 | 3,000 |
1,000,000 | 6 | 20,000 | 20,000 | 3,333 | 3,333 |

The Main Compartment
--------------------

### Component Options

### Command

A ship requires one command module per section. Each command module takes up 0.5% of the ship’s total tonnage and costs MCr.1 per ton of command module/bridge. One of these command modules must be designated the ship’s bridge, but they can all use any specialist bridge options.

### Computer

  Ship Size Minimum     Jump Minimum   Computer Model   TL   Rating   Cost
  --------------------- -------------- ---------------- ---- -------- ---------
  3,000–5,000 tons      2              Core/3           9    40       12 Mcr
  5,001–10,000 tons     2              Core/4           10   50       20 Mcr
  10,001–50,000 tons    3              Core/5           11   60       30 Mcr
  50,001–100,000 tons   4              Core/6           12   70       50 Mcr
  100,001+ tons         5              Core/7           13   80       70 Mcr
  100,001+ tons         6              Core/8           14   90       100Mcr
  100,001+ tons         6              Core/9           15   100      130 Mcr

The rating for the ship’s computer system is in addition to the processing power and speed needed for Jump Control programs, and all jump control software is included in the price of the computer system. Other ship software must be added to this.

### Sensors

Capital ships use standard sensors. However, due to the size of these vessels, it is possible to mount multiple extended or distributed arrays with up to one per section fitted.

Armaments
---------

### Turrets and Barbettes

A capital ship can mount one turret per 100 tons not allocated to other weapons. The standard set of turrets (single, double, triple, pop–up and so on) is available to capital ships. One ton of fire control equipment is required for each turret.

### Bays

The number of bays that a capital ship can mount is limited by the ship’s power plant (see above), and by the number of hardpoints. The total number of turrets and bays cannot exceed the ship’s tonnage divided by one hundred. One ton of fire control equipment is required for each bay.

### Point Defence

While a capital ship can mount point defence systems like sandcasters, the effectiveness of these systems is measured by the total point defence, not by individual systems.

### Screens

Unlike point defence weapons, which are the same for capital ships as they are for smaller craft, defensive screens scale with the size of the ship. A capital ship will need a larger screen generator to protect itself. Only one screen generator needs to be installed per ship, but extra generators can be installed as backups or to provide a stronger screen. There is a limit on the number of screens that may be combined together depending on the Tech Level of the screens. The limits are:

  TL   Nuclear Damper   Meson Screen   Black Globe
  ---- ---------------- -------------- -------------
  12   1                1              –
  13   2                2              –
  14   4                4              –
  15   6                6              3



Hull Code | Nuclear Damper Tons | Nuclear Damper MCr | Meson Screen Tons | Meson Screen MCr | Force Field Tons | Force Field MCr
:--------|---:|---:|---:|---:|---:|----:|
CA to CE | 20 | 30 | 50 | 70 | 10 | 100 |
CF to CK | 30 | 40 | 60 | 80 | 15 | 150 |
CL to CQ | 40 | 50 | 70 | 90 | 20 | 200 |
CR to CV | 50 | 60 | 80 | 100 | 25 | 250 |
CW to CZ | 60 | 70 | 90 | 110 | 30 | 300 |

Spinal Weapons
--------------

The damage of a spinal weapon depends on the size and type of weapon. Spinal weapon damage is measured in capital ship damage terms. For damage to spacecraft, the damage is the barrage value in d6. Spinal mounts use a number of hardpoints equivalent to their tonnage divided by 100. All weapons have long range. A ship may only have one spinal mount.

Increasing Tech Level will reduce size and cost significantly with some improvement in performance.

  Particle        TL+1   TL+2   TL+3   TL+4
  --------------- ------ ------ ------ ------
  Size and Cost   –10%   –20%   –30%   –40%
  Damage          +5%    +10%   +15%   +20%

\

  Meson           TL+1   TL+2   TL+3   TL+4
  --------------- ------ ------ ------ ------
  Size and Cost   –20%   –40%   –60%   –80%
  Damage          +10%   +20%   +30%   +40%

Meson Gun Spinal Mount Penetration is graded on the amount of damage they inflict in accordance with the following table:

  Damage    Penetration
  --------- -------------
  200-259   I
  260-309   II
  310-359   III
  360-459   IV
  460+      V

### Options

Rapid Fire
: A rapid fire spinal weapon is equipped with capacitors and redundant reaction chambers. It can be fired twice in a round instead of once, but only if it does not fire at all in the following round while the capacitors recharge. Making a rapid fire spinal weapon increases the tonnage and the cost of the weapon by 10%.

#### Spinal Weapons

Particle Type | Base TL | Tons | Damage | Cost | Meson Type | Base TL | Tons | Damage | Cost |
A | 8 | 5000 | 200 | 3500 | A | 11 | 5000 | 200 | 5000 | 
B | 12 | 3000 | 300 | 2100 | B | 11 | 8000 | 250 | 8000 |
C | 10 | 5000 | 300 | 3500 | C | 12 | 10000 | 350 | 10000 |
D | 14 | 3500 | 400 | 2500 | D | 13 | 14000 | 450 | 14000 |
E | 12 | 4000 | 400 | 2800

Components
----------

### Barracks

A barracks takes up 2 tons per marine, and costs MCr 0.1 per marine. Barracks can only be used to accommodate troops intended for boarding or assault operations. Troops accommodated in barracks can not be used to reduce the number of service crew embarked.

### Hangar

Storage Hangars
: have just enough space to hold the craft. To launch or recover the craft takes ten six–minute rounds, as the craft must be unpacked and prepared for flight. A storage hangar takes up tonnage equal to tonnage of the stored craft plus 10% and costs MCr 0.2 per ton.

Standard Hangars
: are large enough to hold the craft in readiness for a quick launch, perform reloading and all necessary maintenance. It includes all the necessary spare pairs, tools and heavy machinery to conduct full maintenance and repairs. A standard hangar takes up tonnage equal to the tonnage of the small craft to be stored, plus 30% and costs MCr0.2 per ton.

### Launch Tubes

Launch tubes allow for small craft to be launched and recovered rapidly from the capital ship. The size of a launch tube is twenty–five times the tonnage of the largest craft that will be deployed in this manner, and they cost MCr. 0.5/ton. With a launch tube, up to ten small craft can be launched per starship combat round. Multiple launch tubes can be installed.

Crew
----

All starships require a crew to operate and maintain the ship. In general, the crew of the ship must provide enough personnel to operate all machinery and man all weaponry. The actual number of crew personnel required for the ship must be computed based on the drives, weaponry, and other equipment carried by the ship. It is strongly recommended that you calculate the required crew for the vessel as each element of the ship is designed.

### Command Section

The ship should have a commanding officer, an executive officer, a computer officer, two navigation officers, a medical officer, and a communications officer. The section should also have support personnel, ratings equal to 50% of the total officers in the section. On large ships (over 20,000 tons), the number of personnel in the command section should amount to 5 per 10,000 tons of ship.

### Engineering Section

The ship needs one engineering crew member for each 100 tons of drives installed. This should include a knowledgeable chief engineer, a second engineer, and several petty officers.

### Gunnery Section

The ship should have a chief gunnery officer and at least 1 petty officer for each type of weapon aboard. The major weapon (spinal mount) should have a crew of 1 per 100 tons of weapon; bay weapons should have a crew of at least 2; turret weapons should have a crew of at least 1 per barrage. (Note this places a maximum limit on the number of barrages a ship can shoot, which could limit its performance against small craft. Each operational fighter or turret drone requires at least 1 crew member.

Each screen device (force field, damper, meson screen) should have a crew of at least 4. The gunnery section should have 10% officers, and 30% petty officers. Personnel are drawn from the gunnery branch and the technical services branch.

### Flight Section

If the ship has any launched craft, it should have a flight control officer, crew for each craft, and at least 1 maintenance person per craft. Launch tubes should have a crew of at least 10, which will include a flight supervision officer and a preponderance of petty officers. Pilots must be officers, and maintenance personnel are generally ratings.

In addition, if the ship has more than 3 vehicles (air/rafts, ATVs, and so on), the flight section should include vehicle drivers and maintenance personnel for them as well (at least 1 per 3 vehicles).

### Ship's Troops

Most ships over 1,000 tons have a marine (or military) contingent aboard which ranges in size from a squad to a regiment. Such contingents range from 3 per 100 tons to 3 per 1,000 tons. Ship's troops often fill the role of security forces aboard the ship, and are used for military adventures by the commander where necessary. Ship's troops are also used for damage control parties, manning of some weapons, and boarding actions.

### Service Crew

The ship itself may have a requirement for other sections which provide basic services, including shops and storage, security (especially if there are no ship's troops aboard), maintenance, food service, and other operations. Such personnel are drawn from the crew branch if no other appears appropriate. Allow 3 per 1000 tons if there are no ship's troops. This can be reduced to as low as 2 crew per 1000 tons of ship by replacing service crew with ship’s troops.

### The Frozen Watch

A ship may have low berths installed (and competent medical personnel assigned). If low berths provide enough places for a 50% coverage in personnel (including ship's troops, if any), then the ship has a frozen watch. Replacement personnel are kept available in low berths for continuous replacement of casualties and battle losses; between battles, the frozen watch can be revived and used to restore lost crew.

  --------------------------------------------------------------------
  Section         Base Crew                              Requires
  --------------- -------------------------------------- -------------
  Command         10 or 5/10,000 tons of ship            Stateroom

  Engineering     1/100 tons of drive                    ½ Stateroom

  Gunnery         1/100 tons of spinal weapon\           ½ Stateroom
                   2/bay weapon\                         
                   1/turret\                             
                   4/screen                              

  Flight          Crew of craft, +1 mechanic per craft   ½ Stateroom

  Ship’s Troops   Varies                                 ½ Stateroom

  Service         2/3 per 1000 tons                      ½ Stateroom

  Frozen Watch    Varies                                 Low Berth
  --------------------------------------------------------------------

Quarters
: Staterooms or quarters must be provided for the entire crew. The captain of the ship must be provided with an individual stateroom, as must the commanding officers of each section and the commander of the ship's troops. All other personnel on military vessels must be provided with the equivalent of half a stateroom each.
: Passengers should be provided with single staterooms. Low passengers should be provided with individual low berths.
: Staterooms require 4 tons at a cost of MCr 0.5 per stateroom. Staterooms actually average about 2 tons, but the additional tonnage is used to provide corridors and access ways, as well as galley and recreation areas. Low berths require 0.5 ton per berth, at a cost of MCr 0.05 each.

Section Hit Tables
------------------

Once all components have been selected for the ship, the ship’s details must be recorded and its Section Hit Tables must be laid out.

2d6 | Engineering External | Engineering Internal | Forward External | Forward Internal | Other External | Other Internal |
:--:|:--------------------:|:--------------------:|:----------------:|:----------------:|:--------------:|:--------------:|
2 | Hull | Crew | Hull | Crew | Hull | Crew |
3 | C | J–Drive | C | C | C | C |
4 | M–Drive | P–Plant | B | B | B | B |
5 | A | A | A | A | A | A |
6 | Hull | Structure | Hull | Structure | Hull | Structure |
7 | Armour | Hold | Armour | Hold | Armour | Hold |
8 | Hull | Structure | Hull | Structure | Hull | Structure |
9 | A | A | A | A | A | A |
10 | M–Drive | J–Drive | B | B | B | B |
11 | C | P–Plant | C | C | C | C |
12 | Hull | Critical | Hull | Critical | Hull | Critical |

All slots must be filled on all tables. The entries marked Type A, Type B or Type C can contain any of several components - see the Component Type table.

If there are excess Type A components, then the excess can be placed in unoccupied Type B slots.

If there aren’t enough Type B slots, use unoccupied Type C slots.

Sometimes, not all of a ship’s components can be placed on the Section Hit Tables; if so, place the largest tonnage components first.

If there are still unfilled slots when all components have been placed, then unfilled internal slots are filled with Structure and unfilled external slots are filled with Hull.

| A-External | A-Internal | B-External | B-Internal | C-External | C-Internal |
|:-----------|:-----------|:-----------|:-----------|:-----------|:-----------|
| Turret[^1] | Bay[^1] | Sensors | Spinal Weapon[^4] | Spec Components[^5] | Screen |
| Barbette[^1] | Fuel | Craft[^2] | Hangar[^2] | | Spec Components[^5] |
|            | Hold | Launch Tubes | Power Plant[^3] | | Command |
|            | | M-Drive[^3] | AE Drive[^3] | | |
|            | | Spinal Weapon[^4] | Computer | | |

[^1]: If the ship mounts multiple types of this weapon (such as laser turrets and particle turrets), they should be counted separately.

[^2]: If the ship mounts multiple types of this component (such as fighters and shuttles), they should be counted separately.

[^3]: The engineering section normally contains all the ship’s drives, but if any drive exceeds 10% of the ship’s tonnage, it should be placed in one extra section per extra 10%.

[^4]: If a ship has a spinal weapon, then it must be placed in the Internal Section Hit tables for every section apart from Engineering.

[^5]: If a component such as laboratories or docking clamps exceeds 1% of the ship’s tonnage, it should be placed on the Section Hit table.

All weapons, sensors, small craft, launch tubes, hangars, computers, screens, command sections and any other component that has a role in ship to ship combat must be put in at least one slot.

Capital Ship Crews
------------------

Crew Strength
: The size of the crew relative to the ship is measured on the Crew Strength scale. An understrength crew may still be able to operate the ship, but with penalties to skill rolls or more slowly. An overstrength crew gives no bonuses, but is able to absorb more casualties and has a bonus during boarding actions.

  Crew Strength            % of full crew   Skill DM    
  ------------------------ ---------------- ---------- ---------------------------------------
  Dead                     0%               –          Cannot act
  Survivors                1% to 10%        –4         May only fire once every five rounds
  Skeleton                 11% to 25%       –2         May only fire once every three rounds
  Half                     65% to 50%       –1         May only fire once every two rounds
  Weakened                 51% to 75%       +0          
  Full                     76% to 90%       +0          
  Battle                   91% to 120%      +0          
  Overstrength             121% to 150%     +0          
  Massively Overstrength   151%+            +0          

If a ship is noted as being able to fire once every two or more rounds, then this applies to each individual weapon. For example, a ship armed with a pulse laser bank, a particle beam bank, and a spinal meson gun could fire a half–strength barrage from its pulse lasers together with a meson gun blast. Next round, it could fire another half strength pulse laser barrage and the particle beams, but could not fire the other half of the pulse lasers or the meson gun again.

Crew Skill
: A starship crew is assumed to have average to good Characteristics and to have mastered the following skills: Pilot, Gunner, Discipline, Mechanic, Engineer, Sensors and Medic. All these skills are at the level of their Crew Skill characteristic. Obviously, some individual crewmen will have greater or lesser skills, but the average is the Crew Skill and is used for all skill checks made by the crew.

  Crew Skill    Skill Check DM
  ------------- ----------------
  Green         +0
  Average       +1
  Experienced   +2
  Elite         +3
  Legendary     +4

: A crew may have an especially skilled officer. If the officer has a skill level of 4 or more, he gives a +1 DM to all matching skill checks. An officer may only give a bonus to one skill roll each round, and a skill may only benefit from one officer bonus.

Endurance
---------

Ships are able to operate for one month without needing to go into a spaceport for maintenance, assuming an adequate supply of fuel. This is increased by one month for every 1% of total tonnage dedicated to cargo. If fleet support vessels are in attendance then another three months can be added to the time needed before maintenance is required.
