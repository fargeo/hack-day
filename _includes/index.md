# <img src="img/fargeo.png" style="width: 100px; margin-right:10px;"/> April 2022 Hack Trip: Kona

## Schedule: April 18-21, 2022

### Monday, April 18, 2022:
- **5:00-9:00PM** Check-in, discuss our goals over drinks and dinner 🍺

### Tuesday, April 19, 2022:
- **9:00AM-12:00PM:** hack ⌨️
- **12:00-1:00PM:** lunch 🍴
- **1:00-4:00PM:** hack 🖥
- **4:00-5:00PM:** break 😅
- **5:00PM-?:** hack 🛠 & dinner 🍴

### Wednesday, April 20, 2022:
- **9:00AM-12:00PM:** hack 💻
- **12:00-1:00PM:** lunch 🍴
- **1:00-4:00PM:** hack 📱
- **4:00-5:00PM:** break 😅
- **5:00PM-?:** hack 🤘 & dinner🍴

### Thursday, April 21, 2022:
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
1. Flutter Arches SDK prototype development
    - Goals:
        - Create a prototype Arches Flutter SDK for creating Arches mobile applications
        - Develop reusable component(s) for interacting with Arches API, for example:
            - Login component
            - Resource reports
            - Resource instance map?
        - Demonstrate how a Flutter application could use this SDK to integrate with an Arches server
    - Required Software:
        - [Flutter](https://flutter.dev/docs/get-started/install)
    - Reading:
        - [Developing Flutter Packages](https://docs.flutter.dev/development/packages-and-plugins/developing-packages)
2. Geoprocessing/visualization stack using Arches relational views/additional use cases for Arches relational views
    - Goals:
        - Write a geoprocessing function using relational views then serve that up to Arches via pg_tileserve or otherwise
        - Visualize/report on Arches data (USD SSC?) using off the shelf reporting tools for PostgreSQL
        - Prototype a front end component for managing tile data directly in relational views using Django ORM
    - Reading:
        - [PostgreSQL reporting tools](https://www.postgresql.org/download/products/5-reporting-tools/)
3. Prototype using an alternative front-end framework for Arches component(s) 
    - Goals:
        - Choose a framework with which to develop drop-in replacements for Arches components
        - Prototype the development of Arches components (or pages) using an alternative framework. Possibilities include:
            - resource designer/editor headers,
            - resource instance forms (custom card components?)
            - rework a simple page (resource edit history page?)
        - Demonstrate how data flow within the new component tree and between the new and old (knockout) component trees

At the conclusion of our work, each team should be prepared to briefly (15-30 minutes) present their results and findings to the other teams.

## Teams

Group should be split into three (or four) teams working in 1-2 hour sprints on a given task. Teams will check in for 5-15 minutes between each sprint to see where things are at and plan next tasks.

Here are the initial team assignments:

1. **Flutter Arches SDK prototype development**:
    - Alexei
    - Cyrus
    - Dennis
2. **Geoprocessing/visualization stack using Arches relational views/additional use cases for Arches relational views**:
    - Adam
    - Namjun
    - Rob
3. **Prototype using an alternative front-end framework for Arches component(s)**:
    - Aaron
    - Christopher
    - Ryan

Each team should strive to hack together, on a single machine as much as possible.  The driver role should rotate every 20-30 minutes and each member should drive at least once per sprint.

Members should feel free to change team membership or reorganize teams as desired during the hack.

## Code organization

Non-Arches development for will be done in branches of the [`fargeo/kona`](https://github.com/fargeo/kona) repo.

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
