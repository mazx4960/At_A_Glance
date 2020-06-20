# Project <i>At A Glance</i>

<p align="center">
 <a href="#"><img src="https://img.shields.io/badge/buy%20me%20a-coffee-yellow.svg"></a>
 <img src="https://img.shields.io/badge/last%20updated-June%202020-3d62d1">
 <img src="https://img.shields.io/github/downloads/mazx4960/At-A-Glance/total">
</p>

## About project <i>At A Glance</i>

A Web based application that seeks to improve or automate routine things that people do everyday, like checking the headline news, checking the weather, or finding the route to their location, having a to do list etc. Basically aggregating every site that you commonly use in a single platform. Allows for customisation through plugin support, allowing you to choose what you want to display on your dashboard.

This website would be created using Django, a python web framework. This would be expanded in the future to mobile based application like android or iOS.

Currently, some of the APIs that would be used includes google news API (for news articles), a good weather forecast API (for weather), google maps API (for determining the route to take to the location or the time taken the person would need to travel there), LTA API (for determining the time the next train or bus would arrive so as to alert the person to leave house).

## Features

[ ] A Clean dashboard that displays important information at a glance
    [ ] Tiles/cards support to segregate different kinds of information
    [ ] Resizing of tiles/cards
[ ] Themes support to choose how you want the dashboard to look
[ ] Plugin support to allow 
[ ] Dockerising the application

Installing
----------

Installing required packages using `pip`:

    pip install -r requirements.txt

Or, running in virtualenv:

    source env/bin/activate

Running the website:

    python manage.py runserver
