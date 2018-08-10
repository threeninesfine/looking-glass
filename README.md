# looking-glass
Live poker cardroom analytics in SEA, WA

# Version 1.0
+ Importing scripts from previous work

# Background

Game selection is critical to live poker success.
Unfortunately, cardrooms spreading live poker are geographically separated.

Fortunately, cardrooms often publish information on key factors
relevant for making the best decision for where to play.

The looking-glass is a tool that queries publicly available websites
Seattle area cardrooms publish on game statistics.

# Description

Relevant data collected includes

+ Game stakes (e.g. $1/$2 no-limit texas hold'em)
+ Number of tables
+ Number of players on the waitlist

Other collected information relevant for 'Choosing when to play' include:

+ Date of query, including day of week
+ Time of query
+ Individuals on waitlist (when applicable)

# Implementation
The looking-glass has three components:

1. Query the websites and scrape key data points
2. Store collected data in a database for easy analytics use
3. Analyze stored data for current decision making and historical analytics

As of 10/8/18, only scripts for component (1) are available,
and exist in inflexible scripts.

# Short-term goals
First stop along the project is refactoring existing code to be reusable.

+ Import previous scripts for querying area cardrooms
+ Refactor scripts for reusability
+ Make list of cardrooms and sites to collect information
+ Save example versions of websites to serve as proof-of-concept examples


# Long-term goals

Along the way, emphasis will be placed on learning the following:

## Querying scripts
+ Documentation (parameters, description of output)
+ Flexible code (functions, sourced by main file)

## Database
+ Implementation choice (SQL 'flavor')
+ Data input (semi-automated scripts, manual option for phone-collected data)
+ Database management concepts (secure storing and querying)

## Analytics
+ Optimal timing: Day-of-week and time-of-week analysis
+ Data fidelity checks: comparing historical data with "boots on the ground" information
