# AIPL-Manager
Artificially Intelligent Premier League (AIPL) Manager

This project seeks to build a AI model for choosing and maintaining a Fantasy Premier League (FPL) team throughout a season. The [FPL](https://fantasy.premierleague.com/) is the largest English football fantasy game. It consists of using a bank of 100 million to pick a team from any of the current clubs which recieve points for each gameweek. Every week the "managers" can swap out players and makeother decisions. For a more detailed review of the rules and options see the above link.

Big thanks to [Vaastav Anand](https://github.com/vaastav) for his [GitHub repo](https://github.com/vaastav/Fantasy-Premier-League) containing the majority of the FPL data used for this project. This repo is included as a subtree -- the following commands are used to interact with it:

- Added remote with `git remote add -f fpl-data git@github.com:vaastav/Fantasy-Premier-League.git`
- Merge with `git merge -s ours --no-commit --allow-unrelated-histories fpl-data/master`
- Copy history with `git read-tree --prefix=fpl-data/ -u fpl-data/master`
- Update with `git pull -s subtree fpl-data master`
