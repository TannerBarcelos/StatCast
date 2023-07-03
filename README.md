# statr

#### About the Project

Sports statistics are often hard to get a hand on. You can get them on official league websites but they are often limited and hard to grasp. Likewise, you can use 3rd party services but they are often outdated and also bloated with ads and unecessary data.

statr aims to solve these issues by providing an end-to-end, simple to use web interface for getting the data you want easily. The platform aims to provide immersive data visualizations and experiences that are accessible and usable.

These experiences are powered by an advanced web scraping data ingestion pipeline to power the underlying applications data layer that the applications backend uses to provide the UI with up-to-date sports data as well as historical analytics.

#### Application Tech Stack

| Technology | Purpose                                                                                                                                   |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| React      | **Typescript** Web UI for Data Visualization using D3 and ChartJS                                                                         |
| FastAPI    | **Python** REST API                                                                                                                       |
| Python     | Web Scraper Jobs (Daily Statistics and Historical Statistics _1 time run_)                                                                |
| Spark      | **PySpark** ETL pipeline to process S3 files and send off to Postgres to be the REST API data source                                      |
| MongoDB    | User and application data management                                                                                                      |
| Airflow    | Job Scheduler for web scrapers and ETL jobs                                                                                               |
| Docker     | Containerization of application and services                                                                                              |
| AWS ECS    | Container orchestration for application and services                                                                                      |
| AWS S3     | Staging datalake for the raw CSV files from scraper jobs. Data serves as source for ETL jobs that will enrich, clean and process the data |
| AWS RDS    | Postgres RDBMS for storing processed data from ETL jobs and serving as REST API data source                                               |

> Kubernetes is also being considered as an alternative to AWS ECS but is not currently being used as this project is still in the early stages of development and not expected to scale to a point where Kubernetes is necessary.

#### Architecture

> This is a detailed Architecture diagram of the proposed application. This is not a current representation of the application as it is still in development.

[wip]

#### Getting Started

#### Status

---

> This application is under **planning phase** and therefore is more of a proposal.
