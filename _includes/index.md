# <img src="img/fargeo.png" style="width: 100px; margin-right:10px;"/> October 2023 Hack Trip: San Diego

## Schedule: October 4-7, 2023

### Wednesday, October 4, 2023:
- **5:00-9:00PM** Check-in, discuss our goals over drinks and dinner 🍺 at [El Salvadoreño](https://elsalvadorenosd.com/)

### Thursday, October 5, 2023:
- **9:00AM-12:00PM:** hack ⌨️
- **12:00-1:00PM:** lunch 🍴
- **1:00-5:30PM:** hack 🖥
- **5:30-6:00PM:** break 😅
- **7:00PM:** dinner at [Karina's Seafood](https://www.karinasseafood.com/gaslamp-quarter/)🍴

### Friday, October 6, 2023:
- **9:00AM-12:00PM:** hack ⌨️
- **12:00-1:00PM:** lunch 🍴
- **1:00-2:30PM:** hack 📱
- **3:00:** meet time at Star Park in Coronado (1030 Park Place, Coronado)
- **5:00PM:** dinner 🍴 & drinks 🍺 at [Coronado Brewing](https://coronadobrewing.com/updated-hours-and-offerings/)

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
1. Adding data integrity checks to the validate command (esp. in the context of resource model changes)
    - Goals:
        - Investigate and enumerate the domain of data integrity checks (checking business data relative to model definition) for Arches data
        - Implement logic to perform these checks (preferably in a way that is reusable in both the DB and application)
        - Add these checks to the validate management command
2. Adding instrumentation/observability to Arches Stack to support distributed tracing
    - Goals:
        - Use OpenTelemetry to get telemetry from Arches software dependencies and code
        - Create and visualize a distributed trace in arches using OpenTelemetry
    - Reading:
        - [OpenTelemetry - Getting Started](https://opentelemetry.io/docs/collector/getting-started/)
        - [Getting started with OpenTelemetry visualization](https://signoz.io/blog/opentelemetry-visualization/)
3. Recreate SF Planning field data collection workflow using Survey 123, arcgis online and a custom importer to arches
    - Goals:
        - Create feature classes (or other entities) in ArcGIS Online to support managing field data collection
        - Export Arches data to ArcGIS Online entities using custom exporter
        - Create a Survey123 workflow to mirror the existing field data collection workflow in Arches
        - Import data back into Arches from ArcGIS Online
        - Include images submitted via Survey123 in the import into Arches (stretch goal)
    - Required Software:
        - ArcGIS Online & ArcGIS Survey123 (Cloud)
    - Reading:
        - [ArcGIS Survey123](https://www.esri.com/en-us/arcgis/products/arcgis-survey123/overview?rsource=%2Fen-us%2Farcgis%2Fproducts%2Fsurvey123%2Foverview)
4. Prototype a Vue-based Arches index page
    - Goals:
        - Redesign index page for Arches to modernize and add modularity
        - Rebuild index page using Vue (and PrimeVue?) and eliminating old/distinct dependencies
        - "Componentize" index page to allow for modularity/configurability
    - Reading:
        - [PrimeVue](https://primevue.org/)


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
