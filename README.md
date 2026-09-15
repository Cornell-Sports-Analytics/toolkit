# Sports Analytics Toolkit

A curated collection of resources for sports data analytics projects.

## Data Acquisition Methods

There are three primary methods for acquiring sports data.

### 1. Datasets & Websites
Many sports websites have data that has already been collected and cleaned for you. This allows you to download the data as a CSV and start working on a project. A great place to start looking for data is on Kaggle, which contains many datasets that you can easily download. This is the fastest way to start a project as it requires little to no setup and knowledge of a programming language. 

### 2. Packages/Libraries (Python & R)
Packages/libraries allows you to import and call sports data directly into your script. Under the hood, most of these either call a well-documented API (like nflfastR pulling from NFL.com) or scrape a site's data and package it into a clean, ready-to-analyze format. Packages and libraries are useful because they are often quicker and more reliable than downloading a CSV.

### 3. Web Scraping
Pulling data straight from a webpage when there's no dataset or library for it. This is the most flexible option since it can get you almost anything visible on a site. Make sure to always respect a site's robots.txt and terms of service when web scraping.

To get started with web scraping, it is recommended starting with the Instant Web Scraper Chrome extension. This lets you point-and-click on the data you want on a webpage and export it directly to a CSV. It's a good entry point but for anything recurring or more complex, a coded scraper will give you more control.

---

## Datasets & Websites

Sorted by sport.

