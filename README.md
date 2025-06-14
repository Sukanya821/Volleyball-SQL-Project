# Volleyball-SQL-Project

This project demonstrates how to design and query a relational database for managing data related to volleyball athletes, teams, and matches.

## 🎯 Objectives

- Design normalized tables to store player, team, and match statistics
- Write SQL queries to extract insights such as top scorers, team performance, and player age distribution

## 🧱 Database Schema

The schema includes the following tables:
- `players`: stores personal information about athletes
- `teams`: stores team details
- `matches`: records match information
- `player_stats`: stores individual performance in each match

All schema definitions are in [`schema/create_tables.sql`](schema/create_tables.sql)

## 🧠 Example Queries

- Top 5 scorers in the league → [`queries/top_scorers.sql`](queries/top_scorers.sql)
- Average player age by team → [`queries/player_age_distribution.sql`](queries/player_age_distribution.sql)
- Team win/loss stats → [`queries/match_stats_by_team.sql`](queries/match_stats_by_team.sql)

## 🛠️ Tools Used

- SQL (PostgreSQL / MySQL)
- DBeaver / DB Browser / pgAdmin

## 🖼️ Sample Output

See sample results in the `screenshots/` folder.

## 📂 Dataset

Sample dataset included in `dataset_sample.csv` (generated or fictional data)
