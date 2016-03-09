RTT Worldgen
============

From RPGnetWiki

The RTT Complicated Star System Generator is a detailed, but not *too* detailed, random star system and world generation system for Mongoose Traveller. It attempts to walk that fine line between realistic (as based on current astronomical and planetological research) and easy to use. Drawn from a number of sources, including the core rules, *GURPS Space* (for 4th edition), *GURPS Traveller: First In*, various idea seeds on the [Traveller Mailing List](http://traveller.wikia.com/wiki/Traveller_Mailing_List) and [Citizens of the Imperium fora](http://www.travellerrpg.com/CotI/Discuss/), and the [Arc Builder Planetary Classification List](http://arcbuilder.home.bresnan.net/PCLMaster.html).

This is a "bottom up" system, where you start with the primary star and work through all the planetary orbits. However, a lot of the process has been greatly simplified and fudged, mainly so you don't have to go crazy calculating the molecular weight of the atmosphere and the effects of axial tilt, but also to make it easier to update the system when new scientific discoveries make it outdated. The end results are all in the conventional UPP format, with the addition of a single new rating, **Biosphere**, to describe the complexity of life on the world.

I've made the assumption that minor bodies aren't worth mentioning. Assume all systems have a Kuiper belt and Oort cloud, that most Jovians will have their Trojans and Greeks, and that pretty much any planet at all has a number of minor satellites, meteor clouds, etc. Space is big.

– Shadowjack

Contents
--------

-   [<span class="tocnumber">1</span> <span class="toctext">To Do
    List</span>](#To_Do_List)
-   [<span class="tocnumber">2</span> <span class="toctext">Basic Star
    Placement</span>](#Basic_Star_Placement)
-   [<span class="tocnumber">3</span> <span class="toctext">Star System
    Generation</span>](#Star_System_Generation)
    -   [<span class="tocnumber">3.1</span> <span class="toctext">Number
        of Stars</span>](#Number_of_Stars)
    -   [<span class="tocnumber">3.2</span> <span
        class="toctext">Spectral Types</span>](#Spectral_Types)
    -   [<span class="tocnumber">3.3</span> <span class="toctext">System
        Age & Luminosity
        Classes</span>](#System_Age_.26_Luminosity_Classes)
    -   [<span class="tocnumber">3.4</span> <span
        class="toctext">Companion Orbits</span>](#Companion_Orbits)
-   [<span class="tocnumber">4</span> <span class="toctext">Planetary
    System Generation</span>](#Planetary_System_Generation)
    -   [<span class="tocnumber">4.1</span> <span class="toctext">Orbit
        Contents</span>](#Orbit_Contents)
    -   [<span class="tocnumber">4.2</span> <span class="toctext">World
        Types</span>](#World_Types)
        -   [<span class="tocnumber">4.2.1</span> <span
            class="toctext">Dwarf Planets</span>](#Dwarf_Planets)
            -   [<span class="tocnumber">4.2.1.1</span> <span
                class="toctext">Epistellar</span>](#Epistellar)
            -   [<span class="tocnumber">4.2.1.2</span> <span
                class="toctext">Inner Zone</span>](#Inner_Zone)
            -   [<span class="tocnumber">4.2.1.3</span> <span
                class="toctext">Outer Zone</span>](#Outer_Zone)
        -   [<span class="tocnumber">4.2.2</span> <span
            class="toctext">Terrestrial
            Planets</span>](#Terrestrial_Planets)
            -   [<span class="tocnumber">4.2.2.1</span> <span
                class="toctext">Epistellar</span>](#Epistellar_2)
            -   [<span class="tocnumber">4.2.2.2</span> <span
                class="toctext">Inner Zone</span>](#Inner_Zone_2)
            -   [<span class="tocnumber">4.2.2.3</span> <span
                class="toctext">Outer Zone</span>](#Outer_Zone_2)
        -   [<span class="tocnumber">4.2.3</span> <span
            class="toctext">Helian Planets</span>](#Helian_Planets)
            -   [<span class="tocnumber">4.2.3.1</span> <span
                class="toctext">Epistellar</span>](#Epistellar_3)
            -   [<span class="tocnumber">4.2.3.2</span> <span
                class="toctext">Inner Zone</span>](#Inner_Zone_3)
            -   [<span class="tocnumber">4.2.3.3</span> <span
                class="toctext">Outer Zone</span>](#Outer_Zone_3)
        -   [<span class="tocnumber">4.2.4</span> <span
            class="toctext">Jovian Planets</span>](#Jovian_Planets)
            -   [<span class="tocnumber">4.2.4.1</span> <span
                class="toctext">Epistellar</span>](#Epistellar_4)
            -   [<span class="tocnumber">4.2.4.2</span> <span
                class="toctext">Inner Zone</span>](#Inner_Zone_4)
            -   [<span class="tocnumber">4.2.4.3</span> <span
                class="toctext">Outer Zone</span>](#Outer_Zone_4)
-   [<span class="tocnumber">5</span> <span class="toctext">World
    Generation</span>](#World_Generation)
    -   [<span class="tocnumber">5.1</span> <span class="toctext">World
        Generation Tables</span>](#World_Generation_Tables)
        -   [<span class="tocnumber">5.1.1</span> <span
            class="toctext">Acheronian</span>](#Acheronian)
        -   [<span class="tocnumber">5.1.2</span> <span
            class="toctext">Arean</span>](#Arean)
        -   [<span class="tocnumber">5.1.3</span> <span
            class="toctext">Arid</span>](#Arid)
        -   [<span class="tocnumber">5.1.4</span> <span
            class="toctext">Asphodelian</span>](#Asphodelian)
        -   [<span class="tocnumber">5.1.5</span> <span
            class="toctext">Chthonian</span>](#Chthonian)
        -   [<span class="tocnumber">5.1.6</span> <span
            class="toctext">Hebean</span>](#Hebean)
        -   [<span class="tocnumber">5.1.7</span> <span
            class="toctext">Helian</span>](#Helian)
        -   [<span class="tocnumber">5.1.8</span> <span
            class="toctext">JaniLithic</span>](#JaniLithic)
        -   [<span class="tocnumber">5.1.9</span> <span
            class="toctext">Jovian</span>](#Jovian)
        -   [<span class="tocnumber">5.1.10</span> <span
            class="toctext">Meltball</span>](#Meltball)
        -   [<span class="tocnumber">5.1.11</span> <span
            class="toctext">Oceanic</span>](#Oceanic)
        -   [<span class="tocnumber">5.1.12</span> <span
            class="toctext">Panthalassic</span>](#Panthalassic)
        -   [<span class="tocnumber">5.1.13</span> <span
            class="toctext">Promethean</span>](#Promethean)
        -   [<span class="tocnumber">5.1.14</span> <span
            class="toctext">Rockball</span>](#Rockball)
        -   [<span class="tocnumber">5.1.15</span> <span
            class="toctext">Small Body</span>](#Small_Body)
        -   [<span class="tocnumber">5.1.16</span> <span
            class="toctext">Snowball</span>](#Snowball)
        -   [<span class="tocnumber">5.1.17</span> <span
            class="toctext">Stygian</span>](#Stygian)
        -   [<span class="tocnumber">5.1.18</span> <span
            class="toctext">Tectonic</span>](#Tectonic)
        -   [<span class="tocnumber">5.1.19</span> <span
            class="toctext">Telluric</span>](#Telluric)
        -   [<span class="tocnumber">5.1.20</span> <span
            class="toctext">Vesperian</span>](#Vesperian)
    -   [<span class="tocnumber">5.2</span> <span
        class="toctext">Revised Planetary Profile
        Codes</span>](#Revised_Planetary_Profile_Codes)
        -   [<span class="tocnumber">5.2.1</span> <span
            class="toctext">Size</span>](#Size)
        -   [<span class="tocnumber">5.2.2</span> <span
            class="toctext">Atmosphere</span>](#Atmosphere)
        -   [<span class="tocnumber">5.2.3</span> <span
            class="toctext">Hydrosphere</span>](#Hydrosphere)
        -   [<span class="tocnumber">5.2.4</span> <span
            class="toctext">Biosphere</span>](#Biosphere)
        -   [<span class="tocnumber">5.2.5</span> <span
            class="toctext">Population</span>](#Population)
        -   [<span class="tocnumber">5.2.6</span> <span
            class="toctext">Government</span>](#Government)
        -   [<span class="tocnumber">5.2.7</span> <span
            class="toctext">Law Level</span>](#Law_Level)
        -   [<span class="tocnumber">5.2.8</span> <span
            class="toctext">Industry Level</span>](#Industry_Level)
    -   [<span class="tocnumber">5.3</span> <span
        class="toctext">Populations</span>](#Populations)
        -   [<span class="tocnumber">5.3.1</span> <span
            class="toctext">World
            Desirability</span>](#World_Desirability)
            -   [<span class="tocnumber">5.3.1.1</span> <span
                class="toctext">Asteroid Belts</span>](#Asteroid_Belts)
            -   [<span class="tocnumber">5.3.1.2</span> <span
                class="toctext">Dwarfs, Terrestrials, Helians, and
                Jovians</span>](#Dwarfs.2C_Terrestrials.2C_Helians.2C_and_Jovians)
                -   [<span class="tocnumber">5.3.1.2.1</span> <span
                    class="toctext">Terraforming</span>](#Terraforming)
        -   [<span class="tocnumber">5.3.2</span> <span
            class="toctext">Habitation</span>](#Habitation)
            -   [<span class="tocnumber">5.3.2.1</span> <span
                class="toctext">Homeworld</span>](#Homeworld)
            -   [<span class="tocnumber">5.3.2.2</span> <span
                class="toctext">Colony</span>](#Colony)
            -   [<span class="tocnumber">5.3.2.3</span> <span
                class="toctext">Outpost</span>](#Outpost)
            -   [<span class="tocnumber">5.3.2.4</span> <span
                class="toctext">Uninhabited</span>](#Uninhabited)
        -   [<span class="tocnumber">5.3.3</span> <span
            class="toctext">Other Population
            Stats</span>](#Other_Population_Stats)
        -   [<span class="tocnumber">5.3.4</span> <span
            class="toctext">The Effects of Local
            Industry</span>](#The_Effects_of_Local_Industry)
            -   [<span class="tocnumber">5.3.4.1</span> <span
                class="toctext">Hard Times</span>](#Hard_Times)
        -   [<span class="tocnumber">5.3.5</span> <span
            class="toctext">Interstellar
            Trade</span>](#Interstellar_Trade)
            -   [<span class="tocnumber">5.3.5.1</span> <span
                class="toctext">Trade Codes</span>](#Trade_Codes)
            -   [<span class="tocnumber">5.3.5.2</span> <span
                class="toctext">Starport</span>](#Starport)
            -   [<span class="tocnumber">5.3.5.3</span> <span
                class="toctext">Bases</span>](#Bases)
                -   [<span class="tocnumber">5.3.5.3.1</span> <span
                    class="toctext">Base Codes</span>](#Base_Codes)

</div>


Special Features, internal links for dice tables, descriptive links for planetary and stellar classes, nomenclature/layout sheet

A: B-cdef-ghjk-Lm N N N P

A — Orbit
B — World Type
C — Size
D — Atmosphere
E — Hydrosphere
F — Biosphere
G — Population
H — Government Type
J — Law Level
K — Industrial Base
L — Starport
m — Bases
N — World & Trade Codes
P — Travel Code
\
Playtesting Notes:

12 Dec 2008: Minor tweaks.

19 June 2008: Improved population rules. Needs testing.

9 June 2008: Still working on the population rules. A high stellar society like the Imperium turns out a *lot* of small outposts, which is mildly surprising, but does seem reasonable. Need a more elegant approach to terraforming; maybe this will work…

Gov. and Law codes seem to work, but definitely need to tweak the Industrial Base generation. Some tweaking to the base rules.

6 June 2008: The tables seem to turn out rather small planetary systems, especially for the ubiquitous red dwarfs, but I'm not sure that's a bug; if anything, it makes it easier to cope. And considering that we still don't know how common planets *really* are in the universe; under these rules, the Sol system is neither rare nor typical, which works for me. If you want more planets, try applying DM +1 to the three orbit rolls. Microscopic life is fairly common and macroscopic life less so, which seems a reasonable assumption for Traveller, and there look to be plenty of quiet lifeless worlds suitable for terraforming.

Basic Star Placement
====================

Any hex has a 50% chance of having a brown dwarf (class L) somewhere.

Any hex has a 50% chance of having a star system somewhere.

A hex can contain both, drifting far apart from each other. For either kind of system, follow the procedure below.

<span id="Star_System_Generation" class="mw-headline">Star System Generation</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=3 "Edit section: Star System Generation")<span class="mw-editsection-bracket">\]</span></span>
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### <span id="Number_of_Stars" class="mw-headline">Number of Stars</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=4 "Edit section: Number of Stars")<span class="mw-editsection-bracket">\]</span></span>

Roll 3d6. **DMs:** Open Cluster +3. Don't roll for a lone brown dwarf;
it's always solitary.

3-10 — Solitary star
11-15 — Binary system
16+ — Trinary system
### <span id="Spectral_Types" class="mw-headline">Spectral Types</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=5 "Edit section: Spectral Types")<span class="mw-editsection-bracket">\]</span></span>

For the Primary, roll 2d6.

For each Companion, roll and add 1d6-1 to the Primary's number.

*This generates a main sequence star; if the star later turns out to be
a subgiant or giant, its spectral type will be changed. Don't roll for
lone brown dwarfs.*

2 — A-type or larger. (You may choose to place an O or B star,
supergiant, etc.; max. 1 per sector.)
3 — F-type
4 — G-type
5 — K-type
6-13 — M-type
14+ — L-type
### <span id="System_Age_.26_Luminosity_Classes" class="mw-headline">System Age & Luminosity Classes</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=6 "Edit section: System Age & Luminosity Classes")<span class="mw-editsection-bracket">\]</span></span>

System Age = 3d6-3 (in billions of years). Use this to determine the
luminosity class and final spectral type of each star.

**A-type**

If Age ≤ 2: A-V
If Age = 3, roll 1d6:
1-2 — F-IV
3 — K-III
4-6 — D
If Age ≥ 4: D
**F-type**

If Age ≤ 5: F-V
If Age = 6, roll 1d6:
1-4 — G-IV
5-6 — M-III
If Age ≥ 7: D
**G-type**

If Age ≤ 11: G-V
If Age 12-13, roll 1d6:
1-3 — K-IV
4-6 — M-III
If Age ≥ 14: D
**K-type**

Automatically K-V.
**M-type**

Roll 2d6. **DMs:** Companion star +2.
2-9 — M-V
10-12 — M-Ve (flare star)
13+ — L
**L-type**

Automatically L.
### <span id="Companion_Orbits" class="mw-headline">Companion Orbits</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=7 "Edit section: Companion Orbits")<span class="mw-editsection-bracket">\]</span></span>

For each Companion, roll 1d6:

1-2 — Tight orbit
3-4 — Close orbit
5 — Moderate orbit
6 — Distant orbit
<span id="Planetary_System_Generation" class="mw-headline">Planetary System Generation</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=8 "Edit section: Planetary System Generation")<span class="mw-editsection-bracket">\]</span></span>
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Each Primary and Distant Companion has its own planetary system,
consisting of:

**Epistellar orbits:** 1d6-3, maximum 2. **DMs:** M-V star -1.

*Type III, D, or L star:* automatically 0.
**Inner Zone orbits:** 1d6-1. **DMs:** M-V star -1. If Close Companion
present, automatically 0.

*Type L star:* instead roll 1d3-1.
**Outer Zone orbits:** 1d6-1. **DMs:** M-V or L star -1. If Moderate
Companion present, automatically 0.

### <span id="Orbit_Contents" class="mw-headline">Orbit Contents</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=9 "Edit section: Orbit Contents")<span class="mw-editsection-bracket">\]</span></span>

For each planetary orbit, roll 1d6. **DMs:** L star -1.

0-1 — Asteroid Belt
2 — Dwarf Planet
3 — Terrestrial Planet
4 — Helian Planet
5-6 — Jovian Planet
Then determine if the planets have any major satellites. (Small
satellites are not counted.)

**Asteroid Belt**

Roll 1d6.
1-4 — All members are Small Bodies.
5-6 — Most members are Small Bodies, but there is also one Dwarf Planet.
**Dwarf Planet**

Roll 1d6.
1-5 — No major satellites.
6 — One Dwarf Planet as binary companion.
**Terrestrial Planet**

Roll 1d6.
1-4 — No major satellites.
5-6 — One Dwarf Planet as satellite.
**Helian Planet**

Satellites: 1d6-3. If there are any satellites at all, roll 1d6.
1-5 — All satellites are Dwarf Planets.
6 — One of the satellites is a Terrestrial Planet, and the others are
Dwarf Planets.
**Jovian Planet**

Satellites: 1d6. Then, roll 1d6 again.
1-5 — All satellites are Dwarf Planets.
6 — Roll 1d6 again.
1-5 — One of the satellites is a Terrestrial Planet, and the others are
Dwarf Planets.
6 — One of the satellites is a Helian Planet, and the others are Dwarf
Planets.
Rings: Roll 1d6.
1-4 — Minor ring system only.
5-6 — Complex ring system.
### <span id="World_Types" class="mw-headline">World Types</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=10 "Edit section: World Types")<span class="mw-editsection-bracket">\]</span></span>

Then for each planet, look up its zone and type on the tables below to
find out which world generation type to use.

If the star is type III or D, the first 1d6 orbits (counting outward)
were directly affected by the star's expansion. Any planets in those
orbits are automatically of a particular type:

All Dwarf Planets become Stygian.
All Terrestrial Planets become Acheronian.
All Helian Planets become Asphodelian.
All Jovian Planets become Chthonian.
\

#### <span id="Dwarf_Planets" class="mw-headline">Dwarf Planets</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=11 "Edit section: Dwarf Planets")<span class="mw-editsection-bracket">\]</span></span>

##### <span id="Epistellar" class="mw-headline">Epistellar</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=12 "Edit section: Epistellar")<span class="mw-editsection-bracket">\]</span></span>

Roll 1d6. **DMs:** Asteroid Belt member -2.

1-3 — Rockball
4-5 — Meltball
6 — Roll 1d6:
1-4 — Hebean
5-6 — Promethean
##### <span id="Inner_Zone" class="mw-headline">Inner Zone</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=13 "Edit section: Inner Zone")<span class="mw-editsection-bracket">\]</span></span>

Roll 1d6. **DMs:** Asteroid Belt member -2, Helian satellite +1, Jovian
satellite +2.

1-4 — Rockball
5-6 — Arean
7 — Meltball
8 — Roll 1d6:
1-4 — Hebean
5-6 — Promethean
##### <span id="Outer_Zone" class="mw-headline">Outer Zone</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=14 "Edit section: Outer Zone")<span class="mw-editsection-bracket">\]</span></span>

Roll 1d6. **DMs:** Asteroid Belt member -1, Helian satellite +1, Jovian
satellite +2.

0 — Rockball
1-4 — Snowball
5-6 — Rockball
7 — Meltball
8 — Roll 1d6:
1-3 — Hebean
4-5 — Arean
6 — Promethean
#### <span id="Terrestrial_Planets" class="mw-headline">Terrestrial Planets</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=15 "Edit section: Terrestrial Planets")<span class="mw-editsection-bracket">\]</span></span>

##### <span id="Epistellar_2" class="mw-headline">Epistellar</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=16 "Edit section: Epistellar")<span class="mw-editsection-bracket">\]</span></span>

Roll 1d6.

1-4 — JaniLithic
5 — Vesperian
6 — Telluric
##### <span id="Inner_Zone_2" class="mw-headline">Inner Zone</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=17 "Edit section: Inner Zone")<span class="mw-editsection-bracket">\]</span></span>

Roll 2d6.

2-4 — Telluric
5-6 — Arid
7 — Tectonic
8-9 — Oceanic
10 — Tectonic
11-12 — Telluric
##### <span id="Outer_Zone_2" class="mw-headline">Outer Zone</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=18 "Edit section: Outer Zone")<span class="mw-editsection-bracket">\]</span></span>

Roll 1d6. **DMs:** Satellite +2.

1-4 — Arid
5-6 — Tectonic
7-8 — Oceanic
#### <span id="Helian_Planets" class="mw-headline">Helian Planets</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=19 "Edit section: Helian Planets")<span class="mw-editsection-bracket">\]</span></span>

##### <span id="Epistellar_3" class="mw-headline">Epistellar</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=20 "Edit section: Epistellar")<span class="mw-editsection-bracket">\]</span></span>

Roll 1d6.

1-5 — Helian
6 — Asphodelian
##### <span id="Inner_Zone_3" class="mw-headline">Inner Zone</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=21 "Edit section: Inner Zone")<span class="mw-editsection-bracket">\]</span></span>

Roll 1d6.

1-4 — Helian
5-6 — Panthalassic
##### <span id="Outer_Zone_3" class="mw-headline">Outer Zone</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=22 "Edit section: Outer Zone")<span class="mw-editsection-bracket">\]</span></span>

Automatically Helian.

#### <span id="Jovian_Planets" class="mw-headline">Jovian Planets</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=23 "Edit section: Jovian Planets")<span class="mw-editsection-bracket">\]</span></span>

##### <span id="Epistellar_4" class="mw-headline">Epistellar</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=24 "Edit section: Epistellar")<span class="mw-editsection-bracket">\]</span></span>

Roll 1d6.

1-5 — Jovian
6 — Chthonian
##### <span id="Inner_Zone_4" class="mw-headline">Inner Zone</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=25 "Edit section: Inner Zone")<span class="mw-editsection-bracket">\]</span></span>

Automatically Jovian.

##### <span id="Outer_Zone_4" class="mw-headline">Outer Zone</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=26 "Edit section: Outer Zone")<span class="mw-editsection-bracket">\]</span></span>

Automatically Jovian.

<span id="World_Generation" class="mw-headline">World Generation</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=27 "Edit section: World Generation")<span class="mw-editsection-bracket">\]</span></span>
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### <span id="World_Generation_Tables" class="mw-headline">World Generation Tables</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=28 "Edit section: World Generation Tables")<span class="mw-editsection-bracket">\]</span></span>

#### <span id="Acheronian" class="mw-headline">Acheronian</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=29 "Edit section: Acheronian")<span class="mw-editsection-bracket">\]</span></span>

*Terrestrial Group, Telluric Class, Acheronian Type.*\
These are worlds that were directly affected by their primary's
transition from the main sequence; the atmosphere and oceans have been
boiled away, leaving a scorched, dead planet.

Size: 1d6+4.
Atmosphere: 1.
Hydrosphere: 0.
Biosphere: 0.
#### <span id="Arean" class="mw-headline">Arean</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=30 "Edit section: Arean")<span class="mw-editsection-bracket">\]</span></span>

*Dwarf Group, GeoCyclic Class, Arean / Utgardian / Titanian Types.*\
These are worlds with little liquid, that move through a slow geological
cycle of a gradual build-up, a short wet and clement period, and a long
decline.

Size: 1d6-1.
Atmosphere: Roll 1d6. **DMs:** D star -2.
1-3 — 1.
4-6 — A.
Hydrosphere: 2d6+Size-7. **DMs:** Atmos 1 -4.
Biosphere:
*Chemistry:* Roll 1d6. **DMs:** L star +2; Outer Zone +2.
1-4 — Water (Age modifier +0) *\[Arean\]*
5-6 — Ammonia (Age modifier +1) *\[Utgardian\]*
7-8 — Methane (Age modifier +3) *\[Titanian\]*
If Age ≥ 1d3 + modifier, and Atmos 1: 1d6-4.
If Age ≥ 1d3 + modifier, and Atmos A: 1d3.
If Age ≥ 4 + modifier, and Atmos A: 1d6+Size-2.
Otherwise: 0.
#### <span id="Arid" class="mw-headline">Arid</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=31 "Edit section: Arid")<span class="mw-editsection-bracket">\]</span></span>

*Terrestrial Group, Arid Class, Darwinian / Saganian / Asimovian
Types.*\
These are worlds with limited amounts of surface liquid, that maintain
an equilibrium with the help of their tectonic activity and their
biosphere.

Size: 1d6+4.
Biosphere:
*Chemistry:* Roll 1d6. **DMs:** K-V star +2; M-V star +4; L star +5;
Outer Zone +2.
1-6 — Water (Age modifier +0) *\[Darwinian\]*
7-8 — Ammonia (Age modifier +1) *\[Saganian\]*
9-10 — Methane (Age modifier +3) *\[Asimovian\]*
If Age ≥ 1d3 + modifier: 1d3.
If Age ≥ 4 + modifier: 2d6. **DMs:** D star -3.
Otherwise: 0.
Atmosphere:
If Biosphere 3+ and Water Chemistry: 2d6-7+Size, minimum 2, maximum 9.
Otherwise: A.
Hydrosphere: 1d3.
#### <span id="Asphodelian" class="mw-headline">Asphodelian</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=32 "Edit section: Asphodelian")<span class="mw-editsection-bracket">\]</span></span>

*Helian Group, GeoHelian Class, Asphodelian Type.*\
These are worlds that were directly affected by their primary's
transition from the main sequence; their atmosphere has been boiled
away, leaving the surface exposed.

Size: 1d6+9.
Atmosphere: 1.
Hydrosphere: 0.
Biosphere: 0.
#### <span id="Chthonian" class="mw-headline">Chthonian</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=33 "Edit section: Chthonian")<span class="mw-editsection-bracket">\]</span></span>

*Jovian Group, Chthonian Class.*\
These are worlds that were directly affected by their primary's
transition from the main sequence, or that have simply spent too long in
a tight epistellar orbit; their atmospheres have been stripped away.

Size: G.
Atmosphere: 1.
Hydrosphere: 0.
Biosphere: 0.
#### <span id="Hebean" class="mw-headline">Hebean</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=34 "Edit section: Hebean")<span class="mw-editsection-bracket">\]</span></span>

*Dwarf Group, GeoTidal Class, Hebean / Idunnian Types.*\
These are highly active worlds, due to tidal flexing, but with some
regions of stability; the larger ones may be able to maintain some
atmosphere and surface liquid.

Size: 1d6-1.
Atmosphere: 1d6+Size-6.
If 2+: change to A.
Hydrosphere: 2d6+Size-11.
Biosphere: 0.
#### <span id="Helian" class="mw-headline">Helian</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=35 "Edit section: Helian")<span class="mw-editsection-bracket">\]</span></span>

*Helian Group, GeoHelian / Nebulous Classes.*\
These are typical helian or "subgiant" worlds – large enough to retain
helium atmospheres.

Size: 1d6+9.
Atmosphere: D.
Hydrosphere: Roll 1d6.
1-2 — 0.
3-4 — 2d6-1.
5-6 — F.
Biosphere: 0.
#### <span id="JaniLithic" class="mw-headline">JaniLithic</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=36 "Edit section: JaniLithic")<span class="mw-editsection-bracket">\]</span></span>

*Terrestrial Group, Epistellar Class, JaniLithic Type.*\
These worlds, tide-locked to the primary, are rocky, dry, and
geologically active.

Size: 1d6+4.
Atmosphere: Roll 1d6.
1-3 — 1
4-6 — A
Hydrosphere: 0.
Biosphere: 0.
#### <span id="Jovian" class="mw-headline">Jovian</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=37 "Edit section: Jovian")<span class="mw-editsection-bracket">\]</span></span>

*Jovian Group. If life-bearing, is most likely DwarfJovian Class,
Brammain / Khonsonian Types.*\
These are huge worlds with helium-hydrogen envelopes and compressed
cores; the largest emit more heat than they absorb.

Size: G.
Atmosphere: G.
Hydrosphere: G.
Biosphere: Roll 1d6. **DMs:** Inner Zone +2.
1-5 — 0
6 — Life is possible.
If Age ≥ 1d6: 1d3.
If Age ≥ 7: 2d6. **DMs:** D star -3.
Otherwise: 0.
*Chemistry:* If life, roll 1d6. **DMs:** L star +1; Epistellar -2; Outer
Zone +2.
1-3 — Water *\[Brammian\]*
4-6 — Ammonia *\[Khonsonian\]*
#### <span id="Meltball" class="mw-headline">Meltball</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=38 "Edit section: Meltball")<span class="mw-editsection-bracket">\]</span></span>

*Dwarf Group, GeoThermic Class, Phaethonic / Apollonian / Sethian Types,
or GeoTidal Class, Hephaestian / Lokian Types.*\
These are dwarfs with molten or semi-molten surfaces, either from
extreme tidal flexing, or extreme approach to a star.

Size: 1d6-1.
Atmosphere: 1.
Hydrosphere: F.
Biosphere: 0.
#### <span id="Oceanic" class="mw-headline">Oceanic</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=39 "Edit section: Oceanic")<span class="mw-editsection-bracket">\]</span></span>

*Terrestrial Group, Oceanic Class, Pelagic / Nunnic / Teathic Types, or
Tectonic Class, BathyGaian / BathyAmunian / BathyTartarian Types.*\
These are worlds with a continuous hydrological cycle and deep oceans,
due to either dense greenhouse atmosphere or active plate tectonics.

Size: 1d6+4.
Biosphere:
*Chemistry:* Roll 1d6. **DMs:** K-V star +2; M-V star +4; L star +5;
Outer Zone +2.
1-6 — Water (Age modifier +0) *\[Pelagic / BathyGaian\]*
7-8 — Ammonia (Age modifier +1) *\[Nunnic / BathyAmunian\]*
9-10 — Methane (Age modifier +3) *\[Teathic / BathyTartarian\]*
If Age ≥ 1d3 + modifier: 1d3.
If Age ≥ 4 + modifier: 2d6. **DMs:** D star -3.
Otherwise: 0.
Atmosphere:
If Water Chemistry: 2d6+Size-6, minimum 1, maximum C. **DMs:** K-V star
-1; M-V star -2; L star -3; any IV star -1.
Otherwise: Roll 1d6.
1 — 1
2-4 — A
5-6 — C
Hydrosphere: B.
#### <span id="Panthalassic" class="mw-headline">Panthalassic</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=40 "Edit section: Panthalassic")<span class="mw-editsection-bracket">\]</span></span>

*Helian Group, Panthalassic Class.*\
These are massive worlds, aborted gas giants, largely composed of water
and hydrogen.

Size: 1d6+9.
Atmosphere: 1d6+8, maximum D.
Hydrosphere: B.
Biosphere:
*Chemistry:* Roll 1d6. **DMs:** K-V star +2; M-V star +4; L star +5.
1-6 — Roll 2d6.
2-8 — Water (Age modifier +0)
9-11 — Sulfur (Age modifier +0)
12 — Chlorine (Age modifier +0)
7-8 — Methane (Age modifier +1)
9-10 — Methane (Age modifier +3)
If Age ≥ 1d3 + modifier: 1d3.
If Age ≥ 4 + modifier: 2d6.
Otherwise: 0.
#### <span id="Promethean" class="mw-headline">Promethean</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=41 "Edit section: Promethean")<span class="mw-editsection-bracket">\]</span></span>

*Dwarf Group, GeoTidal Class, Promethean / Burian / Atlan Types.*\
These are worlds that, through tidal-flexing, have a geological cycle
similar to plate tectonics, that supports surface liquid and atmosphere.

Size: 1d6-1.
Biosphere:
*Chemistry:* Roll 1d6. **DMs:** L star +2; Epistellar -2; Outer Zone +2.
1-4 — Water (Age modifier +0) *\[Promethean\]*
5-6 — Ammonia (Age modifier +1) *\[Burian\]*
7-8 — Methane (Age modifier +3)*\[Atlan\]*
If Age ≥ 1d3 + modifier: 1d3.
If Age ≥ 4 + modifier: 2d6. **DMs:** D star -3.
Otherwise: 0.
Atmosphere:
If Biosphere 3+ and Water Chemistry: 2d6+Size-7, minimum 2, maximum 9.
Otherwise: A.
Hydrosphere: 2d6-2.
#### <span id="Rockball" class="mw-headline">Rockball</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=42 "Edit section: Rockball")<span class="mw-editsection-bracket">\]</span></span>

*Dwarf Group, GeoPassive Class, Ferrinian / Lithic / Carbonian Types.*\
These are mostly dormant worlds, with surfaces largely unchanged since
the early period of planetary formation.

Size: 1d6-1.
Atmosphere: 0.
Hydrosphere: 2d6+Size-11. **DMs:** L star +1; Epistellar -2, Outer Zone
+2.
Biosphere: 0.
#### <span id="Small_Body" class="mw-headline">Small Body</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=43 "Edit section: Small Body")<span class="mw-editsection-bracket">\]</span></span>

*Small Body Group.*\
These are bodies too small to sustain hydrostatic equilibrium; nearly
all asteroids and comets are small bodies.

Size: 0 (or Y for an entire Asteroid Belt).
Atmosphere: 0.
Hydrosphere: 0.
Biosphere: 0.
#### <span id="Snowball" class="mw-headline">Snowball</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=44 "Edit section: Snowball")<span class="mw-editsection-bracket">\]</span></span>

*Dwarf Group, GeoPassive Class, Gelidian Type, or GeoThermic Class,
Erisian Type, or GeoTidal Class, Plutonian Type.*\
These worlds are composed of mostly ice and some rock. They may have
varying degrees of activity, ranging from completely cold and still to
cryo-volcanically active with extensive subsurface oceans.

Size: 1d6-1.
Atmosphere: Roll 1d6.
1-4 — 0
5-6 — 1
Hydrosphere: Roll 1d6.
1-3 — A (entirely frozen)
4-6 — 2d6-2 (represents subsurface oceans)
Biosphere:
*Chemistry:* Roll 1d6. **DMs:** L star +2; Outer Zone +2.
1-4 — Water (Age modifier +0)
5-6 — Ammonia (Age modifier +1)
7-8 — Methane (Age modifier +3)
If subsurface oceans, and Age ≥ 1d6: 1d6-3.
If subsurface oceans, and Age ≥ 6 + modifier: 1d6+Size-2.
Otherwise: 0.
#### <span id="Stygian" class="mw-headline">Stygian</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=45 "Edit section: Stygian")<span class="mw-editsection-bracket">\]</span></span>

*Dwarf Group, GeoPassive Class, Stygian Type.* These are worlds that
were directly affected by their primary's transition from the main
sequence; they are melted and blasted lumps.

Size: 1d6-1.
Atmosphere: 0.
Hydrosphere: 0.
Biosphere: 0.
#### <span id="Tectonic" class="mw-headline">Tectonic</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=46 "Edit section: Tectonic")<span class="mw-editsection-bracket">\]</span></span>

*Terrestrial Group, Tectonic Class, Gaian / Amunian / Tartarian Types.*\
These are worlds with active plate tectonics and large bodies of surface
liquid, allowing for stable atmospheres and a high likelihood of life.

Size: 1d6+4.
Biosphere:
*Chemistry:* Roll 1d6. **DMs:** K-V star +2; M-V star +4; L star +5;
Outer Zone +2.
1-6 — Roll 2d6.
2-8 — Water (Age modifier +0) *\[Gaian\]*
9-11 — Sulfur (Age modifier +0) *\[ThioGaian\]*
12 — Chlorine (Age modifier +0) *\[ChloriticGaian\]*
7-8 — Ammonia (Age modifier +1) *\[Amunian\]*
9-10 — Methane (Age modifier +3) *\[Tartarian\]*
If Age ≥ 1d3 + modifier: 1d3.
If Age ≥ 4 + modifier: 2d6. **DMs:** D star -3.
Otherwise: 0.
Atmosphere:
If Biology 3+ and Water Chemistry: 2d6+Size-7, minimum 2, maximum 9.
If Biology 3+ and Sulfur or Chlorine Chemistry: B.
Otherwise: A.
Hydrosphere: 2d6-2.
#### <span id="Telluric" class="mw-headline">Telluric</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=47 "Edit section: Telluric")<span class="mw-editsection-bracket">\]</span></span>

*Terrestrial Group, Telluric Class, Phosphorian / Cytherean Types.*\
These are worlds with geoactivity but no hydrological cycle at all,
leading to dense runaway-greenhouse atmospheres.

Size: 1d6+4.
Atmosphere: C.
Hydrosphere: Roll 1d6.
1-4 — 0.
5-6 — F.
Biosphere: 0.
#### <span id="Vesperian" class="mw-headline">Vesperian</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=48 "Edit section: Vesperian")<span class="mw-editsection-bracket">\]</span></span>

*Dwarf Group, Epistellar Class, Vesperian Type.*\
These worlds are tide-locked to their primary, but at a distance that
permits surface liquid and the development of life.

Size: 1d6+4.
Biosphere:
*Chemistry:* Roll 2d6.
2-11 — Water
12 — Chlorine
If Age ≥ 1d3: 1d3.
If Age ≥ 4: 2d6.
Otherwise: 0.
Atmosphere:
If Biosphere 3+ and Water Chemistry: 2d6+Size-7, minimum 2, maximum 9.
If Biosphere 3+ and Chlorine: B.
Otherwise: A.
Hydrosphere: 2d6-2.
### <span id="Revised_Planetary_Profile_Codes" class="mw-headline">Revised Planetary Profile Codes</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=49 "Edit section: Revised Planetary Profile Codes")<span class="mw-editsection-bracket">\]</span></span>

#### <span id="Size" class="mw-headline">Size</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=50 "Edit section: Size")<span class="mw-editsection-bracket">\]</span></span>

0 — ≤800 km, neg. gravity
1 — 1,600 km, 0.05 G
2 — 3,200 km, 0.15 G (Triton, Luna, Europa)
3 — 4,800 km, 0.25 G (Mercury, Ganymede)
4 — 6,400 km, 0.35 G (Mars)
5 — 8,000 km, 0.45 G
6 — 9,600 km, 0.70 G
7 — 11,200 km, 0.9 G
8 — 12,800 km, 1.0 G (Terra)
9 — 14,400 km, 1.25 G
A — ≥16,000 km, ≥1.4 G
B-E — Helian sizes
G — Jovian sizes
X — Planetary-Mass Artifact
Y — Asteroid Belt
#### <span id="Atmosphere" class="mw-headline">Atmosphere</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=51 "Edit section: Atmosphere")<span class="mw-editsection-bracket">\]</span></span>

0 — Vacuum
1 — Trace
2 — Very Thin Tainted
3 — Very Thin Breathable
4 — Thin Tainted
5 — Thin Breathable
6 — Standard Breathable
7 — Standard Tainted
8 — Dense Breathable
9 — Dense Tainted
A — Exotic
B — Corrosive
C — Insidious
D — Super-High Density
G — Gas Giant Envelope
#### <span id="Hydrosphere" class="mw-headline">Hydrosphere</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=52 "Edit section: Hydrosphere")<span class="mw-editsection-bracket">\]</span></span>

0 — ≤5% (Trace)
1 — ≤15% (Dry / tiny ice caps)
2 — ≤25% (Small seas / ice caps)
3 — ≤35% (Small oceans / large ice caps)
4 — ≤45% (Wet)
5 — ≤55% (Large oceans)
6 — ≤65%
7 — ≤75% (Terra)
8 — ≤85% (Water world)
9 — ≤95% (No continents)
A — ≤100% (Total coverage)
B — Superdense (incredibly deep world oceans)
F — Intense Volcanism (molten surface)
G — Gas Giant Core
#### <span id="Biosphere" class="mw-headline">Biosphere</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=53 "Edit section: Biosphere")<span class="mw-editsection-bracket">\]</span></span>

0 — Sterile
1 — Building Blocks (amino acids, or equivalent)
2 — Single-celled organisms
3 — Producers (atmosphere begins to transform)
4 — Multi-cellular organisms
5 — Complex single-celled life (nucleic cells, or equivalent)
6 — Complex multi-cellular life (microscopic animals)
7 — Small macroscopic life
8 — Large macroscopic life
9 — Simple global ecology (life goes out of the oceans and onto land or
into the air, etc.)
A — Complex global ecology
B — Proto-sapience
C — Full sapience
D — Trans-sapience (able to deliberately alter their own evolution,
minimum Tech Level C)
If Biosphere C or more, this is a Homeworld; proceed to the Population
tables.

#### <span id="Population" class="mw-headline">Population</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=54 "Edit section: Population")<span class="mw-editsection-bracket">\]</span></span>

0 — Uninhabited
1 — Few
2 — Hundreds
3 — Thousands
4 — Tens of thousands
5 — Hundreds of thousands
6 — Millions
7 — Tens of millions
8 — Hundreds of millions
9 — Billions
A — Tens of billions
B — Hundreds of billions
C — Trillions
Includes all sapients.

#### <span id="Government" class="mw-headline">Government</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=55 "Edit section: Government")<span class="mw-editsection-bracket">\]</span></span>

0 — None (tends toward family/clan/tribal)
1 — Company or corporation
2 — Participatory democracy
3 — Self-perpetuating oligarchy
4 — Representative democracy
5 — Feudal technocracy
6 — Captive government (colony or conquered territory)
7 — Balkanized
8 — Civil service bureaucracy
9 — Impersonal bureaucracy
A — Charismatic dictator
B — Non-charismatic dictator
C — Charismatic oligarchy
D — Theocracy
E — Supreme authority
F — Hive-mind collective
#### <span id="Law_Level" class="mw-headline">Law Level</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=56 "Edit section: Law Level")<span class="mw-editsection-bracket">\]</span></span>

0 — No restrictions
1 — Only restrictions upon WMD and other dangerous technologies
2-4 — Light restrictions: heavy weapons, narcotics, alien technology
5-7 — Heavy restrictions: most weapons, specialized tools and
information, foreigners
8+ — Extreme restrictions: extensive monitoring and limitations, free
speech curtailed
#### <span id="Industry_Level" class="mw-headline">Industry Level</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=57 "Edit section: Industry Level")<span class="mw-editsection-bracket">\]</span></span>

Measures level of local production and support, not highest level known.

0 — No industry. Everything must be imported.
1-3 — Primitive. Mostly only raw materials made locally.
4-6 — Industrial. Local tools maintained, some produced.
7-9 — Pre-Stellar. Production and maintenance of space technologies.
A-B — Early Stellar. Support for A.I. and local starship production.
C-E — Average Stellar. Support for terraforming, flying cities, clones.
F — High Stellar. Support for highest of the high tech.
### <span id="Populations" class="mw-headline">Populations</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=58 "Edit section: Populations")<span class="mw-editsection-bracket">\]</span></span>

If a world has Biosphere C+, it is the homeworld of a sapient race.
Otherwise, you will have to determine if anyone has placed a colony or
outpost on this world. To do this, you will need to know:

*Settlement.* How long this region of space has been settled by
starfaring cultures, in centuries. Minimum 0 for recently-explored
regions. In the Imperium, some sectors have been settled for millenia;
subtract 3d6 centuries for the effects of the Long Night.
*Tech Level (TL).* The highest Tech Level of the dominant starfaring
culture. The Imperium and its neighbors have TL15. Jump capability
requires TL10 or higher; a TL9 culture can slowly colonize other stars
with using sub-light ships; a TL8 culture can colonize its own system
only; a TL7- culture cannot expand beyond its homeworld.
#### <span id="World_Desirability" class="mw-headline">World Desirability</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=59 "Edit section: World Desirability")<span class="mw-editsection-bracket">\]</span></span>

Whether or not starfarers take interest in a world depends on its
Desirability score, calculated as follows. These rules are are humans
and similar lifeforms; other sophonts may prefer other kinds of worlds,
and so should have different rules.

##### <span id="Asteroid_Belts" class="mw-headline">Asteroid Belts</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=60 "Edit section: Asteroid Belts")<span class="mw-editsection-bracket">\]</span></span>

For each belt, roll 1d6-1d6, and apply the following DMs:

-   *Flare Star* – M-Ve star: **-1d3**
-   *Lifebelt* – Inner Zone orbit: further detailed needed
    -   Any giant, brown dwarf, or white dwarf: **+0**
    -   M-V star: **+1**
    -   Any other dwarf or subgiant: **+2**

##### <span id="Dwarfs.2C_Terrestrials.2C_Helians.2C_and_Jovians" class="mw-headline">Dwarfs, Terrestrials, Helians, and Jovians</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=61 "Edit section: Dwarfs, Terrestrials, Helians, and Jovians")<span class="mw-editsection-bracket">\]</span></span>

For each such world, add up all the factors which apply:

-   *Dry World* – Hydro 0: **-1**
-   *Extreme Environment* – Size D+; or Atmos C-G; or Hydro F: **-2**
-   *Flare Star* – M-Ve star: **-1d3**
-   *Habitable World* – Size 1-B, Atmos 2-9, and Hydro 0-B: further
    detail needed
    -   *Garden World* – Size 5-A, Atmos 4-9, and Hydro 4-8: **+5**
    -   *Water World* – Hydro A-B: **+3**
    -   *Poor World* – Atmos 2-6, and Hydro 0-3: **+2**
    -   Otherwise: **+4**
-   *High Gravity* – Size A+ and Atmos F-: **-1**

*Note: Yes, normal Jovians don't count as "high gravity", as one doesn't
live on the surface.*
-   *Lifebelt* – Inner Zone orbit: further detail needed
    -   Any giant, brown dwarf, or white dwarf: **+0**
    -   M-V star: **+1**
    -   Any other dwarf or subgiant: **+2**
-   *Tiny World* – Size 0: **-1**
-   *T-Prime Atmosphere* – Atmos 6 or 8: **+1**

###### <span id="Terraforming" class="mw-headline">Terraforming</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=62 "Edit section: Terraforming")<span class="mw-editsection-bracket">\]</span></span>

At Tech Level 10+, any Inner Zone world with Size 1-B and Atmosphere
1-D, and *not* Hydro F, may be terraformed. For each such world, take
(TL+Settlement-15) OR (TL+1d6-15) points, whichever is more. You may add
these points to or subtract them from the world's Atmosphere,
Hydrosphere, or Biosphere codes, in order to improve their Desirability
ratings.

If you want to introduce Earthly bioforms to a world with alternative
biochemistry, you first have to exterminate the existing life by
reducing the Biosphere to 2 or less, *then* increase it.

Other suggested limits on terraforming:

Worlds with Hydro F cannot be terraformed, period.
Worlds with Hydro B cannot be reduced below Hydro B. There's just too
much ocean.
Worlds with Atmos B or C and Hydro 2+ cannot be reduced below Atmos B,
unless you first reduce them to Hydro 1 or less. After converting the
atmosphere, you may add water seas, increasing Hydro normally.
Worlds with native populations cannot be terraformed without genocide –
and the natives will resist. Treat population as another code to modify,
and reduce it to 1 or less before continuing.
Roll to see if there's an outpost first; if there is, terraforming may
proceed. Then roll to see if there's a colony after terraforming.
#### <span id="Habitation" class="mw-headline">Habitation</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=63 "Edit section: Habitation")<span class="mw-editsection-bracket">\]</span></span>

The Population, and resulting Government, Law, and Industry codes,
depend on the type of habitation.

-   If a world has Biosphere C+, it is the homeworld of an
    intelligent species.
-   For each world that is not a homeworld, roll 2d6-2. If you roll less
    than or equal to the world's Desirability score, then a colony has
    been placed there. (No colonies will be placed on worlds with
    Desirability less than 0.)
-   For each world that is not a homeworld or colony, roll 1d6, -1 in a
    culture's home system. If you roll less than or equal to (TL-9),
    then an outpost has been placed there.

##### <span id="Homeworld" class="mw-headline">Homeworld</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=64 "Edit section: Homeworld")<span class="mw-editsection-bracket">\]</span></span>

Population:
If normal carbon/water-based life: Desirability+1d3-1d3.
Other forms of life: 2d6.
Government:
If native TL 0: 0.
If native TL 1+, then roll 1d6:
If roll ≤ (native TL)-9: 7.
Otherwise: Population+2d6-7.
##### <span id="Colony" class="mw-headline">Colony</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=65 "Edit section: Colony")<span class="mw-editsection-bracket">\]</span></span>

Population: TL+Settlement-9, minimum 4, maximum = Desirability+1d3-1d3.
Government: Population+2d6-7.
If the world is habitable (Size 1-B, Atmos 2-9) and has no major
pre-existing lifeforms (Biosphere 2-), the colonists will seed the world
with friendly lifeforms, raising the local Biosphere to 1d6+5.

##### <span id="Outpost" class="mw-headline">Outpost</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=66 "Edit section: Outpost")<span class="mw-editsection-bracket">\]</span></span>

Population: 1d3+Desirability, maximum 4.
If Population = 0, there is only an automated beacon, listening post,
emergency cache, etc., but no permanent population.
Government:
If Population 0: 0.
Otherwise: Population+2d6-7, maximum 6.
##### <span id="Uninhabited" class="mw-headline">Uninhabited</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=67 "Edit section: Uninhabited")<span class="mw-editsection-bracket">\]</span></span>

Population: 0.
Government: 0.
#### <span id="Other_Population_Stats" class="mw-headline">Other Population Stats</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=68 "Edit section: Other Population Stats")<span class="mw-editsection-bracket">\]</span></span>

**Law Level**\

If Government 0: 0.
Otherwise: Government+2d6-7.
**Industrial Base**\

If Population 0: 0.
Otherwise: Population+2d6-7. **DMs:** Law 1-3 +1; Law 6-9 -1; Law A-C
-2; Law D+ -3; +1 if world is unsafe for human habitation (Atmos 0-4, 7,
9+; or Hydro F); TL 12-14 +1; TL15+ +2.
#### <span id="The_Effects_of_Local_Industry" class="mw-headline">The Effects of Local Industry</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=69 "Edit section: The Effects of Local Industry")<span class="mw-editsection-bracket">\]</span></span>

A world's Industrial Base affects its statistics as follows:

Industry 0: Population -1.
Industry 4-9: Population +1, Atmosphere modified as follows:
Atmos 3 becomes Atmos 2.
Atmos 5 becomes Atmos 4.
Atmos 6 becomes Atmos 7.
Atmos 8 becomes Atmos 9.
Industry A+: Choose one of the following:
*a)* Population +1, or
*b)* Population +2, and modify Atmosphere as above.
##### <span id="Hard_Times" class="mw-headline">Hard Times</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=70 "Edit section: Hard Times")<span class="mw-editsection-bracket">\]</span></span>

In a Long Night scenario, worlds are cut off from galactic trade and
forced to rely upon their own technology. Colonies on unsafe worlds
which have less than the required minimum Industrial Base have to be
abandoned; reduce Population to 0, leaving ruins behind.

Atmosphere 4, 7, or 9 requires Industry 3+ to maintain filter production
or air purification.
Atmosphere 2 or 3 requires Industry 5+ to maintain respirator
production.
Atmosphere 0, 1, or A requires Industry 8+ to maintain the pressure
habitats.
Atmosphere B or D requires Industry 9+ to maintain high-pressure or
corrosion-resistant habitats.
Atmosphere C or G, or Hydrosphere F, requires Industry A+ to maintain
deep-pressure or aerostat habitats.
Outposts on unsafe worlds *might* be maintained. If there's a colony or
homeworld nearby, make a roll at *their* Jump level, and if successful,
the outpost remains. Otherwise, it too must be abandoned.

If you want to get really complicated, than for any terraformed planet
during Hard Times, *reverse* the terraforming effects by points equal to
half the difference between the local Industrial Base and the old
galactic Tech Level (e.g. if you were at TL12, and are now at TL8, you
lose 4 points of terraforming).

#### <span id="Interstellar_Trade" class="mw-headline">Interstellar Trade</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=71 "Edit section: Interstellar Trade")<span class="mw-editsection-bracket">\]</span></span>

##### <span id="Trade_Codes" class="mw-headline">Trade Codes</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=72 "Edit section: Trade Codes")<span class="mw-editsection-bracket">\]</span></span>

*Agricultural (Ag):* Atmos 4-9, Hydro 4-8, Pop 5-7.
*Asteroid Belt (As):* Asteroid Belt.
*Desert (De):* Atmos 2-D, Hydro 0.
*Fluid Oceans (Fl):* Atmos A+ or non-water biochemistry, Hydro 1-B.
*Garden (Ga):* Size 5-A, Atmos 4-9, Hydro 4-8.
*High Population (Hi):* Pop 9+.
*High Technology (Ht):* Industry (TL-3)+.
*Ice-Capped (Ic):* Atmos 0-1, Hydro 1+.
*Industrial (In):* Pop 9+, Industry 6+.
*Low Population (Lo):* Pop 1-3.
*Low Technology (Lt):* Industry 5-.
*Non-Agricultural (Na):* Atmos 0-3 or B+, Hydro 0-3 or B+, Pop 6+.
*Non-Industrial (Ni):* Pop 4-6.
*Poor (Po):* Atmos 2-5, Hydro 0-3.
*Rich (Ri):* Atmos 6 or 8, Pop 6-8.
*Sterile (St):* Bio 0.
*Water World (Wa):* Atmos 2+, Hydro A-B.
*Vacuum (Va):* Atmos 0.
*Zoo (Zo):* Bio 7+.
##### <span id="Starport" class="mw-headline">Starport</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=73 "Edit section: Starport")<span class="mw-editsection-bracket">\]</span></span>

Roll 2d6+Industry-7. **DMs:** Ag +1, Ga +1, Hi +1, Ht +1, In +1, Na +1,
Ri +1, TL12-14 +1, TL15+ +2, Lo -1, Po -1, TL9- -1.

≤2 — X
3-4 — E
5-6 — D
7-8 — C
9-10 — B
11≤ — A
An Outpost world with Population 0 automatically has the equivalent of
an E-class starport, in the form of an unmanned navigation beacon and
emergency supply cache.

Any world with Industry 5+ must have at least the equivalent of an
E-class starport, in its airstrips or surface shipping ports.

Any uninhabitable world with Population 1+ must have at least the
equivalent of an E-class starport, in its airlocks and docking ports.

##### <span id="Bases" class="mw-headline">Bases</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=74 "Edit section: Bases")<span class="mw-editsection-bracket">\]</span></span>

Roll 2d6 for all of these.

**Ancients Site (Q)**

Per system: Throw 12+. If present, select a world at random.
**Imperial Consulate, Governor's Estate (G)**

Starport A: Throw 6+.
Success by 3+ means also a foreign embassy or diplomatic consulate (F).
Success by 6+ means also a Moot seat or other government center.
Any Capital automatically has Starport A and government center.
Starport B: Throw 8+.
Success by 3+ means also a foreign embassy or diplomatic consulate (F).
Starport C: Throw 10+.
**Merchant Base (M)**

Starport A: Throw 6+.
Success by 3+ means also a shipyard (Y).
Success by 6+ means also a megacorporate headquarters.
Starport B: Throw 8+.
Success by 3+ means also a shipyard (Y).
Starport C: Throw 10+.
**Naval Base (N)**

Starport A, B, or C: Throw 8+.
Success by 3+ means also a shipyard or galactic hospital (Y or H).
**Pirate Base (P)**

Starport B: Throw 12+.
Starport C: Throw 10+.
Starport D or E: Throw 12+.
**Psionics Institute (Z)**

Any inhabited world: Throw 12+.
**Research Installation (R)**

Starport A: Throw 8+
Success by 3+ means also a galactic hospital, university or library
archive (H, U, or L).
Starport B or C: Throw 10+.
Outpost: Throw 9+.
Success by 3+ means also a backup library archive (L).
**Sacred Site (K)**

Any inhabited world: Roll 2d6 ≤ Pop.
**Scout Base (S)**

Starport A: Throw 10+.
Starport B or C: Throw 8+.
Success by 3+ means also a scout hostel.
Starport D: Throw 7+.
Success by 3+ means also a scout hostel.
**Special Enclave, Nature Preserve, Prison (V)**

Any world with Pop 1+ or Bio 1+: Throw 10+.
**Traveller's Aid Society Hostel (T)**

Starport A: Throw 4+.
Success by 3+ means first-class accommodations.
Success by 6+ means a full chapter-house.
Starport B: Throw 6+.
Success by 3+ means first-class accommodations.
Starport C: Throw 10+.
**Weather Control Station, Terraforming Facility (W)**

Any terraformed world: Automatic.
###### <span id="Base_Codes" class="mw-headline">Base Codes</span><span class="mw-editsection"><span class="mw-editsection-bracket">\[</span>[edit](/index.php?title=RTT_Worldgen&action=edit&section=75 "Edit section: Base Codes")<span class="mw-editsection-bracket">\]</span></span>

**A** — A-class (Excellent) Starport
**B** — B-class (Good) Starport
**C** — C-class (Routine) Starport
**D** — D-class (Poor) Starport
**E** — E-class (Frontier) Starport or Emergency Beacon
**F** — Foreign Embassy / Diplomatic Consulate
**G** — Imperial Consulate / Governor's Estate
**H** — Galactic Hospital
**J** — Ansible / Stargate
**K** — Galactic church, temple, or other religious site
**L** — Library Archive
**M** — Merchant / Megacorporate base
**N** — Naval base
**P** — Pirate base
**Q** — Ancients' site
**R** — Research installation
**S** — Scout base
**T** — Travellers' Aid Society Hostel
**U** — Galactic University
**V** — Special enclave (prison, refugee facility, nature preserve,
etc.)
**W** — Weather control / terraforming facility
**X** — No starport
**Y** — Shipyard
**Z** — Psionics Institute

</div>

</div>
