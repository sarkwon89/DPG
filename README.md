# DPG developer profile generator

# What is it?
Created a command-line application that dynamically generates a PDF profile from a GitHub username. The application will be invoked with the following command:

```sh
node index.js
```
# How it works
The user will be prompted for a favorite color, which will be used as the background color for cards.

The PDF will be populate the following:

* Profile image
* User name
* Links to the following:
  * User location via Google Maps
  * User GitHub profile
  * User blog or portfolio
* User bio
* Number of public repositories
* Number of followers
* Number of GitHub stars
* Number of users following
* User Company

Following the [common templates for user stories](https://en.wikipedia.org/wiki/User_story#Common_templates), we can frame this challenge as follows:

```
AS A product manager

I WANT a developer profile generator

SO THAT I can easily prepare reports for stakeholders
```

Refer to the [design mockup](./Assets/09-NodeJS-homework-demo.pdf).

## Business Context

When preparing a report for stakeholders, it is important to have up-to-date information about members of the development team. Rather than navigating to each team member's GitHub profile, a command-line application will allow for quick and easy generation of profiles in PDF format.
- - -
