# website.md

# PakVision – Pakistan Cricket Analytics Dashboard**

**Version:** 1.0
**Project Type:** Frontend Web Application
**Developer:** Abdullah Shahzad
**Technology Stack:** HTML5, CSS3, JavaScript (ES6), Chart.js, JSON
**Deployment:** GitHub Pages / Netlify / Vercel

---

# 1. Project Overview

## Introduction

PakVision is a modern sports analytics web application focused on the Pakistan Cricket Board (PCB). The platform provides users with detailed information about PCB, Pakistan's men's cricket team, player statistics, historical performance, interactive comparisons, team analytics, and future squad predictions.

The application is developed entirely using **HTML, CSS, and JavaScript**, making it lightweight, fast, responsive, and easy to deploy.

---

# 2. Purpose

The purpose of PakVision is to:

* Present comprehensive information about the Pakistan Cricket Board.
* Showcase Pakistan cricket players with detailed career statistics.
* Allow users to compare players and teams visually.
* Display historical match performances.
* Predict future Pakistan squads using a JavaScript-based scoring system.
* Demonstrate frontend development and UI/UX skills through a professional dashboard.

---

# 3. Project Objectives

* Build a responsive sports analytics dashboard.
* Display PCB information in an engaging format.
* Visualize cricket statistics using interactive charts.
* Provide player and team comparison tools.
* Create a future squad prediction feature.
* Use modular HTML, CSS, and JavaScript architecture.
* Ensure excellent performance and accessibility.

---

# 4. Target Audience

### Primary Users

* Cricket fans
* PCB supporters
* Sports enthusiasts
* Students
* Recruiters reviewing frontend portfolios

### Secondary Users

* Cricket analysts
* Coaches
* Journalists

---

# 5. Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript (ES6)

### Libraries

* Chart.js
* Font Awesome
* Google Fonts

### Data Source

* Local JSON Files

### Deployment

* GitHub Pages
* Netlify
* Vercel

---

# 6. Website Features

## Homepage

The homepage serves as the central dashboard of PakVision.

### Components

* Hero Banner
* PCB Introduction
* Featured Players
* Quick Statistics
* Dashboard Cards
* Navigation Bar
* Search Bar
* Quick Access Buttons
* Footer

---

## PCB Page

Displays detailed information about the Pakistan Cricket Board.

### Content

* History
* Vision
* Mission
* Chairman
* Coaching Staff
* Domestic Cricket Structure
* Stadiums
* International Achievements
* PCB Timeline

---

## Players Page

Displays all Pakistan players.

### Features

* Player Cards
* Search Players
* Filter by Role
* Sort by Runs
* Sort by Wickets
* Filter by Format
* Responsive Grid Layout

Each player card includes:

* Player Photo
* Name
* Role
* Batting Style
* Bowling Style
* Age
* View Profile Button

---

## Player Profile

Displays complete player information.

### Personal Information

* Name
* Age
* Role
* Batting Style
* Bowling Style
* Debut
* Jersey Number

### Career Statistics

Tests

ODIs

T20Is

Overall

### Batting

* Matches
* Innings
* Runs
* Average
* Strike Rate
* Highest Score
* Hundreds
* Fifties

### Bowling

* Wickets
* Economy
* Bowling Average
* Best Figures

### Fielding

* Catches
* Run Outs

### Visualizations

* Runs by Year
* Wickets by Year
* Opponent Analysis
* Format Comparison
* Home vs Away Performance

---

# 7. Player Comparison

Users can compare any two Pakistan players.

### Comparison Metrics

* Matches
* Runs
* Batting Average
* Strike Rate
* Hundreds
* Fifties
* Wickets
* Economy
* Bowling Average
* Catches

### Output

* Comparison Table
* Radar Chart
* Bar Chart
* Winner Highlight
* Overall Performance Score

---

# 8. Teams Page

Displays major international cricket teams.

Each card contains:

