# GitHub for Developers Provisioner Repo
This repository can be used to generate repositories for students attending a GitHub for Developers training. 

## Prerequisites:
1. Create a personal access token with the following scopes: ```repo``` and ```delete repo```
1. Add the PAT as an actions secret with the name ORG_PAT.

## Steps:
1. Create an issue and list the usernames in the issue body, separated by line breaks or carriage returns. 
1. Workflow will run and create public repos for the specified users, commit the starting files, and invite the users as admins on their repos.
1. When class is over and we are ready to clean up the repos, simply close the issue. 
1. Workflow will run and delete the repos for the users on the closed issue. 

## Notes:
Repos will be created in the same org that the workflow executes in.  

![](http://i.imgur.com/NcsRW1q.png)

**[PLAY IT HERE (http://ncase.me/polygons)](http://ncase.me/polygons)**

---

This playable post is [public domain (CC0)](http://creativecommons.org/publicdomain/zero/1.0).

This repository is also being used as a part of GitHub training, to practice Git and GitHub.

Please feel free to use this in your classrooms,
make video/picture/text adaptations,
or modify the source code!
Attribution is not mandatory, but super appreciated.
We are [Vi Hart](http://vihart.com/) and [Nicky Case](http://ncase.me/).

Show us how you're using and remixing Parable of the Polygons!    
Tweet us at
[@vihartvihart](https://twitter.com/vihartvihart) and
[@ncasenmare](https://twitter.com/ncasenmare).