| Sport | Title | Description |
|---|---|---|
| Multi-sport | Kaggle | Hosts a massive collection of free, public datasets across thousands of topics. |
| NFL | [Pro Football Reference](https://www.pro-football-reference.com/) | Historical NFL data since 1967 — player statistics, all-time leaders, draft history, coaches. Updated weekly; some data paywalled. |
| NFL | NFLSavant | CSV play-by-play data from 2013–2024, segmented by team, play, down, formation, and play type. |
| NFL | NFL Play | CSV data covering the NFL combine, draft, and a range of performance metrics. |
| College Football | Sports-Reference College Football | Historical CFB data since 1956 — statistics, Heisman winners, all-time leaders, bowl history. |
| College Football | College Football Data | Play-by-play data, drive results, historical ratings, and predictive metrics (EPA, WPA) via API. |
| MLB | [Baseball Reference](https://www.baseball-reference.com/) | Historical MLB data since 1871 — players, teams, statistics, all-time leaders. Filterable by player/team; some data paywalled. |
| MLB | [Baseball Savant](https://baseballsavant.mlb.com/) | Statcast-based advanced metrics (xwOBA, barrel%, etc.), with built-in CSV export and visualization tools. |
| MLB | [Fangraphs](https://www.fangraphs.com/) | Standings, projections, scores, and advanced player metrics (AVG, K%, wOBA). |
| MLB | Retrosheet | Event-level historical data — postponed games, ejections, protested games, no-hitters. |
| NBA | [Basketball Reference](https://www.basketball-reference.com/) | Historical NBA and WNBA data since 1946 — statistics, leaders, teams, draft history. Some data paywalled. |
| NBA | NBA Play-by-Play | Detailed play-by-play data sets covering 2000–2020, useful for shot/score trend analysis. |
| NBA | WeHoop | Play-by-play data for the WNBA and women's college basketball. |
| College Basketball | Sports-Reference CBB | Historical college basketball data since 1892 — scores, leaders, tournament history, awards. |
| Soccer | [FBref](https://fbref.com/) | Historical soccer data going back to the 1800s across major global leagues — statistics, standings, all-time leaders. |
| Soccer | Statsbomb Open Data | Public subsets of Statsbomb's advanced event data (e.g., Euro 2025, Messi data) via GitHub. |
| Soccer | Metrica Sports | Tracking and event data with an accompanying glossary; available per-game or per-team. |
| NHL | [Hockey Reference](https://www.hockey-reference.com/) | Historical NHL data since 1917 — players, statistics, records, awards. Some data paywalled. |
| NHL | Money Puck | Playoff odds, team, and player data from 2008–2023, delivered as CSV. |
| NHL | Stat Trick | Live and in-depth NHL game data — scores, shots, expected goals, high-danger chances. |
| Tennis | ATP Matches | CSV match data (tournament, seeds, winner, rank, serve stats) from 2000–2017. |
| Tennis | WTA Matches | CSV match data (tournament, surface, winner) from 2000–2016. |
| Motorsports | F1 Race Data | CSV data on circuits, drivers, races, and results, including pit stop times. |
| Motorsports | F1 World Championships | CSV data on the F1 World Championship since 1950 — drivers, lap times, results. |
| MMA | UFC Data | UFC fight data from 1993–2021 with 144 variables (date, weight class, fighters, referee). |
| MMA | UFC Refactored | Advanced UFC fight dataset with 400+ variables. |
| Golf | PGA Tour Data | Golf statistics — fairway percentage, average score, wins. |
| Golf | PGA Tour Rankings | Rankings data, including events played and points gained/lost. |
| Track & Field | [World Athletics](https://worldathletics.org/) | Professional meet results (Diamond League, national meets), toplists, records, and rankings. |
| Track & Field | [TFRRS](https://www.tfrrs.org/) | Collegiate track & field and cross country data since 2009, covering D1–D3, NAIA, NJCAA, and NCCAA. |
| Cricket | Indian Premier League | CSV data on IPL matches, players, seasons, and teams from 2008 onward. |

---

## Libraries

Sorted by sport.

| Sport | Title | Description | Language |
|---|---|---|---|
| NFL | [nflfastR](https://opensource.pysport.org/project/nflfastR) | Core `nflverse` package for accessing NFL play-by-play data since 1999, with EPA/WPA and other advanced metrics built in. | R |
| NFL | [nfl_data_py](https://opensource.pysport.org/project/nfl_data_py) | Python interface to `nflfastR`-sourced NFL data, mirroring the R ecosystem for Python users. | Python |
| College Football | [cfbscrapR](https://opensource.pysport.org/project/cfbscrapR) | R wrapper around the College Football Data API, adding EPA/WPA to play-by-play data. | R |
| College Football | [CFBScrapy](https://opensource.pysport.org/project/CFBScrapy) | Python wrapper for the College Football Data API. | Python |
| MLB | [pybaseball](https://opensource.pysport.org/project/pybaseball) | Retrieves Statcast, Baseball Reference, and FanGraphs data directly in Python. | Python |
| MLB | [baseballr](https://opensource.pysport.org/project/baseballr) | Utilities for acquiring and analyzing baseball data from Baseball Reference, FanGraphs, and the MLB Stats API. | R |
| NBA | [hoopR](https://opensource.pysport.org/project/hoopR) | Play-by-play and box score access for men's college and NBA basketball, wrapping the NBA Stats API and ESPN. | R |
| NBA | [py_ball](https://opensource.pysport.org/project/py_ball) | Python API wrapper for stats.nba.com, focused on NBA and WNBA data. | Python |
| NHL | [fastRhockey](https://opensource.pysport.org/project/fastRhockey) | Scrapes and loads play-by-play data and statistics for the NHL and PWHL. | R |
| Soccer | [kloppy](https://opensource.pysport.org/project/kloppy) | Standardizes soccer tracking and event data across providers into a common format. | Python |
| Soccer | [worldfootballR](https://opensource.pysport.org/project/worldfootballR) | Retrieves tidy soccer data from FBref, Transfermarkt, and Understat. | R |
| Motorsports | [fastf1](https://opensource.pysport.org/project/fastf1) | Accesses and analyzes Formula 1 results, schedules, timing data, and telemetry. | Python |
| Motorsports | [f1dataR](https://opensource.pysport.org/project/f1dataR) | Obtains Formula 1 data via the Jolpica API and the unofficial F1 live-timing API. | R |
| Cricket | [cricketdata](https://opensource.pysport.org/project/cricketdata) | Downloads international and domestic cricket match data from ESPNcricinfo and Cricsheet. | R |

---
