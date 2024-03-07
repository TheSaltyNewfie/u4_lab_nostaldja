# Nostaldja Lab

![Nostalgia](https://www.zocalopublicsquare.org/wp-content/uploads/2022/02/nostalgia-L.jpg)

## Overview

In this lab, we'll build an app called Nostaldja, an app for tracking fads across decades.

## Instructions


1. Set up your virtual environment and activate it.
1. Install dependencies.
1. Follow the Django set up instructions!
1. Fulfill the listed requirements.



## Setup

Read through the setup instructions from our previous labs

The goal of this app is to have a full-CRUD application with a functioning Admin panel

In your SQL file, create a Database called "Nostaldja", with a user of "NostaldjaUser", and make sure to grant them all permissions

## Requirements

 You'll need to create a new psql database for your app.

### Models

Create two models: `Decade` and `Fad`.

A `Decade` will have `Fad`s, or in other words a fad will have a foreign key for
a decade.

Each Decade should have many Fads (One to Many relationship)

- Decades
  - name ('eighties', 'nineties'...)
  - start_year
  - end_year
- Fads
  - name
  - image_url
  - description
  - decade

### Bonus 

We are coming to terms with the fact that some of our students were born in the 21st century (my knee hurts). Which means some of you may not know these older fads, and may want to add in some more modern ones

- Add in more decades (00's, Tens, Twenties...) and any respective fads from each (Memes, planking, tik tok, whatever else the kids are doing these days)
- But wait! It'd be terrible UX to have the 80's, 90's and 00's all set together, what if we wanted to do the 1920's, or the 2080's? Create a 3rd model called Century and relate your decades into this new model

