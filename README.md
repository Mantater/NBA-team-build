# NBA team build

## Description
A fun project where you can create your dream basketball starter team using real NBA player data.
The project collects player and team info from the `nba_api`
 (an open-source Python package) and stores it locally in an `SQLite` database. From there, you can filter players and build your custom team of up to 5 members.

## Installation
1. Clone repo
```sh
git clone https://github.com/Mantater/NBA-team-build
```
2. Install dependencies
```sh
pip install -r requirements.txt
```
3. Run project
```sh
python Main.py
```

## Usage
1. Download or clone all files.
2. Database `nba_info` is already populated and ready to use.
3. Run `NBADataCollector.py` — this will populate or update the database with player/team info.
```sh
python NBADataCollector.py
```
4.Run `Main.py` — this launches the main program for team building.
5. Filter players by attributes (`team`, `position`, `active` status, etc.).
6. Add selected players to MyTeam.
7. MyTeam Rules:
	- Max cap = 5 players
	- You can remove a player anytime by opening MyTeam

## Features
- Fetches real NBA player and team data from `nba_api`
- Stores data locally in `SQLite` for offline access
- Retry system for API timeouts and skipped players
- Filter and search players before adding to your team
- Create and manage your own dream starter 5

## License
This project uses the MIT License.
- The code in this repo is open-source and free to use.
- Data is fetched from NBA.com via the community-made `nba_api`.
(**Please note that NBA data is subject to NBA.com’s Terms of Use, so review them if using this project commercially.**)
