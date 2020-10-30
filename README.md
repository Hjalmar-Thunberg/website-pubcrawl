url: https://nameless-shelf-03104.herokuapp.com/

## Getting started

```bash
# Clone repository
git clone git@git.ita.chalmers.se:courses/dit341/group-00-web.git

# Change into the directory
cd group-00-web

# Setup backend
cd server && npm install
npm run dev

# Setup frontend
cd client && npm install
npm run serve
```

> Check out the detailed instructions for [backend](./server/README.md) and [frontend](./client/README.md).

## System Definition (MS0)

### Purpose

Our system will provide information about local bars based on the user location and search criteria. The user can register to the website and add personal reviews or change the menu to the chosen bars. In addition, there will be an events page can be viewed and edited by registered users to create an event, such as e.g. a Barcrawl.

### Pages

- **Home** displays a map overlay of local bars, a list of bars that can be sorted for different criterias and give a short description of the displayed bars.
- **Bar** gives detailed information of the selected bar, let registered users add reviews and add drinks to the menu.
- **User** let users register, sign in, view and edit their user account.
- **Event** gives an overview of created events, let registered users create new events and edit their created events.

### Entity-Relationship (ER) Diagram

![ER Diagram](./images/er_diagram.png)

## Teaser (MS3)
Created by:
[Christian O'Neill](https://git.chalmers.se/oneillc)
[Hugo Hempel](https://git.chalmers.se/hugohe)
[Hjalmar Thunberg](https://git.chalmers.se/hjathu)
![Teaser](./images/teaser.png)
