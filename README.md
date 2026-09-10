# Historical @realDonaldTrump Posting Activity Analysis

> **Master’s Psychology Research & Analytics Portfolio**
>
> This project was completed as part of my Master’s degree program in Psychology. It uses R to analyze historical social-media posting patterns, hashtag use, and activity timing from the @realDonaldTrump account.
>
> [View the complete Master’s Psychology Research & Analytics Portfolio](https://github.com/users/rickhegenbart/projects/1)

## Overview

This R Markdown project examines historical posting activity from the @realDonaldTrump account.

The analysis focuses on descriptive patterns: frequently used hashtags, posts per day, average daily posting activity, posting times, weekday patterns, and combined day-and-hour activity.

This is a nonpartisan academic analysis of public social-media activity. It does not evaluate political positions, campaign messages, policy claims, or the accuracy of post content.

## Analysis Questions

* Which hashtags appeared most often in the collected posts?
* How many posts occurred each day?
* What was the average number of posts per day?
* At what hours of the day did posting activity peak?
* How did activity vary by day of the week?
* What combined weekday-and-hour patterns were visible?

## Methods

The analysis:

* Retrieves historical timeline data through the X/Twitter API.
* Extracts and counts hashtags.
* Calculates daily posting volume and average posts per day.
* Converts timestamps to U.S. Eastern Time.
* Analyzes hourly and weekday posting patterns.
* Creates interactive tables, histograms, and a two-dimensional activity heat map.

## Tools

* R
* R Markdown
* `tidyverse`
* `rtweet`
* `DT`
* `plotly`
* `lubridate`

## Data and Security

The analysis retrieves public social-media data through the X/Twitter API.

API credentials are not included in this repository. Configure approved credentials locally through environment variables, and never commit API keys, tokens, `.Renviron` files, or data that cannot be redistributed.

Platform access, API requirements, and available historical data may change over time.

## Repository Contents

```text
├── README.md
└── rtweet_trump(20260910-202952).Rmd
```

## Reproducing the Analysis

Install the required R packages:

```r
install.packages(c("tidyverse", "DT", "plotly", "rtweet", "lubridate"))
```

Configure valid API credentials locally, then render the R Markdown file with active internet access.

## Project Status

This repository preserves the original social-media-analysis source code. A reproducible HTML report can be added after the data-retrieval workflow is updated and tested.
