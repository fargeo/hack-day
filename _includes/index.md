# <img src="img/fargeo.png" style="width: 100px; margin-right:10px;"/> November 2022 Hack Trip: Pajaro Dunes

## Schedule: November 13-16, 2022

### Sunday, November 13, 2022:
- **5:00-9:00PM** Check-in, discuss our goals over drinks and dinner 🍺

### Monday, November 14, 2022:
- **9:00AM-12:00PM:** hack ⌨️
- **12:00-1:00PM:** lunch 🍴
- **1:00-4:00PM:** hack 🖥
- **4:00-5:00PM:** break 😅
- **5:00PM-?:** hack 🛠 & dinner 🍴

### Tuesday, November 15, 2022:
- **8:00AM-12:00PM:** kayaking at Moss Landing 🚣‍♀️
- **12:00-1:00PM:** lunch 🍴
- **1:00-5:00PM:** hack 📱
- **4:00-5:00PM:** break 😅
- **5:00PM-?:** hack 🛠 & dinner 🍴

### Wednesday, November 16, 2022:
- **9:00AM-10:00AM:** Debrief and head home 🚘

## Priorities

While hacking, please keep in mind these priorities, in order of importance:

1. Listen and learn
2. Share knowledge and techniques
3. Try new things and gain new knowledge/insights
4. Have fun/team building
5. Produce usable code, prototypes or demos

Priorities #1-4 are **essential**.  Priority #5 would be nice to have.

## Goals 💯

For this hack trip, we are going to be exploring three tracks, each with its own set of goals.
1. Develop a Django application to update business data in Arches using relational views
    - Goals:
        - 
    - Required Software:
        - 
    - Reading:
        - 
1. Develop a Django application to update business data in Arches using relational views
    - Goals:
        - 
    - Required Software:
        - 
    - Reading:
        - 
1. Develop a Django application to update business data in Arches using relational views
    - Goals:
        - 
    - Required Software:
        - 
    - Reading:
        - 
1. Develop a Django application to update business data in Arches using relational views
    - Goals:
        - 
    - Required Software:
        - 
    - Reading:
        - 

At the conclusion of our work, each team should be prepared to briefly (15-30 minutes) present their results and findings to the other teams.

## Teams

Group should be split into three (or four) teams working in 1-2 hour sprints on a given task. Teams will check in for 5-15 minutes between each sprint to see where things are at and plan next tasks.

Here are the initial team assignments:

1. **Develop a Django application to update business data in Arches using relational views**
    - Adam
    - Alexei
    - Johnathan
2. **Automate common workflows in AWS for Arches using AWS step functions (or similar)**
    - Aaron
    - Rob
3. **Use ArcGIS Javascript API in Arches to export data to AGOL and visualize**
    - Christopher
    - Namjun
4. **Using PgFeatureServe to execute geoprocessing task via Arches map widget for data editing**
    - Peter
    - Dennis
    - Ryan

Each team should strive to hack together, on a single machine as much as possible.  The driver role should rotate every 20-30 minutes and each member should drive at least once per sprint.

Members should feel free to change team membership or reorganize teams as desired during the hack.

## Code organization
Non-Arches development will be done in branches of the [`fargeo/kona`](https://github.com/fargeo/kona) repo.

Each team will code in a separate branch, merging work branches as needed.

Core Arches development work will be done in branches of the [`fargeo/arches` fork](https://github.com/fargeo/arches).

Instead of cloning the `fargeo/arches` fork, it is probably much easier to just [change remote](#preparation) on your existing local arches repo.

After the trip, you can change your Arches repo's remote back with the following command:
```
git remote set-url origin https://github.com:archesproject/arches.git
```

## Preparation

Please do the following before arriving:

- re-read this page (it's being updated daily)
- if possible, bring adapters and cables (esp. HDMI) to connect your laptop to TVs
- change your arches repo remote to point to [`fargeo/arches`](https://github.com/fargeo/arches) by running the following:
```
git remote set-url origin https://github.com:fargeo/arches.git
git fetch
```
- checkout the branches you will be working on
- clone the [`fargeo/kona`](https://github.com/fargeo/kona) repo
