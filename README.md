# statr

> Note that this application is under development and planning. This README is proposing a lot more than what is currently complete and is more of an outline.
> A checklist of tasks will be added here soon to outline work being done

#### About the Project

Sports statistics are often hard to get a hand on. You can get them on official league websites but they are often limited and hard to grasp. Likewise, you can use 3rd party services but they are often outdated and also bloated with ads and unecessary data.

statr aims to solve these issues by providing an end-to-end, simple to use web interface for getting the data you want easily. The platform aims to provide immersive data visualizations and experiences that are accessible and usable.

These experiences are powered by an advanced web scraping data ingestion pipeline to power the underlying applications data layer that the applications backend uses to provide the UI with up-to-date sports data as well as historical analytics.

#### Application Tech Stack

| Technology | Purpose                                                                   |
| ---------- | ------------------------------------------------------------------------- |
| React     | **Typescript** Web UI for Data Visualization using D3                                                 |
| FastAPI    | **Python** Backend Web Services                                           |
| MongoDB    | Managing users and web application related data                           |
| PostgreSQL | Final Persistence Layer for scraped data                               |
| Python     | Web Scrapers (Daily Stats and Historical Stats)                           |
| Spark      | ETL jobs written with **Scala**                                           |
| Airflow    | Job Scheduler                                                             |
| GCS        | Store raw CSV files from scraper jobs. Data serves as source for ETL jobs |

#### Application E2E Flow

#### Architecture
