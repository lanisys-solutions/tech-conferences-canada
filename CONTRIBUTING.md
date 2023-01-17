# Contribute to this repository

## How to choose the event 🧐

This repo is a community-curated list of Canadian tech conferences. So, before adding a new event, please:

- make sure it is a tech conference and it is not already listed.

- make sure that is a conference (not a meetup, hackathon, etc.)

- make sure that the event is happening in Canada (either in English, French or in a foreign language).

## Prepare the contribution ✍️

Fork this project to your GitHub account and create the file inside the `_conferences/` directory.

The file should be named the conference name and year with an `.md` extension (for example, `lanisys-conf-2023.md`).

## File format 📄

The contents of the file should use the following template:

`name`*: the name of the conference, avoid adding the location of the event in the name, the location will be displayed next to the name of the conference.

`website`*: the website of the conference, avoid linking to signup pages (Eventbrite, Meetup, etc...) instead try to find the official event website, to allow users to find more information about the event.

`location`*: the location of the conference (`<city>, <province>, <country>`, `Virtual` or both)

`status`: if the conference is canceled or postponed (`Canceled` or `Postponed`)

`online`: if the conference is online (`true` or `false`)

`lang`*: the language of the conference (`English`, `Français` or `English & Français`)

`date_start`*: the start date of the conference (`YYYY-MM-DD`)

`date_end`*: the end date of the conference (`YYYY-MM-DD`)

Call For Papers (CFP)

`cfp`: the conference is calling for papers (`cfp`)

`start`**: the start date of the call for papers (`YYYY-MM-DD`)

`end`**: the end date of the call for papers (`YYYY-MM-DD`)

`site`: the website of the call for papers (`https://lanisys.ca/contact/`)

Variables marked with a `*` are required. Variables marked with a `**` are required for CFP. 

Example:

```markdown
---
name: "LaniSys Conf"
website: https://lanisys.ca/
location: Montréal, QC, Canada
online: true
lang: English & Français

date_start: 2023-04-01
date_end:   2023-04-01

cfp:
 start: 2022-04-01
 end:   2022-04-01
 site:  https://lanisys.ca/contact/
---
```

## Create a pull request 📌

Before push, please verify that the file is correctly formatted ([try to run the project](/README.md#running-locally) on your local machine).

There is no convention for the commit message, but it is recommended to use the following format: `"Add <conference name> <year>"`.

Then commit the changes, push the code and create a pull request.
