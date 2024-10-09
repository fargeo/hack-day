# <img src="img/fargeo.png" style="width: 100px; margin-right:10px;"/> October 2024 Hack Trip: Palm Springs

## Venue
**Blackhaus**<br/>
[Check in & Accomodation Information](https://avantstay.com/reservation-hub/8GKLDGVK/things-to-know?token=5WYKmJ2DGWt7XdMxYM%2BzGf%2FKHum7U6xFFrCusXCz5CJLOSyYvWmF7wxMDAO0s6Ro7egOm9NU1F9hofL9QpM3%2FA%3D%3D)<br/>
Address: [421 S Calle Encilia<br/>Palm Springs, CA 92262](https://maps.app.goo.gl/aeM7tc6C88WYVGbJ7)

## Schedule: October 13-16, 2023

### Sunday, October 13, 2023:
- **5:00-9:00PM** Check-in, discuss our goals over drinks and dinner 🍺 at ...

### Monday, October 14, 2023:
- **9:00AM-12:00PM:** hack ⌨️
- **12:00-1:00PM:** lunch 🍴
- **1:00-5:30PM:** hack 🖥
- **5:30-6:00PM:** break 😅
- **7:00PM:** dinner at ...🍴

### Tuesday, October 15, 2023:
- **7:00AM-11:30PM:** ATV Riding at [Steve's ATV Rentals](https://stevesatvrentals.com/palm-springs-atv-rentals/)
    - Depart by 7am to arrive at 8am for waivers and safety briefings
    - [Directions](https://maps.app.goo.gl/nxAVhh9GLa16e9DM9)
- **11:30-1:00PM:** lunch & travel back to Blackhaus 🍴
- **1:00-5:30PM:** hack 🖥
- **5:30-6:00PM:** break 😅
- **7:00PM:** dinner at ...🍴

### Wednesday, October 16, 2023:
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
1. **Create arches application to replace mapbox-gl-js with MapLibre**
    - Goals:
        - Insert goals here
    - Reading:
        - Any relevant readings here
2. **Python/Go Compare Arches Companion benchmarks to Arches, optimize arches based on companion implementation (resources API)**
    - Goals:
        - Insert goals here
    - Reading:
        - Any relevant readings here
3. **General performance improvements (N+1 queries, caching, psycopg 3, UUIDv7, add index to resourceid in edit log)**
    - Goals:
        - Insert goals here
    - Reading:
        - Any relevant readings here
4. **Lessons/philosophizing on better resource forecasting (using Zoho or other tools)**
    - Goals:
        - Insert goals here
    - Reading:
        - Any relevant readings here


At the conclusion of our work, each team should be prepared to briefly (15-30 minutes) present their results and findings to the other teams.

## Teams

Group should be split into three (or four) teams working in 1-2 hour sprints on a given task. Teams will check in for 5-15 minutes between each sprint to see where things are at and plan next tasks.

Here are the initial team assignments:

1. **Create arches application to replace mapbox-gl-js with MapLibre**
    - Christopher
    - Johnathan
    - Rob
2. **Python/Go Compare Arches Companion benchmarks to Arches, optimize arches based on companion implementation (resources API)**
    - Alexei
    - Jacob
    - Dennis
3. **General performance improvements (N+1 queries, caching, psycopg 3, UUIDv7, add index to resourceid in edit log)**
    - Aaron
    - Cyrus
    - Namjun
4. **Lessons/philosophizing on better resource forecasting (using Zoho or other tools)**
    - Adam
    - Alex
    - Peter
    - Dennis

Each team should strive to hack together, on a single machine as much as possible.  The driver role should rotate every 20-30 minutes and each member should drive at least once per sprint.

Members should feel free to change team membership or reorganize teams as desired during the hack.

## Code organization
Non-Arches development will be done in branches of the [`fargeo/palm_springs_hack`](https://github.com/fargeo/palm_springs_hack) repo.

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
- clone the [`fargeo/palm_springs_hack`](https://github.com/fargeo/palm_springs_hack) repo
