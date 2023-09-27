# <img src="img/fargeo.png" style="width: 100px; margin-right:10px;"/> October 2023 Hack Trip: San Diego

## Schedule: October 4-7, 2023

### Wednesday, October 4, 2023:
- **5:00-9:00PM** Check-in, discuss our goals over drinks and dinner 🍺

### Thursday, October 5, 2023:
- **9:00AM-12:00PM:** hack ⌨️
- **12:00-1:00PM:** lunch 🍴
- **1:00-4:00PM:** hack 🖥
- **4:00-5:00PM:** break 😅
- **5:00PM-?:** hack 🛠 & dinner 🍴

### Friday, October 6, 2023:
- **9:00AM-12:00PM:** hack ⌨️
- **12:00-1:00PM:** lunch 🍴
- **1:00-5:00PM:** hack 📱
- **4:00-5:00PM:** break 😅
- **5:00PM-?:** hack 🛠 & dinner 🍴

### Saturday, October 7, 2023:
- **9:00AM-12:00PM:** Debrief and head home 🚘

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
1. Data validation in the context of resource model changes, adding data integrity checks to the validate command
    - Goals:
        - 
    - Required Software:
        - 
    - Reading:
        - 
2. Adding instrumentation/observability to Arches Stack to support distributed tracing
    - Goals:
        - 
    - Required Software:
        - 
    - Reading:
        - 
3. Recreate SF Planning field data collection workflow using Survey 123, arcgis online and a custom importer to arches
    - Goals:
        - 
    - Required Software:
        - 
    - Reading:
        - 
4. Prototype a Vue index page (or other page in arches)
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

1. **Data validation in the context of resource model changes, adding data integrity checks to the validate command**
    - Adam
    - Jacob
    - Johnathan
2. **Adding instrumentation/observability to Arches Stack to support distributed tracing**
    - Aaron
    - Rob
    - Ryan
3. **Recreate SF Planning field data collection workflow using Survey 123, arcgis online and a custom importer to arches**
    - Cyrus
    - Namjun
    - Peter
4. **Prototype a Vue index page (or other page in arches)**
    - Alexei
    - Christopher
    - Dennis

Each team should strive to hack together, on a single machine as much as possible.  The driver role should rotate every 20-30 minutes and each member should drive at least once per sprint.

Members should feel free to change team membership or reorganize teams as desired during the hack.

## Code organization
Non-Arches development will be done in branches of the [`fargeo/san_diego_hack`](https://github.com/fargeo/san_diego_hack) repo.

Each team will code in a separate branch, merging work branches as needed.

Core Arches development work will be done in branches of the [`fargeo/arches` fork](https://github.com/fargeo/arches).  We will be using the [sfplanning](https://github.com/fargeo/sfplanning) project as our default project unless teams determine otherwise.

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
- clone the [`fargeo/san_diego_hack`](https://github.com/fargeo/san_diego_hack) repo
