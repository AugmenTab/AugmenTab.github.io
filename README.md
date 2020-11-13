## Introduction

I am attending the Deep Dive Coding Java + Android Bootcamp with the goal of changing my career. I plan to pursue work in software development after graduation. 

## Current Projects

* [Viral: Android game](https://github.com/AugmenTab/viral)

* AlbuQuirky: Android app

* [CodeBreaker: Android game](https://github.com/AugmenTab/codebreaker-android)

* [Animals: Android app](https://github.com/AugmenTab/animals)

## Recently Updated Repositories

{% assign public_repositories = site.github.public_repositories | where: 'fork', false | sort: 'updated_at' | reverse %}
{% for repo in public_repositories limit: 10 %}
* [{{ repo.name }}]({{ repo.html_url }})
{% endfor %}

## Links

* [LinkedIn](https://www.linkedin.com/in/thebaum)