* Team Logo
* Captain
* Coach
* ICC Ranking
* Matches Played
* Win Percentage

---

# 9. Team Comparison

Users can compare Pakistan with other cricket nations.

Supported Teams:

* Pakistan
* India
* Australia
* England
* South Africa
* New Zealand
* Sri Lanka
* Bangladesh
* Afghanistan
* West Indies

Comparison Metrics:

* Matches
* Wins
* Win Percentage
* Batting Average
* Bowling Average
* ICC Ranking
* ICC Trophies

---

# 10. Match History

Displays Pakistan's historical matches.

Each match includes:

* Opponent
* Date
* Venue
* Tournament
* Result
* Score
* Top Batter
* Top Bowler
* Player of the Match

Filters:

* Year
* Opponent
* Format
* Tournament

---

# 11. Analytics Dashboard

Interactive dashboard featuring:

* Top Run Scorers
* Top Wicket Takers
* Win Percentage
* Home vs Away Performance
* Format Comparison
* Team Statistics
* Performance Trends

Charts used:

* Bar Chart
* Pie Chart
* Doughnut Chart
* Radar Chart
* Line Chart

---

# 12. Future Squad Prediction

Predicts Pakistan's strongest playing XI using predefined data.

### Selection Factors

* Current Form (40%)
* Career Statistics (30%)
* Fitness (20%)
* Potential (10%)

### Output

* Playing XI
* Bench Players
* Captain
* Vice Captain
* Selection Reasoning

---

# 13. Records Page

Displays cricket records including:

* Most Runs
* Most Wickets
* Highest Scores
* Fastest Century
* Fastest Fifty
* Best Bowling Figures
* Most Catches
* Highest Partnerships

---

# 14. Search & Filter

Global search functionality for:

* Players
* Teams
* Matches

Filter options:

* Role
* Format
* Age
* Batting Style
* Bowling Style

Sorting options:

* Runs
* Wickets
* Average
* Strike Rate
* Alphabetical

---

# 15. Folder Structure

```text
PakVision/
│
├── index.html
├── pcb.html
├── players.html
├── player.html
├── comparison.html
├── teams.html
├── analytics.html
├── prediction.html
├── matches.html
├── records.html
├── about.html
│
├── css/
│   ├── style.css
│   ├── navbar.css
│   ├── dashboard.css
│   ├── cards.css
│   └── responsive.css
│
├── js/
│   ├── app.js
│   ├── players.js
│   ├── comparison.js
│   ├── analytics.js
│   ├── prediction.js
│   ├── search.js
│   └── charts.js
│
├── data/
│   ├── players.json
│   ├── teams.json
│   ├── matches.json
│   ├── records.json
│   └── predictions.json
│
├── images/
│
└── assets/
```

---

# 16. Non-Functional Requirements

### Performance

* Fast loading
* Optimized assets
* Lazy loading for images

### Responsiveness

* Mobile
* Tablet
* Desktop

### Accessibility

* Semantic HTML
* Keyboard navigation
* Alt text for images
* High contrast colors

### Browser Support

* Chrome
* Firefox
* Edge
* Safari

---

# 17. Future Enhancements

* Live Cricket API Integration
* User Authentication
* Real-Time Match Scores
* AI-Based Squad Prediction
* Favorite Players
* Export Reports
* Dark/Light Theme Toggle

---

# 18. Success Criteria

The project will be successful if users can:

* Navigate the website easily.
* Explore PCB information.
* View player profiles.
* Compare players and teams.
* Analyze statistics through interactive charts.
* Generate future Pakistan squads.
* Access the website smoothly across all devices.

---

# 19. Conclusion

PakVision is a frontend-focused cricket analytics platform built to showcase modern web development practices using HTML, CSS, and JavaScript. It combines responsive design, data visualization, interactive comparisons, and predictive features into a polished, portfolio-ready application that highlights both technical skills and user-centered design.
 Product Requirements Document (PRD)

