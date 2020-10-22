# <img src="img/fargeo.png" style="width: 100px; margin-right:10px;"/> Fall 2020 Remote Hack Trip: Earth

## Schedule: Fall, 2020

##Docker Dev Hack
### Friday, October 21, 2020:
- **12:00PM-4:00PM:** Setup/Hack ⌨️

### Wednesday, October 21, 2020:
- **12:00PM-4:00PM:** Hack ⌨️

### Friday, October 23, 2020:
- **12:00PM-4:00PM:** Hack ⌨️

### Wednesday, October 28, 2020:
- **12:00PM-4:00PM:** Hack ⌨️

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
1. Create an Arches dev environment using Docker
    - Goals:
        - Rewrite/update docker-compose, Dockerfile, and entrypoint.sh files as necessary
        - Allow developer to link to local Arches directory to container
        - Eliminate virtual env(?)
        - Script project dependency load
        - Script project/package load
        - EXPLORATORY: Containerize projects with Arches container as a dependency
    - Required Software:
        - [Docker Desktop](https://www.docker.com/products/docker-desktop)
    - Resources:
        - [Docker Mastery](https://www.udemy.com/course/docker-mastery/) Credentials in LastPass

At the conclusion of our work, each team should be prepared to briefly (15-30 minutes) present their results and findings to the other teams.

## Teams

Group should be split into three (or four) teams working in 1-2 hour sprints on a given task. Teams will check in for 5-15 minutes between each sprint to see where things are at and plan next tasks.

Here are the initial team assignments:

1. **Prototype an Arches Esri FeatureService using Koop.js**:
    - Ryan
    - Namjun
    - Dennis

Members should feel free to change team membership or reorganize teams as needed during the hack day.

## Code organization

Coding for tracks **1** will be done in branches of the [`archesproject/docker_dev`](https://github.com/archesproject/arches/tree/docker_dev) repo (`koop_prototype` and `arcgis_pro_prototype` respectively).

All team members will code in the same branch.

<!-- Instead of cloning the `fargeo/arches` fork, it is probably much easier to just [change remote](#preparation) on your existing local arches repo. -->

<!-- After the trip, you can change your Arches repo's remote back with the following command: -->
<!-- ```
git remote set-url origin https://github.com:archesproject/arches.git -->
<!-- ``` -->

## Preparation

Please do the following before arriving:

- re-read this page (it's being updated daily)

- switch your repo to be on the docker_dev branch [`archesproject/docker_dev`](https://github.com/archesproject/arches/tree/docker_dev) and checkout the `salinas` branch by running the following:
```
git pull
git checkout docker_dev
```

-Follow the instructions below

1. In the docker-compose.yml change image setting under the Arches service from getty/arches:5.0  to your_name/arches:5.0
2. In a terminal cd to to your core arches directory and run `docker-compose build`
3. Once that’s done run `docker-compose up`
4. Go to localhost:8000 and you should see Arches.



## Food
Anything you can find in your fridge.
