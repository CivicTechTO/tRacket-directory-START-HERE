# Welcome to tRacket!

tRacket is a volunteer-led project for aimed at making it easy and affordable to collect data about noise. 

## Mission & Vision

TBC

## How to help

If you're interesting in contributing to the project, you should start out by joining our project Slack channel, `#proj-noisemeter`, in the [Civic Tech Toronto Slack](https://civictechto.slack.com/). [Link to join](https://link.civictech.ca/join).

You can look at our [Strategy & Design](https://github.com/CivicTechTO/tRacket-strategy-design) repo to see our roadmap and where we are aiming our project to go next. There are some big new pieces we need help with currently:
- **Online ordering**: 
  - Creating an interface for people to place an order for a sensor, and to be able to track the status of their order. 
  - For now, we will charge $0 for the sensors, but we may offer accessories (cables, power supplies) and shipping for a fee. 
- **Order fulfillment**: 
  - Tools and processes for volunteers to fill orders.
- **Promotion and content design**: 
  - Promoting the availability of sensors, through partnerships, earned media, our website and mailing list.
- **Legal**:
  - Creating a Terms of Use, reviewing/updating our Privacy Policy, advising on risks.

We have several project streams you can contribute to, each with its dedicated GitHub repository and tasks detailing items we are looking to do next. You can browse the links below to find something interesting to you.

### Repositories

- [Strategy & Design](https://github.com/CivicTechTO/tRacket-strategy-design): our design system, policies, project management, governance, communication, research, and other related documentations.
- [Sensor](https://github.com/CivicTechTO/proj-noisemeter-device): the hardware we designed to make the noise measurements and send them over wifi.
- Dashboard:
  - [Dashboard - Current](https://github.com/CivicTechTO/tRacket-dashboard): the dashboard that is currently available to inspect our database of noise measurements. We are only working on maintenance.
  - [Dashboard - New](https://github.com/CivicTechTO/tRacket-dashboard-react): we are actively developing a new React version of the dashboard.
- [Sensor Manager](https://github.com/CivicTechTO/tRacket-sensor-manager): the interface for sensor owners to register and then manage their device.
- [API](https://github.com/CivicTechTO/tRacket-api): this is the software layer that helps the database receive noise measurements and the dashboard to read the database.

## Architecture

You can view below how the components interact in our framework:

<img src="https://tracket.info/wp-content/uploads/2024/07/tracket-architecture.png" width="500"/>

