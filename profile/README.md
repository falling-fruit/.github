### How to get involved

We are looking for help with **design** and **software development**, but there are many other ways to contribute (**translate**, wrangle **data**, **recruit** others, write **newsletter** content). Ideas to get started:

  - Open an issue, weigh in on issues, or contribute a pull request in one of our GitHub [repositories](https://github.com/orgs/falling-fruit/repositories) or [projects](https://github.com/orgs/falling-fruit/projects)
  - Join our [Slack workspace](https://join.slack.com/t/fallingfruit/shared_invite/zt-1oh1paonq-XJ7dBHPapv6uuBTc93~4UA)
  - Share your thoughts in the GitHub [Discussions](https://github.com/orgs/falling-fruit/discussions)
  - Email info@fallingfruit.org


### Development roadmap

We use a PostgreSQL database on a self-managed Amazon EC2 Ubuntu server, which also serves all our APIs and web interfaces. Our widely-used website and mobile app are built on aging frameworks and are now inactively maintained:

  - [falling-fruit](https://github.com/falling-fruit/falling-fruit) – Our website ([fallingfruit.org](https://fallingfruit.org)), built as a Rails 3 (Ruby 2.3.4) web application, admin dashboard, and database migrations.

  - [falling-fruit-mobile](https://github.com/falling-fruit/falling-fruit-mobile) – Our mobile app ([Google Play](https://play.google.com/store/apps/details?id=uh.fallingfruit.app) · [App Store](https://apps.apple.com/us/app/falling-fruit/id380859409)), built with Cordova, Angular v1, and the Rails API.

Instead, a new API and mobile-friendly website are being developed as eventual replacements:

  - [falling-fruit-api](https://github.com/falling-fruit/falling-fruit-api) – Public REST API (https://fallingfruit.org/api/0.3 · [documentation](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/falling-fruit/falling-fruit-api/main/docs/openapi.yml)) built with NodeJS and Express.

  - [falling-fruit-web](https://github.com/falling-fruit/falling-fruit-web) – Web app ([beta.fallingfruit.org](https://beta.fallingfruit.org)) built with ReactJS and the new API. It introduces long-awaited features (multiple photos per review, multi-type location filtering, link from list to map in mobile view) but still lacks some existing features.


### On the horizon

There are several major features that we've wanted to develop for a long time but have not found the time to finish.

  - Seasonality filter (described [here](https://docs.google.com/document/d/1ah6jKO9uizBqeBtTVoIXi51gpYEQEyYzzastcMKOp5Y/edit#heading=h.1hnrl61rsxes))
    - *Summer 2023*: Exploratory efforts to build predictive fruit ripeness models from historic climate data and phenology observations are underway at [dfg-seasons](https://github.com/falling-fruit/dfg-seasons).
  - Tree inventories – We've identified hundreds more open tree inventories to add to our map! If only we had the time to deal with all that data...
    - *Summer 2023*: Improvements are being made to our data archiving and processing pipeline at [dfg-trees](https://github.com/falling-fruit/dfg-trees).
  - Interactive location types (described [here](https://docs.google.com/document/d/1ah6jKO9uizBqeBtTVoIXi51gpYEQEyYzzastcMKOp5Y/edit#heading=h.cbt21puyoh05))
  - Protected lands / foraging regulations map layer (described [here](https://docs.google.com/document/d/1ah6jKO9uizBqeBtTVoIXi51gpYEQEyYzzastcMKOp5Y/edit#heading=h.ubvuwkfv2v84)) – This is a frequent request from land agencies and a political must in the long term.
  