# **PakVision – Pakistan Cricket Analytics Dashboard**

**Version:** 1.0
**Project Type:** Frontend Web Application
**Developer:** Abdullah Shahzad
**Technology Stack:** HTML5, CSS3, JavaScript (ES6), Chart.js, JSON
**Deployment:** GitHub Pages / Netlify / Vercel

---

# 1. Project Overview

## Introduction

PakVision is a modern sports analytics web application focused on the Pakistan Cricket Board (PCB). The platform provides users with detailed information about PCB, Pakistan's men's cricket team, player statistics, historical performance, interactive comparisons, team analytics, and future squad predictions.

The application is developed entirely using **HTML, CSS, and JavaScript**, making it lightweight, fast, responsive, and easy to deploy.

---

# 2. Purpose

The purpose of PakVision is to:

* Present comprehensive information about the Pakistan Cricket Board.
* Showcase Pakistan cricket players with detailed career statistics.
* Allow users to compare players and teams visually.
* Display historical match performances.
* Predict future Pakistan squads using a JavaScript-based scoring system.
* Demonstrate frontend development and UI/UX skills through a professional dashboard.

---

# 3. Project Objectives

* Build a responsive sports analytics dashboard.
* Display PCB information in an engaging format.
* Visualize cricket statistics using interactive charts.
* Provide player and team comparison tools.
* Create a future squad prediction feature.
* Use modular HTML, CSS, and JavaScript architecture.
* Ensure excellent performance and accessibility.

---

# 4. Target Audience

### Primary Users

* Cricket fans
* PCB supporters
* Sports enthusiasts
* Students
* Recruiters reviewing frontend portfolios

### Secondary Users

* Cricket analysts
* Coaches
* Journalists

---

# 5. Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript (ES6)

### Libraries

* Chart.js
* Font Awesome
* Google Fonts

### Data Source

* Local JSON Files

### Deployment

* GitHub Pages
* Netlify
* Vercel

---

# 6. Website Features

## Homepage

The homepage serves as the central dashboard of PakVision.

### Components

* Hero Banner
* PCB Introduction
* Featured Players
* Quick Statistics
* Dashboard Cards
* Navigation Bar
* Search Bar
* Quick Access Buttons
* Footer

---

## PCB Page

Displays detailed information about the Pakistan Cricket Board.

### Content

* History
* Vision
* Mission
* Chairman
* Coaching Staff
* Domestic Cricket Structure
* Stadiums
* International Achievements
* PCB Timeline

---

## Players Page

Displays all Pakistan players.

### Features

* Player Cards
* Search Players
* Filter by Role
* Sort by Runs
* Sort by Wickets
* Filter by Format
* Responsive Grid Layout

Each player card includes:

* Player Photo
* Name
* Role
* Batting Style
* Bowling Style
* Age
* View Profile Button

---

## Player Profile

Displays complete player information.

### Personal Information

* Name
* Age
* Role
* Batting Style
* Bowling Style
* Debut
* Jersey Number

### Career Statistics

Tests

ODIs

T20Is

Overall

### Batting

* Matches
* Innings
* Runs
* Average
* Strike Rate
* Highest Score
* Hundreds
* Fifties

### Bowling

* Wickets
* Economy
* Bowling Average
* Best Figures

### Fielding

* Catches
* Run Outs

### Visualizations

* Runs by Year
* Wickets by Year
* Opponent Analysis
* Format Comparison
* Home vs Away Performance

---

# 7. Player Comparison

Users can compare any two Pakistan players.

### Comparison Metrics

* Matches
* Runs
* Batting Average
* Strike Rate
* Hundreds
* Fifties
* Wickets
* Economy
* Bowling Average
* Catches

### Output

* Comparison Table
* Radar Chart
* Bar Chart
* Winner Highlight
* Overall Performance Score

---

# 8. Teams Page

Displays major international cricket teams.

Each card contains:

