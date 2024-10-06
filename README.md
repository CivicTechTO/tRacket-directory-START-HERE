## Welcome!

tRacket is a volunteer-led project for aimed at making it easy and affordable to collect data about noise. 

## How to help

If you're interesting in contributing to the project, you should start out by joining our project Slack channel, `#proj-noisemeter`, in the [Civic Tech Toronto Slack](https://civictechto.slack.com/). [Link to join](https://link.civictech.ca/join).

We have several project streams you can contribute to, each with its dedicated GitHub repository. You can browse the links below to find something interesting to you.

### Repositories

- [Strategy & Design]: our design system, policies, governance, communication, research, and other related documentations.
- [Sensor](https://github.com/CivicTechTO/proj-noisemeter-device): the hardware we designed to make the noise measurements and send them over wifi.
- Dashboard:
  - [Dashboard - Current](https://github.com/CivicTechTO/tRacket-dashboard): the dashboard that is currently available to inspect our database of noise measurements. We are only working on maintenance.
  - [Dashboard - New]: we are actively developing a new React version of the dashboard.
- [Sensor Manager](https://github.com/CivicTechTO/tRacket-sensor-manager): the interface for sensor owners to register and then manage their device.
- [API](https://github.com/CivicTechTO/tRacket-api): this is the software layer that helps the database receive noise measurements and the dashboard to read the database.

## Architecture

You can view below how the components interact in our framework:

<img src="https://tracket.info/wp-content/uploads/2024/07/tracket-architecture.png" width="500"/>

