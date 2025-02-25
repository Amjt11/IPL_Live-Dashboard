# IPL_Live-Dashboard

## Business Problem Statement

The Indian Premier League (IPL) 2024 lacks a unified platform offering real-time match updates, player statistics, and team rankings. Fans and analysts currently rely on fragmented sources, hindering seamless access to comprehensive information. A single, user-friendly dashboard with interactive visuals and in-depth analytics would streamline access, enhancing the experience for casual fans and professional analysts alike.


## Crafting the Solution
Addressing this challenge involves developing a unified and user-friendly dashboard that provides comprehensive IPL-related information in real time. Such a dashboard would empower users with up-to-date match scores, player statistics, and team rankings, catering to a diverse audience that includes casual fans and seasoned analysts. Bridging this gap would enhance user engagement throughout the IPL 2024 season.


Link to published Power BI report:  https://app.powerbi.com/groups/me/reports/d38e09c3-1569-4531-9f64-ce9d9e5e8c4a/ReportSectione5427cc19ba91920038e?experience=power-bi

---

## Leveraging Data Sources
The dataset is sourced from APIs using:
- The Rapid API Hub: [Rapid API Hub](https://rapidapi.com/hub)
- Cricbuzz: [Cricbuzz API](https://rapidapi.com/cricketapilive/api/cricbuzz-cricket)
These sources offer live data and comprehensive cricket-related information, ensuring the dashboard remains dynamically updated to reflect the latest IPL 2024 match developments.

---


## Understanding the Dataset Structure
The dataset comprises multiple tables, each serving a distinct purpose and containing specific information relevant to IPL matches.

## Key Tables and Columns
### Live Match Information Table:
- **Live Match ID**: A unique identifier for each match. This is used to differentiate between different matches in the dataset.

- **Player_Info**: This section contains details about players, such as their names, teams, and roles (batsman, bowler, all-rounder, etc.).

- **Points Table**: Displays the current standings of the teams in the league based on their wins, losses, and points earned.

### API Live Score Table:
- **Live Team Score**: Provides the current score of the teams in live matches. It typically includes runs scored, wickets lost, and overs completed.

- **Live Batsman Score**: Contains the batting statistics of individual players in the live matches, such as runs scored, balls faced, and strike rate.

- **Live Bowler Score**: Contains bowling statistics, including wickets taken, runs conceded, and overs bowled.

- **Live Toss Info**: Provides information about the toss result in the live matches, including which team won the toss and their choice (batting or bowling).

## Implementing API Calls and Data Retrieval
The data from the **Rapid API** Hub and **Cricbuzz** is retrieved using API calls, where each call pulls specific data (like live scores or player information) into the Power BI dataset. The dataset updates dynamically, reflecting the **real-time changes** in the IPL 2024 matches, ensuring that the dashboard provides live and accurate information.


## Structuring the Report
The report consists of two primary pages: a live dashboard showcasing real-time IPL 2024 match data and a points table page providing team rankings and detailed performance metrics.

### 1. Live Match Score Page
This section shows the current score of the ongoing match, including runs scored, wickets taken, overs bowled, and target (if batting second). It updates in real time, giving users an up-to-date view of the match's progress.

#### A)    Playing Batsmen

- This section highlights the current batsmen at the crease, providing their individual scores, including runs scored, balls faced, and strike rate.
- This information is crucial for fans wanting to track the performance of their favourite players.

#### B)    Team Batting Performance

- Both teams' batting performances are detailed here, including a breakdown of the scores in both the first and second innings.
- Users can see how teams are performing over time, offering a comprehensive overview of the match's batting dynamics.

#### C)    Bowling Performance

- This section provides statistics on the bowling performance, listing bowlers' names, overs bowled, wickets taken, and runs conceded. 
- It allows users to understand how each bowler contributes to the match's outcome.

#### D)   4s, 6s, and 2-Run Scores

This section adds a deeper level of insight by showing the number of 4s, 6s, and 2-run scores made by each batsman.
- This helps users identify which batsmen are hitting boundaries and keeping the scoreboard moving.

### Special Features:

**Dynamic Image Change**

- A unique feature of this dashboard is that the background images change based on the match and score. 
- This adds a visually appealing element to the dashboard, making it more engaging for users.\


### 2. Points Table Page
This page offers an overview of the IPL 2024 team standings and performance metrics. It is designed to give users a clear understanding of the tournament's current state. The page is divided into two main sections: the top section displays the tournament points table and the bottom section highlights individual team performance.

 #### A)    Top Section: Tournament Points Table

This section presents the overall standings of the IPL teams. It includes the following columns:

**Team Name**: Lists the names of the participating teams.

**Matches Played**: The total number of matches each team has played.

**Wins**: The total number of matches won by each team.

**Losses**: The total number of matches each team has lost.

**Points**: The accumulated points are based on wins and losses.

**Net Run Rate (NRR)**: Indicates the net run rate, a key metric for ranking teams with equal points.


#### B)    Bottom Section: Team Performance Details

This section provides more detailed information about each team, including the following columns:

**Captain**: The name of the team's captain, along with an image for easier identification.

**Matches Played**: The total number of matches the team has played in the tournament.

**Wins**: The total number of matches won.

**Losses**: The total number of matches lost.

**Points**: The points accrued based on the tournament rules.

**Net Run Rate (NRR)**: Displays the team's net run rate.

This section allows users to quickly understand the performance of individual teams, including their captains, win-loss records, and other crucial statistics.


### Special Features

**Dynamic Updates**

- This page is dynamic, with real-time updates reflecting the latest results and team standings. 
- This feature ensures that users always have access to the most current information.

**Interactive Elements**

- Includes interactive elements such as tooltips or clickable sections that provide additional insights when hovering over or selecting specific data points.


 