* Team Logo
* Captain
* Coach
* ICC Ranking
* Matches Played
* Win Percentage

---

# 9. Team Comparison

Users can compare Pakistan with other cricket nations.

Supported Teams:

* Pakistan
* India
* Australia
* England
* South Africa
* New Zealand
* Sri Lanka
* Bangladesh
* Afghanistan
* West Indies

Comparison Metrics:

* Matches
* Wins
* Win Percentage
* Batting Average
* Bowling Average
* ICC Ranking
* ICC Trophies

---

# 10. Match History

Displays Pakistan's historical matches.

Each match includes:

* Opponent
* Date
* Venue
* Tournament
* Result
* Score
* Top Batter
* Top Bowler
* Player of the Match

Filters:

* Year
* Opponent
* Format
* Tournament

---

# 11. Analytics Dashboard

Interactive dashboard featuring:

* Top Run Scorers
* Top Wicket Takers
* Win Percentage
* Home vs Away Performance
* Format Comparison
* Team Statistics
* Performance Trends

Charts used:

* Bar Chart
* Pie Chart
* Doughnut Chart
* Radar Chart
* Line Chart

---

# 12. Future Squad Prediction

Predicts Pakistan's strongest playing XI using predefined data.

### Selection Factors

* Current Form (40%)
* Career Statistics (30%)
* Fitness (20%)
* Potential (10%)

### Output

* Playing XI
* Bench Players
* Captain
* Vice Captain
* Selection Reasoning

---

# 13. Records Page

Displays cricket records including:

* Most Runs
* Most Wickets
* Highest Scores
* Fastest Century
* Fastest Fifty
* Best Bowling Figures
* Most Catches
* Highest Partnerships

---

# 14. Search & Filter

Global search functionality for:

* Players
* Teams
* Matches

Filter options:

* Role
* Format
* Age
* Batting Style
* Bowling Style

Sorting options:

* Runs
* Wickets
* Average
* Strike Rate
* Alphabetical

---

# 15. Folder Structure

```text
PakVision/
│
├── index.html
├── pcb.html
├── players.html
├── player.html
├── comparison.html
├── teams.html
├── analytics.html
├── prediction.html
├── matches.html
├── records.html
├── about.html
│
├── css/
│   ├── style.css
│   ├── navbar.css
│   ├── dashboard.css
│   ├── cards.css
│   └── responsive.css
│
├── js/
│   ├── app.js
│   ├── players.js
│   ├── comparison.js
│   ├── analytics.js
│   ├── prediction.js
│   ├── search.js
│   └── charts.js
│
├── data/
│   ├── players.json
│   ├── teams.json
│   ├── matches.json
│   ├── records.json
│   └── predictions.json
│
├── images/
│
└── assets/
```

---

# 16. Non-Functional Requirements

### Performance

* Fast loading
* Optimized assets
* Lazy loading for images

### Responsiveness

* Mobile
* Tablet
* Desktop

### Accessibility

* Semantic HTML
* Keyboard navigation
* Alt text for images
* High contrast colors

### Browser Support

* Chrome
* Firefox
* Edge
* Safari

---

# 17. Future Enhancements

* Live Cricket API Integration
* User Authentication
* Real-Time Match Scores
* AI-Based Squad Prediction
* Favorite Players
* Export Reports
* Dark/Light Theme Toggle

---

# 18. Success Criteria

The project will be successful if users can:

* Navigate the website easily.
* Explore PCB information.
* View player profiles.
* Compare players and teams.
* Analyze statistics through interactive charts.
* Generate future Pakistan squads.
* Access the website smoothly across all devices.

---

# 19. Conclusion

PakVision is a frontend-focused cricket analytics platform built to showcase modern web development practices using HTML, CSS, and JavaScript. It combines responsive design, data visualization, interactive comparisons, and predictive features into a polished, portfolio-ready application that highlights both technical skills and user-centered design.

## website link 
https://abdspcb.netlify.app/