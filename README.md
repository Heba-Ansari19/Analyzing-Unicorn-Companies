# Analyzing-Unicorn-Companies
This project analyzes unicorn companies to help an investment firm identify the top-performing industries from 2019–2021. Using SQL (PostgreSQL), we explore industry growth, average valuations, and the emergence rate of high-value startups, providing insights that guide portfolio structuring and strategic investment decisions.
<br>
<br>
## PROJECT OVERVIEW

Unicorn companies are private startups valued at over $1 billion, and tracking their growth can reveal where the next wave of innovation and opportunity lies. In this project, we were tasked with supporting an investment firm by analyzing unicorn data across industries and years. The firm wanted to understand which industries are producing the most unicorns and how their valuations have evolved between 2019 and 2021.

By working with a structured unicorn database, the analysis focused on three critical areas: identifying the most promising industries, understanding how many new unicorns each industry produced during the selected years, and evaluating their average valuations in billions of dollars. These insights provide competitive intelligence for the firm, helping it recognize where to direct its future investment portfolio.
<br>
<br>
## OBJECTIVE / KEY QUESTIONS

* Which three industries produced the highest number of unicorns in 2019, 2020, and 2021 combined?
* How many unicorns did these industries generate each year?
* What was the average valuation (in billions, rounded to two decimals) of unicorns in these industries per year?
<br>

## DATASET

* Source: Unicorn Companies Database
* Tables:
    * `dates` – records when each company became a unicorn and its founding year.
      | Column        | Description                                 |
      | ------------- | ------------------------------------------- |
      | company\_id   | A unique ID for the company.                |
      | date\_joined  | The date that the company became a unicorn. |
      | year\_founded | The year that the company was founded.      |

    * `funding` – contains company valuations and total funding raised.
      | Column            | Description                                 |
      | ----------------- | ------------------------------------------- |
      | company\_id       | A unique ID for the company.                |
      | valuation         | Company value in US dollars.                |
      | funding           | The amount of funding raised in US dollars. |
      | select\_investors | A list of key investors in the company.     |

    * `industries` – shows the industry each company operates in.
      | Column      | Description                                |
      | ----------- | ------------------------------------------ |
      | company\_id | A unique ID for the company.               |
      | industry    | The industry that the company operates in. |

    * `companies` – provides details on the company name, location (city, country, continent).
      | Column      | Description                                       |
      | ----------- | ------------------------------------------------- |
      | company\_id | A unique ID for the company.                      |
      | company     | The name of the company.                          |
      | city        | The city where the company is headquartered.      |
      | country     | The country where the company is headquartered.   |
      | continent   | The continent where the company is headquartered. |

## TOOLS AND SKILLS USED

* SQL (PostgreSQL)
* Concepts: CTEs (Common Table Expressions), Joins, Aggregations, Grouping, Filtering with WHERE and EXTRACT, Ordering, Subqueries.
* Techniques Used: Data exploration, industry benchmarking, trend analysis, valuation averaging, filtering by year, summarizing performance.









































