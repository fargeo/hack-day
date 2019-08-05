# <img src="img/fargeo.png" style="width: 100px; margin-right:10px;"/> August 2019 Hack Trip: Salinas

## Schedule: August 7-10, 2019

### Wednesday, August 7, 2019:
- **11:00AM-3:30PM:** Wine tasting
- **3:30-9:00PM** Check-in, discuss our goals over drinks and dinner 🍺

### Thursday, August 8, 2019:
- **9:00AM-12:00PM:** hack ⌨️
- **12:00-1:00PM:** [lunch 🍴](#food)
- **1:00-4:00PM:** hack 🖥
- **4:00-5:00PM:** break 😅
- **5:00PM-?:** hack 🛠 & [dinner🍴](#food)

### Friday, August 9, 2019:
- **9:00AM-12:00PM:** hack 💻
- **12:00-1:00PM:** [lunch 🍴](#food)
- **1:00-4:00PM:** hack 📱
- **4:00-5:00PM:** break 😅
- **5:00PM-?:** hack 🤘 & [dinner🍴](#food)

### Saturday, August 10, 2019:
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

For this hack trip, we are going to be exploring a variety of tracks (three to start), each with its own set of goals.
1. Prototype an Arches Esri FeatureService using [Koop.js](https://koopjs.github.io/)
    - Goals:
        - Write a custom Koop provider that pulls data from Arches
        - Implement the "Esri GeoServices" output for Koop
        - Use ArcGIS Pro (or similar) to visualize Arches data via Koop Esri GeoServices output
        - Explore ways to secure Koop services either natively or by proxying through Arches authentication
    - Reading:
        - [What is Koop?](https://koopjs.github.io/docs/basics/what-is-koop)
        - [Koop.js in Layman’s Terms](https://medium.com/@lusisuwandi/koop-js-in-laymans-terms-15549599ae7)
        - [koop-cli](https://github.com/koopjs/koop-cli)
2. Prototype an ArcGIS Pro add-in for accessing Arches resource instance data via API
    - Goals:
        - Create a simple ArcGIS Pro add-in
        - Create a UI for the add-in that allows a user to authenticate via the Arches API
        - Prompt the user to provide a resource instance ID, and use that ID to retreive resource instance data via the Arches API
        - Visualize Arches resource instance data in the add-in UI (for example, a tree of tile data or a mini report on individual tiles)
        - Show geospatial data for selected resource instance on the ArcGIS Pro map
    - Required Software:
        - ArcGIS Pro
        - [Visual Studio](https://visualstudio.microsoft.com/) ([Mac C# setup guide](https://www.youtube.com/watch?v=71i5C0l4POw))
    - Reading:
        - [Build your first add-in](https://developers.arcgis.com/labs/pro/build-your-first-add-in/)
        - [ProGuide Build your first add in](https://github.com/Esri/arcgis-pro-sdk/wiki/ProGuide-Build-your-first-add-in)
3. Improve performance of the arches business data import routine
    - Goals:
        - Find ways to improve the overall performance of Arches business data load (concepts & resource instances)
    - Reading:
        - [How to Use Django Bulk Inserts for Greater Efficiency](https://www.caktusgroup.com/blog/2019/01/09/django-bulk-inserts/)
        - [Django Data Wizard](https://github.com/wq/django-data-wizard)

If deemed necessary, we can split off a fourth track:
4. Use [Kibana](https://www.elastic.co/products/kibana) and custom ES indexes to build interactive dashboards for Arches
    - Goals:
        - Create a custom index that would calculate Statistics on Arches resources (eg total new records by model)
        - Create a simple Kibana dashboard to render data from the new custom index
        - Create an Arches plugin that would wrap the Kibana dashboard for use inside the Arches web application
    - Reading:
        - [Kibana User Guide](https://www.elastic.co/guide/en/kibana/6.7/introduction.html)
        - [Kibana tutorial](https://logz.io/blog/kibana-tutorial/)

At the conclusion of our work, each team should be prepared to briefly (15-30 minutes) present their results and findings to the other teams.

## Teams

Group should be split into three (or four) teams working in 1-2 hour sprints on a given task. Teams will check in for 5-15 minutes between each sprint to see where things are at and plan next tasks.

Here are the initial team assignments:

1. **Prototype an Arches Esri FeatureService using Koop.js**:
    - Ryan
    - Rob
    - Dennis
2. **Prototype an ArcGIS Pro add-in for accessing Arches resource instance data via API**:
    - Namjun
    - Adam
    - Cyrus
3. **Improve performance of the arches business data import routine**:
    - Galen
    - Alexei

Each team should strive to hack together, on a single machine at a time.  The driver role should rotate every 20-30 minutes and each member should drive at least once per sprint.

Members should feel free to change team membership or reorganize teams as needed during the hack day.

## Code organization

Coding for tracks **1** & **2** will be done in branches of the [`fargeo/salinas`](https://github.com/fargeo/salinas) repo (`koop_prototype` and `arcgis_pro_prototype` respectively).

For track **1**, after cloning the [`fargeo/salinas`](https://github.com/fargeo/salinas) repo and checking out the `koop_prototype` branch, you will need to run the following to install dependencies:
```
yarn install
```

Each team will code in a separate branch, merging into `master` as needed.

Core Arches development work will be done in branches of the [`fargeo/arches` fork](https://github.com/fargeo/arches); we should create a new branch for each track that requires core arches development.

Instead of cloning the `fargeo/arches` fork, it is probably much easier to just [change remote](#preparation) on your existing local arches repo.

After the trip, you can change your Arches repo's remote back with the following command:
```
git remote set-url origin https://github.com:archesproject/arches.git
```

## Preparation

Please do the following before arriving:

- re-read this page (it's being updated daily)
- add or suggest food/drink places and/or activities (below)
- if possible, bring adapters and cables (esp. HDMI) to connect your laptop to house TVs

- change your arches repo remote to point to [`fargeo/arches`](https://github.com/fargeo/arches) and checkout the `salinas` branch by running the following:
```
git remote set-url origin https://github.com:fargeo/arches.git
git fetch
git checkout salinas
```

- clone the [`fargeo/salinas`](https://github.com/fargeo/salinas) repo


## Food

Since we're in Salinas this time, most of the meals will be catered, but for dinner on Thursday and lunch on Friday were going to be on our own, so we'll need to pick destinations in/around Salinas for those meals.  Here are some options:

🍴&🍻 | **Salinas** | **Monterey** 
--- | --- | --- 
 | [Patria](https://www.yelp.com/biz/patria-salinas) | [Montrio](https://www.montrio.com/menu/)
 |  | [Bull and Bear](https://bullandbearca.com/)
{:.table}
