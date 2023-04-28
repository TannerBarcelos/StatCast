# StatCast

> Note that this application is under development. This README is proposing a lot more than what is currently completed.
> A checklist of tasks will be added here soon to outline work being done

#### About the Project

Sports statistics are often hard to get a hand on. You can get them on official league websites but they are often limited and hard to grasp. Likewise, you can use 3rd party services but they are often outdated and also bloated with ads and unecessary data.

StatCast aims to solve these issues by providing an end-to-end, simple to use web interface for getting the data you want easily. The platform aims to provide immersive data visualizations and experiences that are accessible and usable.

These experiences are powered by an advanced web scraping data ingestion pipeline to power the underlying applications data layer that the applications backend uses to provide the UI with up-to-date sports data.

#### Application Tech Stack

| Technology | Purpose                                            |
| ---------- | -------------------------------------------------- |
| NextJS     | Web Client                                         |
| NodeJS     | REST APIs                                          |
| MongoDB    | Managing users and application related data        |
| Python     | Web Scrapers (scheduled by Airflow)                |
| Spark      | ETL jobs written with Scala (scheduled by Airflow) |
| MySQL      | Final Persistence Layer                            |

#### Application E2E Flow

#### Architecture

---

#### Application Motivation

My background is in Full Stack Web Engineering but am becoming more immersed in Big Data in my current role. Because of this, I want to learn big data, data ETL pipelines and more by applying it on a project I know I can build as a web platform. My passion for sports has driven the idea for developing such an application as well. I find official league websites or sports stat sites are unusable. I figured this idea would be a perfect opportunity to offer sports fans alike the ability to see data in a whole new way, but also push my abilities in learning more about Big Data.
