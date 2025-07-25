# Codex Darts Tournament Manager

Backend made with help from Codex, Frontend made with help from Claude 4

This repository contains a simple web-based application for managing darts tournaments. Any number of players from four up to twelve can be entered. All players start in a single group (Group A) before entering a knockout bracket seeded by the group results. Tournament of 4-12 players are possible.

## Web Usage

Run the Flask server and open the page in your browser:

```bash
python app.py
```

Then navigate to `http://localhost:5000/` to use the tournament manager.

Active line 633 and deactivade line 631 in app.py to run on network

The main page allows an administrator to log in. Use the default credentials:

```
username: admin
password: password
```

Only an authenticated admin can create or modify tournaments.

## CLI Usage

A command-line implementation is also available. Run:

```bash
python tournament.py
```

Follow the prompts to enter player names and match scores. The script shuffles the players into Group A, calculates standings, and manages the knockout bracket.
