# The oldest business in the world

An important part of business is planning for the future and ensuring that the company survives changing market conditions. Some businesses do this really well and last for hundreds of years.

BusinessFinancing.co.uk [researched](https://businessfinancing.co.uk/the-oldest-company-in-almost-every-country) the oldest company that is still in business in (almost) every country and compiled the results into a dataset. In this project, you'll explore that dataset to see what they found.

## The database contains three tables.

### `categories`

| column          | type    | meaning                                |
| --------------- | ------- | -------------------------------------- |
| `category_code` | varchar | Code for the category of the business. |
| `category`      | varchar | Description of the business category.  |

### `countries`

| column         | type    | meaning                                           |
| -------------- | ------- | ------------------------------------------------- |
| `country_code` | varchar | ISO 3166-1 3-letter country code.                 |
| `country`      | varchar | Name of the country.                              |
| `continent`    | varchar | Name of the continent that the country exists in. |

### `businesses`

| column          | type    | meaning                                |
| --------------- | ------- | -------------------------------------- |
| `business`      | varchar | Name of the business.                  |
| `year_founded`  | int     | Year the business was founded.         |
| `category_code` | varchar | Code for the category of the business. |
| `country_code`  | char    | ISO 3166-1 3-letter country code.      |

**By analyzing this dataset, I found answers to the following questions:**

1. What are the founding years of the oldest and newest businesses?
1. How many businesses were established before the year 1000?
1. Which businesses were established before the year 1000?
1. What industries do these businesses belong to?
1. How many industries are represented in the dataset?
1. How many businesses fall under each category?
1. Which industry has the highest number of companies?
1. What is the founding year of the oldest business on each continent?
1. How many businesses in each continent belong to each industry? …etc
