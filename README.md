# untap-upkeep-draw
A free web app for in-browser simulated games of Magic: the Gathering (which is a trading card game made and owned by Wizards of the Coast).

## Roadmap
- [ ] get a server set up and ready to go
- [ ] figure out how anonymous sessions will work (look at https://github.com/jbowens/codenames for inspiration)
- [ ] implement data sync between clients on the same session (card state e.g. position, tapped/untapped)
- [ ] implement decklist importer
- [ ] backup scryfall card data on our server
- [ ] figure out keypress events (using keyboard buttons to interact with cards in addition to mouse)
- [ ] figure out user accounts
- [ ] figure out animations (drag and drop, tap, flip)
- [ ] figure out how to do ads

## Tech Stack
- Front-end: NextJS, Typescript, Sass?
- Back-end: Express...? Maybe Go?
- server: Debian Stable?
- database:
  - non-relational
  - redis if server has enough RAM
  - maybe mongoDB?

## Low Priority Features
- [ ] let users upload custom images for card sleeves, card alts, and table background image
- [ ] customize keybinds
- [ ] built-in card search (literally just use scryfall)
- [ ] if we ever get big enough, migrate to AWS or something

### Tentative (Default) Keybinds
| Action | Keybind(s) |
| ---    | ---        |
| pog    | pog        |
