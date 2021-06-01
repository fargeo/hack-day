# <img src="img/fargeo.png" style="width: 100px; margin-right:10px;"/> June 2021 Hack Trip: Sunriver

## Schedule: June 6-9, 2021

### Sunday, June 6, 2019:
- **5:00-9:00PM** Check-in, discuss our goals over drinks and dinner 🍺

### Thursday, June 7, 2019:
- **9:00AM-12:00PM:** hack ⌨️
- **12:00-1:00PM:** lunch 🍴
- **1:00-4:00PM:** hack 🖥
- **4:00-5:00PM:** break 😅
- **5:00PM-?:** hack 🛠 & dinner 🍴

### Friday, June 8, 2019:
- **9:00AM-12:00PM:** hack 💻
- **12:00-1:00PM:** lunch 🍴
- **1:00-4:00PM:** hack 📱
- **4:00-5:00PM:** break 😅
- **5:00PM-?:** hack 🤘 & dinner🍴

### Wednesday, June 9:
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
1. Build a custom mobile application for an existing Arches workflow using Flutter
    - Goals:
        - Deploy a hosted Arches For Science instance in AWS to be used during development
        - Automate deployment and explore Dockerization, Kubernetes, and security concerns (stretch goal)
        - Build a mobile application using Flutter that recreates the business process of an Arches For Science workflow using the Arches API.
    - Required Software:
        - [Flutter](https://flutter.dev/docs/get-started/install)
    - Reading:
        - [Write your first Flutter App](https://flutter.dev/docs/get-started/codelab)
2. Export a relational schema from Arches resource models
    - Goals:
        - Write a script to automate generation of SQL from an existing Arches database that will create related tables for each nodegroup in a resource model
        - Extend the script to support creation of database constraints based on graph/node datatypes and configurations (stretch goal)
        - Write a script that will populate the relation schema created by the above script from existing Arches business data (stretch goal)
3. Use Silk for profiling and optimization of Arches database queries
    - Goals:
        - use Silk to identify opportunites to optimize the load time for Arches pages/services
        - based on query volume & timing, identify patterns to optimize Arches views
        - implement high return optimizations in Arches view code
    - Required Software:
        - [django-silk](https://github.com/jazzband/django-silk)
    - Reading:
        - [Silk Docs](https://silk.readthedocs.io/en/latest/)

At the conclusion of our work, each team should be prepared to briefly (15-30 minutes) present their results and findings to the other teams.

## Teams

Group should be split into three (or four) teams working in 1-2 hour sprints on a given task. Teams will check in for 5-15 minutes between each sprint to see where things are at and plan next tasks.

Here are the initial team assignments:

1. **Build a custom mobile application for an existing Arches workflow using Flutter**:
    - Rob
    - Cyrus
2. **Export a relational schema from Arches resource models**:
    - Adam
    - Dennis
    - Ryan
3. **Use Silk for profiling and optimization of Arches database queries**:
    - Alexei
    - Namjun
    - Christopher

Each team should strive to hack together, on a single machine as much as possible.  The driver role should rotate every 20-30 minutes and each member should drive at least once per sprint.

Members should feel free to change team membership or reorganize teams as desired during the hack.

## Code organization

Coding for track **1** & **2** will be done in branches of the [`fargeo/sunriver`](https://github.com/fargeo/sunriver) repo (`flutter` and `schema_export` respectively).

Each team will code in a separate branch, merging work branches as needed.

Core Arches development work will be done in branches of the [`fargeo/arches` fork](https://github.com/fargeo/arches); we should create a new branch (off of `stable/5.2.x`) for each track that requires core arches development.

Instead of cloning the `fargeo/arches` fork, it is probably much easier to just [change remote](#preparation) on your existing local arches repo.

After the trip, you can change your Arches repo's remote back with the following command:
```
git remote set-url origin https://github.com:archesproject/arches.git
```

## Preparation

Please do the following before arriving:

- re-read this page (it's being updated daily)
- if possible, bring adapters and cables (esp. HDMI) to connect your laptop to house TVs

- change your arches repo remote to point to [`fargeo/arches`](https://github.com/fargeo/arches) and checkout the `sunriver` branch by running the following:
```
git remote set-url origin https://github.com:fargeo/arches.git
git fetch
git checkout sunriver
```

- clone the [`fargeo/sunriver`](https://github.com/fargeo/sunriver) repo
