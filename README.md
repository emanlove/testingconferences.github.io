# Testing Conferences [![CircleCI](https://circleci.com/gh/TestingConferences/testingconferences.github.io.svg?style=svg)](https://circleci.com/gh/TestingConferences/testingconferences.github.io) [![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT) 

This is a simple list of software testing conferences and workshops published collaboratively with the testing community.

## Quick Start
1. Clone or download the project and cd project dir
> git clone git@github.com:TestingConferences/testingconferences.github.io.git
> cd testingconferences.github.io

2. Run using [Docker](https://docs.docker.com/get-docker/)

Build the image: 

> docker build -t tcorg:latest .

Run the container: 

> docker run -d -p 4000:4000 -it --volume="$PWD:/srv/jekyll" tcorg:latest

An alternate option is to use docker-compose:

> docker-compose up

3. Browse to http://localhost:4000 to see the site

## Contributing Guidelines
The list of events is driven by files in the ```_data``` folder - if you have an update for those things, just change the ```current.yml``` and ```past.yml``` files and send a PR.
  - The _order_ of the events listed in ```current.yml``` and ```past.yml``` dictates the _order_ displayed, please make sure to properly insert events.
  - If possible, spell out the conference name and add the abbreviation. Otherwise just use the abbreviation:
    - Example: Workshop on Performance and Reliability (WOPR)
  - Include the year
    - Sometimes workshops use a version instead of a year
      - Example: Workshop on Performance and Reliability (WOPR) 24
  - Don't include the @ symbol for the twitter handle. If there is no twitter option, leave it blank
  - Optionally include a status such as:
    - CFP is open / closed (CFP == Call for Proposal)
    - CFP is closed
    - Early Bird Registration is open
    - Registration is open / closed
    - Feel free to put in dates about when things expire
  - Optionally include a link to a conference video playlist. This will only appear for past conferences and can be added directly to the ```past.yml``` file.
    - These should be videos from the conference presentations or talks. No marketing videos please.  

## Eligible Conferences and Workshops

Focus is a goal of this project and as a result, only conferences, un-conferences and workshops that are specifically for software testing are listed. That means that if a conference covers software testing, but is not specifically for testers, then it is left out.

A good _heuristic_ for whether a conference should be included is if its name includes Test(ing) or Quality and/or how it describes itself.

## Mailing List

Don't forget to **[sign up](http://eepurl.com/c4paYT)** for our once **monthly newsletter.**


## License

TC.org is released under the [MIT License](MIT-LICENSE).

[![Testing Powered By SauceLabs](https://opensource.saucelabs.com/images/opensauce/powered-by-saucelabs-badge-white.png?sanitize=true "Testing Powered By SauceLabs")](https://saucelabs.com)