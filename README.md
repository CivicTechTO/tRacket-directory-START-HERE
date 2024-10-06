# Welcome to tRacket!

## Mission

Our mission is to make it easy and affordable to monitor noise, to empower advocates and government agencies to understand and reduce harmful noise within their communities.

## Our Vision

- We created a low-cost, easy to setup sensor that is available to monitor noise levels 24 hours a day.
- Dozens (and maybe someday, hundreds) of these sensors are deployed across cities mapping the noise landscape.
- Residents better understand the stress put on them by environmental noise and differences in living conditions throughout the city.
- Advocates use detailed data on noise to argue for new policies and regulations.
- Our communities become more livable thanks to the reduction of unnecessary, harmful noise.

## Goals

To accomplish our vision, we will:
- Design and make available affordable noise monitoring hardware that is easy to acquire, set up, monitor and share noise levels at specific locations long-term.
- Build a platform to support device owners through the configuration and support of their hardware, long-term storage of their measurements, access to their measurements as open data, and tools to visualize, annotate, analyze and share noise measurements, as well as aggregated measurements and “stories” through annotations and online community.
- Build a platform to support advocates through access to noise measurements within their communities, including location-based noise levels, analysis and commentary.
- Build privacy controls into the sensors and platform to assure users that measurements in their homes and communities cannot be used for malicious purposes.
- Build a team and platform that is self-sustained through initial volunteers, sensor sales, donations and/or other means.
- Promote and grow tRacket to increase use and impact.


## How to help?

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

