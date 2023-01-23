# Bot Battlr
Welcome to Bot Battlr, the one and only spot in the known universe where you can custom build your own Bot Army. Here's the scenario: a galactic overlord has hired you, a galactic web developer, to develop a galactic web app that will allow them to browse through a list of robots, view a robot's details, and, enlist a bot into their army. This is a react application that implements these features for a user.

# Instructions
For this project, you’ll be building out a React application that displays a
list of available bots, among other features. Try your best to find the right
places to insert code into the established code base.

# Setup
Once you have the plan in place for the application you want to build take the following steps:
Create a new project folder.
Create a new GitHub repository.
In your project directory, create a db.json file and use this data Links to an external site.for your server DB.
Run this command to get the backend started: json-server --watch db.json
Test your server by visiting this route in the browser: http://localhost:8001/bots

# Core Deliverables
As a user, I should be able to:
 See profiles of all bots rendered in `BotCollection`.
 Add an individual bot to my army by clicking on it. The selected bot should
  render in the `YourBotArmy` component. The bot can be enlisted only **once**.
  The bot **does not** disappear from the `BotCollection`.
Release a bot from my army by clicking on it. The bot disappears from the
  `YourBotArmy` component.
Discharge a bot from their service forever, by clicking the red button marked
  "x", which would delete the bot both from the backend and from the
  `YourBotArmy` on the frontend.

# Advanced Deliverables
As a user, I should be able to:

- Choose if I want to enlist a bot into my army or just see their data. Clicking
  on the card should instead display a show view (`BotSpecs`) for that bot,
  which should replace `BotsCollection`. BotSpecs should have two buttons: one
  to go back to the list view and another to enlist that bot. 
- Sort bots by their health, damage or armor. For this, create a new component,
  `SortBar`.
- When I enlist a bot it will be **removed** from the `BotCollection` and added
  to `YourBotArmy`.
- Filter bots by their class. We can select a few filters at the same time.
- Sort bots by their health, damage or armor. For this, create a new component,
  `SortBar`.
- Only enlist **one** bot from each `bot_class`. The classes are
  `["Support", "Medic", "Assault", "Defender", "Captain", "Witch"]`.